# Terminal Download website
Use a script to download website recursively (files within folders), great for downloading renders from render farm via terminal (MAC)
1. open Termninal
2. Type CD and drag the folder you'd like to download ontop of it, Press enter
3. Copy the below web adress into Terminal Replacing the "URL" with actual website URL which should be downloaded. 

Code to paste in terminal:
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows URL
last bit will be costom

Found at
https://superuser.com/questions/55040/save-a-single-web-page-with-background-images-with-wget
