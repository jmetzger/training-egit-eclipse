## Increase Icon-Size (works on oxygen and newer)  

  * You might want to have bigger icon size (tested on Windows) 
  * Search for "eclipse.ini" 
  * Open in editor (e.g. Notepad++)
  * Add the following 3 lines (at the end of the file):

```
-Dswt.enable.autoScale=true
-Dswt.autoScale=200
-Dswt.autoScale.method=nearest
```
