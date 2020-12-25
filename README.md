# MieTurbo Animations

## Installation for Windows

- [MikTex](https://miktex.org/download)
- `conda create -n manim`
- `conda activate manim`
- `conda install -c conda-forge sox`
- `conda install -c conda-forge ffmpeg`
- `conda install -c conda-forge cairo`
- (optional) `conda install numpy` if there is an error about numpy
- Add `C:\Users\Tommie\miniconda3\Library\bin` to the environment variable PATH
- `pip install manimlib`


## Running

```sh
manim 1.py Shapes -p --high_quality
```