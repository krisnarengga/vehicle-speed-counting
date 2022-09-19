# vehicle-speed-counting
This project is demonstrating simple vehicle speed measurement estimation on toll road or highway

This app is based on YOLOV7 object detection library engine from WongKinYiu repository on https://github.com/WongKinYiu/yolov7 

DeepSort object tracking implementation
https://github.com/RizwanMunawar/yolov7-object-tracking/

And based on PySource.com tutorial
https://www.youtube.com/watch?v=j10j8IuKSBI&t=0s

Run this command to run the app
python detect_speed.py --weights yolov7-tiny.pt --source traffic.mp4 --view-img --nosave --no-trace

Notes:
You can download yolov7-tiny or yolov7 weights from YOLOV7 assets repository https://github.com/WongKinYiu/yolov7/releases

App Demo:
https://www.youtube.com/watch?v=dFxkekwXPCQ

Sample Video:
https://drive.google.com/file/d/119FPTQ3FyK6J_16WZUzQUCD9R0PD9In-/view?usp=sharing
