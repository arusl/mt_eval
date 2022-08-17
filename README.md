# mt_eval
Experiments related to MT evaluation

## Check PyTorch with CUDA
In your terminal, type `python`, then: \
```
import torch
x = torch.rand(5,3)
print(x) # if installed, will print a random tensor

# check if CUDA is installed, how many device, and the device name
print(torch.cuda.is_available())
print(torch.cuda.device_count())
print(torch.cuda.get_device_name(0)) # e.g. GeForce RTX 3070
```

To install huggingface-related package, you need to make sure [PyTorch is installed](https://pytorch.org/get-started/locally/), then check here https://huggingface.co/docs/transformers/installation.

## Python Virtual Env
- Creating: `python -m venv .env`
- Activating
    - Windows: `. .env/Scripts/activate`
    - Linux/MacOS: `source .env/bin/activate`
- Deactivating: `deactivate` or `conda deactivate` or `source deactivate`
- Installing all required packages: `pip install -r requirements.txt`