Before you run this code, you need to download the pretrained models. 
Go to slim-pretrained folder and run these scripts: 
```
sh download_extract_v1.sh
```
Above will download inception_v1 model and extract it. You should have inception_v1.ckpt file in slim-pretrained folder after this.

```
sh download_extract_v3.sh
```

Above will download inception_v3 model and extract it. You should have inception_v3.ckpt file in slim-pretrained folder after this.


You can now run prediction on any image url like this: 

```
python run_inference_on_v1.py https://pbs.twimg.com/media/B5B9ZsvIgAATiC6.jpg
```
```
python run_inference_on_v3.py https://pbs.twimg.com/media/B5B9ZsvIgAATiC6.jpg
```
