# Fallout_Terminal_Game
This is a simple recreation of the "hacking" minigame from Fallout meant for the Raspberry Pi using Python and Curses.

You can find the complete bill of materials here:

https://www.element14.com/community/docs/DOC-91315/l/episode-373-raspberry-pi-fallout-terminal-pc

TODO:
- [ ] Prevent matched braces from crossing over words or removed duds
- [ ] Prevent matched braces from appearing in their entirety after having been used
- [ ] Prevent matches braces from spanning multiple lines
- [ ] Abstract writing to the console to allow choice of curses or tcod (Windows PDCurses doesn't properly set colour)
- [ ] Allow for platform detection so it can use RPi GPIO for input when available
- [ ] Remove brand names and modern tech from the word list
- [ ] Create difficulty modes based on similarity of words to the password
