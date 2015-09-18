# mintty
Automatically exported from code.google.com/p/mintty
> mintty is a terminal emulator for [Cygwin](http://www.cygwin.com/) and [MSYS](http://www.mingw.org/wiki/MSYS). In Cygwin, it is installed as the default terminal by Cygwin's [setup.exe](http://www.cygwin.com/setup.exe). IN MSYS, the mintty package can be installed with the command `mingw-get install mintty`. Alternatively, binaries for Cygwin 1.7, 1.5 and MYSY can be found in the downloads page.

### feature include:
- Xterm-compatible terminal emulation.
- Native Windows user interface with a simple options dialog.
- Easy copy & paste.
- Drag & drop of text, files and folders.
- Ability to open files and URLs with Ctrl+click.
- Comprehensive character encoding support, including UTF-8.
- Wide character display and Windows IME support.
- Window transparency, including glass effect on Vista and 7.
- 256 colours.
- Fullscreen mode.
- Options stored in a text file. No registry entries.
- Small program size and quick scrolling.
  
Mintty works on all Windows versions from Windows 2000 onwards. Similarly to other Cygwin/MSYS terminals based on [pseudo terminal](http://en.wikipedia.org/wiki/Pseudo_terminal) ("pty") devices, however, mintty is not a full replacement for the Windows Command Prompt. While native console programs with simple text output usually work fine, interactive programs often have problems, although sometimes there are workarounds.

The Cygwin package ships with a manual page that can be accessed with man mintty. A PDF version of the manual is available from the downloads page. Invoking mintty with the --help option shows a summary of available command line options. Keycodes, control sequences and some random tips can be found on the wiki.

Please report bugs or suggest enhancements via the issue tracker. Vote for any issues you'd particularly like to see addressed by starring them. The discussion group for all things mintty is mintty-discuss. General Cygwin questions should be sent to the [Cygwin mailing list](mailto://cygwin@cygwin.org).

Mintty is based on code from [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty) [0.60](http://the.earth.li/~sgtatham/putty/0.60/putty-src.zip) by Simon Tatham and [team](http://www.chiark.greenend.org.uk/~sgtatham/putty/team.html). The program icon comes from [KDE's Konsole](http://konsole.kde.org/). Mintty ties directly into Cygwin/MSYS and leaves out PuTTY's networking functionality, which is provided by packages such as [openssh](http://www.openssh.com/) and [inetutils](http://www.gnu.org/software/inetutils) instead. A number of PuTTY issues have been addressed.
