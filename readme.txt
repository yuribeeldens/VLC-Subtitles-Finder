Usage:
 - Open a movie in VLC
 - (optional) Stop the movie
 - Open the the VLC menu: "View->Subtitles Finder" (this activates the plugin)
 - Open the the plugin menu: "View->Subtitles Finder->Download"

Notes:
  - Because of internal changes in VLC, the minimum version of VLC required is 1.1.0
  - VLC support only uncompressed .rar files
  - VLC 1.1.x do not support lua scripts that uses GUIs under MAC-OSx, so:
    this plugin WILL NOT work on your MAC!

Know issues:
  - The search fail if you click the button two times consecutively

Recent fixes:
  - Now works on Linux-VLC. The fix should not break Windows VLC, but is untested. [by Abraham van Helpsing]
  
Thanks to:
  - Mederi (Various fixes and corrections)
  - Ciprus (Testing)
  - Abraham van Helpsing (Linux fixes)