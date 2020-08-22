# ATLAS for windows
#### Hey, do you ever wonder what if you have an assistant to do some small things on your laptop just by typing some small words or a sentence?
1. Example: can you draw something for me?
   (opens MSPaint)
2. Example: I need to do some editing.
   (opens photoshop)
3. Example: Day 
   (Tells you the day.)
4. Example: can you play some videos for me?
   (opens youtube)
5. Example: let's do some scrolling.
   (opens Instagram)
6. Example: I'm in a party mood.
   (opens window media player )
7. Example: Open my connections.
   (opens linkedin)
8. Example: Do i need to carry my umbrella?
   (opens weather app)
9. Example: ppt/slides
   (opens powerpoint)
10. Example: where am i?
    (open maps)
11. Example: wpc/WPC
    (open windows parental control)
12. Example: let's play some cards. 
    (opens Microsoft Solitaire Collection)

#### Here I present you ATLAS.
#### This is a very simple code in python and the work is authentic and not copied from any of the     websites. It requires a lot of work to do to handle every critical statement. For starters, you need to give your name as an input.
#### Then ATLAS can tell/open:
1. Time(24 hour clock)
2. Date 
3. Month 
4. Weekday
5. Gmail(By default)
6. Instagram
7. Whatsapp
8. Youtube
9. Facebook
10. Twitter
11. Linkedin
12. Excel
13. Word
14. PowerPoint
15. Outlook
16. Infopath
17. Onenote
18. MSgroove.
19. Notepad
20. Snipping tool
21. Photoshop
22. MSPaint
23. Calculator
24. Acrobat PDF reader
25. Control panel
26. Windows media player
27. VLC
28. Chrome browser.
29. Settings
30. Calender
31. Weather
32. Webcam
33. Photos
34. Store
35. IBM SPSS
36. Maps
37. Windows parental control
38. Microsoft Solitaire Collection

NOTE : ATLAS includes Microsoft windows preinstalled programs and other applications like photoshop and the applications(offline) which are metioned above must be installed in your machine before hand to work with ATLAS.
** (Compatible with windows for now) **


### HOW TO WORK WITH ATLAS:
#### There are some initial steps you need to know:
1. After starting/executing ATLAS, it will ask for your name.
2. Then atlas will wish you good morning, good afternoon or good evening. (Don't                                                  worry, ATLAS is quite humble and respectful towards everyone.)
3. Then you can hear the voice of ATLAS saying "How can i assist you"?
4. Running applications using ATLAS is quite simple, you just know the name of the application and ATLAS will handle the rest.

# KEYWORDS:
* For calendar : Calendar
* For day name : Day
* For saying bye to ATLAS : see ya, see you, exit, quit, bye, toodles.
* For Windows parental control : WPC/wpc
* For calendar : calc (you can also ask like: can you help me with some calculations?)

#### Importing OS module.
import os


* If os module is not avaiable in your enviroment then please install using :
#### pip install os


#### Importing pyttsx3 module.
from pyttsx3 import speak

* If pyttsx3 module is not avaiable in your enviroment then please install using : pip install pyttsx3

### USE of this module:
1. To convert text to speech and making the code more interactive.
2. We can just simply use SPEAK function from pyttsx3 module. To do that, run the command : from pyttsx3 import speak


#### Importing Datetime module.
from datetime import datetime

* If Datetime module is not avaiable in your enviroment then please install using : pip install datetime

## USE of this module:
1. To deal with date and time.
2. To make it more user friendly, we can just use the datetime function from datetime module. To do that, run this command:        from datetime import datetime

## Today() function: 

#### This function allows to see the present date.

## Accessing elements of datetime like:
1. Minutes
2. Hours
3. Day
4. weekday(Name of the day)
5. Month
6. year

#### To Access the above elements, we can use STRFTIME() function. There are various string formatting to extract the various parts of the datetime.
1. To acceess present day or name of the day. ('%A')
2. To access hour. ('%H')
3. To access minutes. ('%M')
4. To access month name. ('%B')
5. To access the which day of month it is. ('%d')
6. To access year. ('%Y')

### Example: datetime.today().strftime('%A') 
