# Yolo object detection

python flow --imgdir test/training/images --model cfg/yolo.cfg --load bin/yolo.weights
python setup.py build_ext --inplace
python flow --model cfg/yolo.cfg --load bin/yolo.weights --demo person.mp4 --saveVideo
