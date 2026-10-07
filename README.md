## To Download / Install yourself
**FFMPEG.exe** : https://ffmpeg.org/download.html  
**XbTool.exe** : https://github.com/AlexCSDev/XbTool  
**XbxDETool.exe** : https://github.com/Nenkai/XbxDeTool  

## Already present
**opus.dll** :  
	https://packages.msys2.org/packages/mingw-w64-x86_64-opus  
  Scroll down to "Files" and click on the mirror link starting with "https://mirror.msys2.org/mingw/..."

**nopus.exe** :  
	1. Install MSYS2 and lauch it https://www.msys2.org/  
	2. Enter the following command : `pacman -S mingw-w64-ucrt-x86_64-gcc make mingw-w64-ucrt-x86_64-opus`  
	3. Confirm with Y whenever prompted  
	4. Install Git with the following command : `pacman -S git`  
	5. Then run : `git clone https://github.com/conhlee/nopus.git`  
	6. `cd nopus`  
	7. `make LDFLAGS="-l:libopus.a -lm -static"`  
	8. The result will be generated in :`C:\msys64\home\%Username%\nopus`  