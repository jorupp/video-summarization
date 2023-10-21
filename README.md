# video-summarization

Setup environment

```sh
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

You may also have to do this to get the GPU version of pytorch installed
```sh
pip uninstall torch torchvision torchaudio
pip cache purge
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```
