# PyMenu
A Python 3 based framework for creating simple and intuitive text-based menu interfaces.

---

Supported operating systems: Windows

Note: The msvcrt library is the only thing that is preventing this from being able to run on other operating systems.

---

Main features: 
- Can take user input in the form of strings as well as boolean checkboxes. 
- Can display information in the form of text boxes (With word-wrapping and scrolling functionality)
- Menus can contain many different buttons and inputs simultaneously. Scrolling functionality will be used if the number of elements is too large.
- Input is asynchronous (ie the program doesn't halt when an input is being taken)
- Menus are resized dynamically depending on the number and scale of the elements within them.
- Buttons are linked to existing functions within the program.
- Menus can be stacked. If one is closed then the previous one is started up again.

---

Navigation:
- Left & Right Arrow Keys: Select horizontal options.
- Up & Down Arrow Keys: Select vertical options.
- Enter: Activates the selected button.
- Space: Toggle checkboxes.
- Tab: Selects the next button/input.
- F5: Redraws the current menu.
- F1: Displays this navigation information.
- Escape: Closes the current menu.
- Any option highlighted in blue is currently selected.
