About
============
AVAudioEngine is a new tool that Apple gave developers in 2014 to make building mixers and buffers much easier. It works amazingly, but the documentation is not exactly helpful. After playing around with it for a few days I managed to build a working player. Since I am already using AVAudioPlayer in Cloud Play, I wanted it to build an AVAudioEngine player to work in place of AVAudioPlayer. The reason is because for devices &lt;. iOS 8, I want to continue to use AVAudioPlayer and for devices >= iOS 8, I want to use the new AVAudioEngine.


AEAudioPlayer
=============

**IMPORTANT NOTE**: This is not tuned for production. It is meant for instructional purposes.

AEAudioPlayer is an AVAudioEngine music player to mimic AVAudioPlayer. Simply add AEAudioplayer.h and AEAudioPlayer.m to your project and use it the same way that you use any AVAudioPlayer. 

To set frequencies, simply initialize AEAudioPlayer with and array of NSNumbers with the frequencies that you would like to use. Then call the setGain: method to set the gain for that frequency. 
