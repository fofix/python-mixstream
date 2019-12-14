# MixStream

MixStream is a C-extension in Python to combine [SoundTouch](https://www.surina.net/soundtouch/) and [SDL_mixer](https://www.libsdl.org/projects/SDL_mixer/).


## Setup

### Dependencies

You'll need those packages:

* `glib`
* `libogg`
* `libtheora`
* `libvorbisfile`
* `sdl 1.2`
* `sdl_mixer 1.2`
* `soundtouch`.


### Native modules

Build the extension::

    python setup.py build_ext --inplace --force
