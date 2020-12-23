# MieTurbo Animations

## Installation for Windows

- [MikTex](https://miktex.org/download)
- [SoX](https://sourceforge.net/projects/sox/files/sox/), the latest version might be 14.4.2
- `choco install ffmpeg`
- `conda create -n manim`
- `conda activate manim`
- Download the source code from [Manim](https://github.com/3b1b/manim) and run `pip install -r requirements.txt`
- [Pycairo](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pycairo)
    - If you use Python 3.8, then download `pycairo‑1.??.?‑cp38‑cp38‑win_amd64.whl` and run `pip install pycairo‑1.??.?‑cp38‑cp38‑win_amd64.whl`
- (optional) `conda install numpy` if there is an error about numpy
- Add `C:\Users\Tommie\miniconda3\Library\bin` to the environment variable PATH
- pip install manimlib


## Running

```sh
manim 1.py Shapes -p --high_quality
```