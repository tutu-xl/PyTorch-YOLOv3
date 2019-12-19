 1. Check Hardware (Nividia card) if yes -> install CUDA 10.x https://developer.nvidia.com/cuda-downloads
 2. Check python version (3.5.x or 3.6.x)
 3. Install PyTorch 1.x (https://pytorch.org/get-started/locally/)
 4. Clone and install requirements
    $ git clone https://github.com/eriklindernoren/PyTorch-YOLOv3
    $ cd PyTorch-YOLOv3/
    $ 
    $ sudo pip3 install -r requirements.txt
 5. Download pretrained weights
    $ cd weights/
    $ bash download_weights.sh
    $ cd ..
 6. Download COCO  
    $ cd data/
    $ bash get_coco_dataset.sh


