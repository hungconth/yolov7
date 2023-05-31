
## Inference

On video:
``` shell
python detect.py --weights best.pt --conf 0.5 --source yourvideo.mp4
```

On image:
``` shell
python detect.py --weights best.pt --conf 0.5  --source inference/images/horses.jpg
```
On Camera:
``` shell
python detect.py --weights best.pt --conf 0.5  --source 0
```
