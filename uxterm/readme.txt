1. cp Xresources ~/.Xresources

2. xrdb -merge ~/.Xresources

3. To apply it for this session you need to run
        xrdb -merge ~/.Xresources

4. To make it effective across sessions you need to add it to the autostart
   file of the window manager. Eg: xfce4-session-settings

5. Now if you open uxterm you should see the new terminus font
