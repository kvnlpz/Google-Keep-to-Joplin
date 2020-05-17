# Google-Keep-to-Joplin
This project assists in importing Google Keep Notes into Joplin,


To use this program, create a folder and download the python file into it. 
You need to use Google Takeout to download your Google Keep notes.
As of right now, this program cannot handle Keep notes with images in them, 
so you'd have to backup those notes into google docs (Keep gives you this option)
and then delete the image from the note and continue to Google Takeout to download

Once you download your zip file, extract the files and copy every HTML file into
a any folder you want to. 

Using Python 3
To use the script just type: 

python keeptojoplin.py "folderName\*.html" (include the quotation marks)

Note that you need to install glob (pip install glob3) 

Note that the folder is INSIDE the folder that the python script is in. 


After it is done, a file named data.txt will be in your folder. 
You need to rename this file to any name but with the ".enex" extension.

Finally, open Joplin and import note. Choose the Evernote markup option. 
