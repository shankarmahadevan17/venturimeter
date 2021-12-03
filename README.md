# venturimeter
The venturimeter works on the principle of Bernoulli's equation, i.e., the pressure decreases as the velocity increases. The cross-section of the throat is less than the cross-section of the inlet pipe.The animation is done in python manim



https://user-images.githubusercontent.com/89344915/144592356-cb11bd2f-0a5d-4c9e-a5d6-1bb12d0552de.mp4

Manim runs on Python 3.6 or higher (Python 3.8 is recommended).

System requirements are [FFmpeg](https://ffmpeg.org/), [OpenGL](https://www.opengl.org/) and [LaTeX](https://www.latex-project.org) (optional, if you want to use LaTeX).
For Linux, [Pango](https://pango.gnome.org) along with its development headers are required. See instruction [here](https://github.com/ManimCommunity/ManimPango#building).


### Directly

```sh
# Install manimgl
pip install manimgl

# Try it out
manimgl
```

For more options, take a look at the [Using manim](#using-manim) sections further below.

If you want to hack on manimlib itself, clone this repository and in that directory execute:

```sh
# Install manimgl
pip install -e .

# Try it out
manimgl example_scenes.py OpeningManimExample
# or
manim-render example_scenes.py OpeningManimExample
```

### Directly (Windows)

1. [Install FFmpeg](https://www.wikihow.com/Install-FFmpeg-on-Windows).
2. Install a LaTeX distribution. [MiKTeX](https://miktex.org/download) is recommended.
3. Install the remaining Python packages.
    ```sh
    git clone https://github.com/3b1b/manim.git
    cd manim
    pip install -e .
    manimgl example_scenes.py OpeningManimExample
    ```
