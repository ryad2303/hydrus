# Hydrus-1D for CMake

This is [Hydrus-1D](http://www.pc-progress.com/en/Default.aspx?hydrus-1d) adapted for CMake and GFortran. See the [Hydrus-1D technical manual](http://www.pc-progress.com/Downloads/Pgm_hydrus1D/HYDRUS1D-4.08.pdf) for more information.

It was tested on Linux with gcc 4.8.1 and CMake 2.8.12.

## Instructions

```bash
git clone https://github.com/bilke/hydrus.git
mkdir build
cd build
cmake ../hydrus
make
./h1d_calc
```