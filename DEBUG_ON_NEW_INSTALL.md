Current repo build uses torch 2.7, the compatible CUDA version is 12.8.

1. Install these packages manually before anything: 
`pip install torch==2.7.1 torchvision==0.22.1 torchaudio==2.7.1 --index-url https://download.pytorch.org/whl/cu128`

1a. Otherwise, if `pip install -r requirements.txt` on the repo was already run, uninstall pytorch related packages first, `pip uninstall torch torchvision torchaudio easyOCR` and then run the first command.


