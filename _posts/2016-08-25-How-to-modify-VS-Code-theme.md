---
layout: page
title: How to modify MS Visual Studio Code Theme
---

Last year, Microsoft released [Visual Studio (VS) Code](https://code.visualstudio.com/) for free. I decided to use this IDE for python scripting since I took a [session](https://github.com/pythonkr/pyconapac-2016-files/raw/master/20160813-102-59-KimYoungwook.pdf) about it in [PyCon 2016](https://www.pycon.kr/2016apac/)
(The lecturer insists Microsoft changed their attitude to open source, and I deeply agree about it.)

Yes, I admit that it has still long journey to get more fancy. But I provides fine features for free and many plugins already!

You can change your VS-Code theme in the menu (File > Preference > Color Theme). Because I was a user of SublimeText and VIM, I was missing it very much. So, I choose **"Monokai"** theme.

However, you can notify that "Monokai" theme uses gray color for comments. For a person like me, a gray color (especially in the black bg) is really hard to read, and not notifiable. Thus, if you suffer same problem like me, you can change the highlighting color for your precious eyes.

There is a XML file at "\resources\app\extensions\theme-monokai\themes" directory at the VS-Code directory. (In my case, VS-Code is installed at "C:\Program Files (x86)\Microsoft VS Code". I believe that not much different in other OS.)

For "Monokai" theme, the file name would be "Monokai.tmTheme". Befor open it, make sure that open with administrator mode. Once you open it, you can change colors for your own favorite.
Of course, to change "comment" color, you can find a string "comment" using your text editor.
