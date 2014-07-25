CATWM
=====

     /\___/\
    ( o   o )  Made by cat...
    (  =^=  )
    (        )            ... for cat!
    (         )
    (          ))))))________________ Cute And Tiny Window Manager

Summary
-------

catwm is a very simple and lightweight tiling window manager.
I will try to stay under 1000 SLOC.

Status
------
 * 25.07.14 -> v0.4

   -Minor changes in catwm.c

   -Added a x error handler (if other wm is running in the same display)...

 * 24.07.14 ->

   -Minor changes in catwm.c
  
 * 23.07.14

   -Removed function client_to_desktop, more buggy o_O

   -Desktops are now 10 aka 10 tags or workspaces...

   -Added a quick, and dirty hack in unmapnotify, for molest resize if have, more windows with dialogs...
  
   -Added catkill function, to close X, in dwm's style

 * 22.07.14

   -About: catwm -v,

   -Removed a obsolete header,

   -changed volume keybindings.

 * 21.07.14  
   -Numlock not affects keyboard shotcurts. 

   -Multiple desktops works now ok,

   -Added space to use a toolbar, ex: dzen2 

   -unmapnotify function, for, rares windows, ex: thunderbird, firefox...

    Before this, catwm crashes, with about dialogs or new window, from these windows..

 * 05.07.19 -> v0.3. Multiple desktops and correct some bugs
 * 30.06.10 -> v0.2. Back again \o/
 * 15.03.10 -> v0.2. The wm is functional -> I only use this wm!
 * 24.02.10 -> First release, v0.1. In this release 0.1, the wm is almost functional

Modes
-----

It allow the "normal" modes of tiling window managers:

    --------------
    |        |___|
    |        |___|
    | Master |___|
    |        |___|
    |        |___|
    --------------

Horizontal tiling mode:

    -------------
    |           |
    |  Master   |
    |-----------|
    | W |   |   |
    -------------

and fullscreen mode:

    -------------
    |           |
    | no        |
    | borders!  |
    |           |
    -------------

Installation
------------

In debian and derivatives: 

    # apt-get install build-essential libx11-dev xlibs-dev

If use slackware, archlinux, headers is present now, in default installation...

Need Xlib, then:

    $ nano config.h
    
    $ make
    
    # make install

    $ make clean

Bugs
----
 * No bugs for the moment ;) (I mean, no importants bugs ;)

Todo
----
 * Add multiple view ("desktop") >> "cutre" multihead supported, see not mine screenshot: http://a.pomf.se/ggylig.png
 
   And other not mine screenshot: http://a.pomf.se/mdtbvb.png

 * Switch to XCB

If you have some particular request, just send me an e-mail, and I will see for it!

Here a screenshot: http://a.pomf.se/qxwuno.png

License
-------

Licensed under MIT/X Consortium License, see [LICENSE][law] file for more copyright and license information.

  [law]: https://raw.githubusercontent.com/djmasde/catwm/master/LICENCE_DWM

Thanks
------

 * [the suckless team](http://suckless.org/)
 * [moetunes](https://github.com/moetunes)
 * [pyknite](https://github.com/pyknite)
