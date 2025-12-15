1.cd fire_Yolov5_v1
2.git clone https://github.com/ultralytics/yolov5.git 
cd yolov5
pip install -r requirements.txt

3.python train.py --img 640 --batch 16 --epochs 10 --data ../fire.yaml --weights yolov5s.pt --workers 0
4.python detect.py --source http://192.168.0.224:8080/video --weights runs/train/exp/weights/best.pt --conf 0.4(for Mobile webcam)

fire Dataset download link- https://mega.nz/file/MgVhQSoS#kOcuJFezOwU_9F46GZ1KJnX1STNny-tlD5oaJ9Hv0gY
