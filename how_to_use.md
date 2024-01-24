```python
source ~/myenv/bin/activate

# train
python train.py --img 640 --batch 16 --epochs 3 --data Water-Level-Measurement-1/data.yaml --weights yolov5s.pt

# detect
python detect.py --source Water-Level-Measurement-1/valid/images --weights runs/train/exp/weights/best.pt
```
