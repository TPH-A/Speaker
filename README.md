# Speaker

## Statement

This software imports pywin32,formed can sound function.

## Source code

```python
import win32com.client
import os
import time
os.system("color 1b")
speaker = win32com.client.Dispatch("SAPI.SpVoice")
print("---------------------RUN---------------------\n")
print("\t\tTips:In operation,enter 'q' to quit")
while True:
    speak_on = input("\nType in what you want to say:")
    speaker.Speak(speak_on)
    print(speak_on)
    if speak_on == 'q':
        time.sleep(0.5)
        print("\nClosing program......\n")
        speaker.Speak("Closing Program.")
        time.sleep(3)
        print("Program is closing!Thank for you use!")
        speaker.Speak("Program is closing!Thank for you use!")
        break

```

### Download

#### [download](https://pan.baidu.com/s/1fj2iuFLXH0PkFnB24fkZhA)

### Python download

#### [Python3.8.2](https://www.python.org/downloads/release/python-382/)

### Blog

#### [blog](https://blog.csdn.net/weixin_46140392/article/details/104893294)

## Running results

Type in what you want to say.

She will report back what you have said.

## Opendlg

Open the dist folder,you will find an exe file,click open it!

# CSDN user name

顶级程序员-黑客

# User ID

weixin_46140392

# QQ 

1279610056

# Wechant

zyxhbdxc070905
