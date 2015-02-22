# smplayer_themes
My themes for smplayer

HowTo create theme in SMPlayer v>14.9 (example):

Making a folder: smtheme

The smtheme has:
Files: MyTheme.qrc
Subfolder: MyTheme, with the logo.png file

The MyTheme.qrc:
<RCC>
  <qresource prefix="/">
    <file>MyTheme/logo.png</file>
  </qresource>
</RCC>

Opening a console to the smtheme folder and running command:
rcc --binary -o  MyTheme.rcc MyTheme.qrc

Then put MyTheme.rcc into /usr/share/smplayer/themes/MyTheme/
