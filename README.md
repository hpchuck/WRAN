PyTorch training code for Wide Residual Networks

# Requirements

Install requirements:

```
pip install -r requirements.txt
```


# Howto

Train WRN-28-10 on 4 GPUs:

```
python main.py --save ./logs/resnet_$RANDOM$RANDOM --depth 28 --width 10 --ngpu 1 --gpu_id 0
```
