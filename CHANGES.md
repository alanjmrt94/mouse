# 0.8.0
- [All] Invokes callback with args when the right button is pressed, clicked and double clicked.
- [All] Invokes callback with args when the middle button is pressed, clicked and double clicked.
- [All] Add ability to set default fps for mouse.move().
- [All] Add missings definitions for right, left and middle clicks.
- [All] Add missings tests for right, left and middle clicks.
- [Linux] Fix linux segfault when no display.
- [Linux] Allow non-root users of appropriate groups to use module in Linux.
- [Linux] Fix mouse movements/hooks work, but mouse clicks do not.
##### Known issues:
- Segmentation fault (core dumped) when calling Gtk.menu popup (Linux) #104


# 0.7.1

- [All] Fixed errors and incorrect information on setup.py.
- [Windows] Fixed Windows segfault.
- [All] Applied pending bug fixes.


# 0.7.0

- [All] Fix Windows hook error (#1).
- [All] Add __main__ module, allowing `python -m mouse` to save and load events.


# 0.6.1

- [Windows] Fixed ctypes type-checking error.
- [All] Misc fixes to release process.


# 0.6.0

- Added README and API docs.
- Bump version to replace old library.


# 0.0.1

- Initial release, migrated from `keyboard` package.


