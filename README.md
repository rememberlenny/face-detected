# face-detected
1.将installer文件夹的内容拷贝到树莓派上， 执行setup.sh文件，会在桌面生成一个face-detected应用，执行。
2.打开face-detectd-demo文件夹，kfpkg文件夹下有人类识别模型， 按 http://wiki.seeedstudio.com/Grove_AI_HAT_for_Edge_Computing/ 教程将人脸识别模型刷写到K210上，打开Arduino 更新最新的K210 Pi板定义，打开Face_Detect_Demo.ino， 将程序刷写到K210 Pis上
3.运行树莓派上的face-detected程序，当有人脸出现时计次，Reset复位。

ps:1. 如果setup.sh文件执行不成功，可尝试执行 face-detected.sh

