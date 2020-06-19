nw-tray-experiment
==================

Debugging of NW.js tray icon code on Linux. This probably uses the XFCE
[StatusNotifierItem] specification.

Related to Gitter Desktop [issue #296][296].


Running
-------

`npm start` should bring up the test app.

After you click "OK" on the initial alert box, this successfully adds a new
icon to the tray, in my case, [xfce4-panel] 4.12.1 configured with the
[Notification Area] tray that comes with it. (The code comes from the
Synopsis section of [References » Tray][nw:tray] in the NW.js
documentation.) However, neither left- nor right-clicking on the icon
brings up a menu. (Left and right clicks on other apps' icons do work,
doing different things in some cases.)



<!-------------------------------------------------------------------->
[296]: https://gitlab.com/gitlab-org/gitter/desktop/-/issues/296
[StatusNotifierItem]: https://www.freedesktop.org/wiki/Specifications/StatusNotifierItem/
[notification area]: https://docs.xfce.org/xfce/xfce4-panel/systray
[nw:tray]: https://nwjs.readthedocs.io/en/latest/References/Tray/
[xfce4-panel]: https://docs.xfce.org/xfce/xfce4-panel/start
