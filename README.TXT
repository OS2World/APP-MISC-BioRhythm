Comments about BIO

When you first enter the BIO program, you should enter your birthdate;
then click the "Ok" button.  If you hit <Return> after entering an input
line, it will actually start the program, but probably not with the
parameters you want.  Options can be changed with (Options...Dates)
and recorded in OS2.INI for automatic recall when the program is run
subsequently.

There is also a "Legend" option, which allows you to examine the legend
of the biorhythm chart; and you can use the scrollbar to view biorhythms
for the past and the future.

The program illustrates handling the mouse/keyboard interface, managing
dialog box input, system proportional font handling, use of child windows,
scroll bars, memory bitmaps, copying bitmaps to the clipboard, using the
OS2.INI file, accelerator keys, and subclassing the frame to modify its
behavior.


File List:

README.TXT	this file
BIO			Makefile
BIO.C		main() routine
BIO.DEF		Definition file
BIO.H		Header file (definitions)
BIO.ICO		Icon file
BIO.RC		Resource file
BIOCMD.C	Dialog procedures
BIOPAINT.C	WM_PAINT processing, date conversion routines
WNDPROC.C	Window procedures
