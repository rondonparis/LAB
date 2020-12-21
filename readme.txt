1. mrcnn setup하기
- 'setup.py'가 있는 곳으로 경로 이동하기.
python setup.py install
http://www.robots.ox.ac.uk/~vgg/software/via/via-1.0.6.html
데이터셋 만들기
https://youtu.be/Z1-zQEgOoXI
pip install tensorflow==1.15.0
pip install tensorflow-gpu==1.15.0
pip install keras==2.2.5
pip install scikit-image
pip install opencv-python
pip install imgaug
pip install pycocotools
pip install -U scikit-image==0.16.2
pip install -U h5py==2.10.0

python bottle.py train --dataset=dataset --weights=coco
