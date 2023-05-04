# **Swift-Basic-Xylophone-App**
A simple iOS App will produce different sound if user tap each button from iOS &amp; Swift - The Complete iOS App Development Bootcamp by Dr. Angela Yu.

_*demo video Xylophone App._

![Xylophone](https://user-images.githubusercontent.com/60531747/236204365-7f1c13ac-7775-43f3-86a4-e656249057ae.gif)

## **Developmet Step by Step:**
- Clone the template project from **Github.**
- Linking all buttons to one **IBAction** Method called keyPressed.
- Create **Function** called playSound.
- Inside playSound Function use **AVAudioPlayer** from **AVFoundation** UIkit Library.
- Make constant called url to connect the currentButton using **sender** and extension audio.
- Inside IBAction function use playSound **Method** sender.currentTitle to get the value which button have pressed.
- Give **opacity** value 0.5 using **.alpha** when button get pressed and make the sender opacity back to 1.0 after 0.2 second in delay.

## **What have I Learned:**
- **How to play sound using AVFoundation and AVAudioPlayer.**
- **Understand Apple documentation and how to use StackOverflow.**
- **Functions and methods in Swift.**
- **Error handling in Swift.**
- **Working with Opacity.**
- **Connect and running using sender.**
