Detecção de rostos com OpenCV e Python
Para rodar o script é necessário instalar o Python e o OpenCV.

1. Para executar a detecção de faces em imagens use:
python face_detect.py --image faces.jpg --prototxt deploy.prototxt --model res10_300x300_ssd_iter_140000.caf

2. Para executar a detecção de faces em vídeos use:
python detect_faces_video.py --video rostos.mp4 --prototxt deploy.prototxt --model res10_300x300_ssd_iter_140000.caffemodel

Testes realizados no Sistema operacional Linux Debian 9.
