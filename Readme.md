
Waver

1) Basic Concept

Waver is a pedagogical tool.
Students wave to vote on which topics to explore, in front of a camera.
The goal is to get students to be more physically active and in control of their learning.
Waver was created for research, so more details will be given in an academic paper (if you use this code for research, please cite it, thank you!).

2) Content (languages, libraries, and files used) 

waver.py
waver_win.exe (Compiled with pyinstaller on Windows 7 64 bit)
waver_linux.exe (Compiled with pyinstaller on Ubuntu 14.04 64 bit)
Readme.md

2) Setup:
You need a computer running Windows or Linux with a webcamera connected to it.

3) How to use:

-This assumes you are in a classroom with students.
Make sure the students are in the field of view of the camera you are using.
-Start the program. 
You can either double click the executable for Windows or Linux.
Or if you have python/opencv installed you can call
"python waver.py"
-Tell the students "Wave your hands now if you want to try ____" 
(Fill in whatever activity you would like them to consider: it could be taking a quiz, or watching a video, etc)
Press "i" to reset the program, which will begin to pick up the student's movements.
After a few seconds, press "1" to get a number representing how much movement occurred for the "yes" condition.
-Tell the students "Wave your hands now if you don't want to try ____"
Press "i" to reset the program, which will begin to pick up the student's movements.
After a few seconds, press "2" to get a number representing how much movement occurred for the "no" condition.
-Press "o" to get the decision output. 
-Do you want to use the program again? Just press "n" to clear away all the text, then follow the instructions above again as many times as you wish.
-To quit, press "q".

4) Licenses

For this author's code and dataset, the MIT license applies:

Copyright 2018 Martin Cooney 

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated dataset and documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



