# bltcrt
// About //
    
    BLTCRT is a python lib, based on the BearLibTerminal* library, to emulate
    a console/terminal like, environment for application developing on the
    terminal.
    
    BearLibTerminal is used to build Rogue-like games. BLTCRT expands its 
    usage to an easier way to write console-like programs. The names of the 
    functions are the same as in Mystic Python (MPY) and also my other lib.
    PyCrt (https://github.com/xqtr/pycrt). This way, writing apps/mods to any
    of these platforms is like using almost the same code, only a few changes
    are needed.
    
    Also, because BLTCRT and BearLibTerminal are written in Python, you can
    run an application made with it, in any modern system (Windows, Unix/Linux,
    RPi) that uses Python3 and has a GUI. BLTCRT and BearLibTerminal are cross
    platform libs.
    
    You can see a full written application using BLTCRT, by downloading the
    file tdfstudio2.zip from Another Droid BBS or any FSXnet, DOREnet, SCInet,
    affiliate BBS. This file contains an app that displays TheDrawFonts and
    also can manipulate the files.
    
    You can use any .TTF font and give your app the look of a DOS app or an 
    Amiga one. BearLibTerminal/BLTCRT supports Unicode characters and many 
    fonts are included in the ./fonts directory.
    
    
    *http://foo.wyrd.name/en:bearlibterminal
    
    // Installation //
    
    Uncompress the archive in a desired directory. Make sure you have 
    installed python3 and the following packages:
    
     [] bearlibterminal 
        http://foo.wyrd.name/en:bearlibterminal
        
        install by using pip:
        pip install bearlibterminal
    
    
    // Usage //
    
    Import the library, best in this way:
        
        import bltcrt as crt
    
    ...now you can use MPY-like / Pascal-like functions like:
    
      writexy()
      readkey()
      textcolor()
      textbackground()
      clrscr()
    
    ...and more.
    
    You can always use the BearLibTerminal object for more advanced things, 
    like using the mouse. At the git site of BearLibTerminal you will find
    some very good examples.
    
    BLTCRT is not a replacement of BearLibTerminal, it's just an encapsulation
    of it to a more MPY-ish/Pascal-ish way, for writing cross-platform (BBS,
    Linux Terminal, Windows/Linux GUI, RPi) utilities, apps, mods.
