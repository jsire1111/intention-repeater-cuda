## --> TO ANYONE READING THIS ON MY PERSONAL GITHUB <--

### BEGIN jsire1111

I have forked both the original *Intention Repeater* and *Intention Repeater*, CUDA version from [tsweet77](https://github.com/tsweet77):

[twseet77/intention-repeater](https://github.com/tsweet77/intention-repeater)

[tsweet77/repeater-max-cuda](https://github.com/tsweet77/repeater-max-cuda)

I have done this so that I may freely restructure the repo and history in a way that makes sense to me.

Eventually, I will start refactoring, as I would like to try utilizing this on a cloud-hosted GPU Jupyter Notebook.

Everything currently outside this one block of text is from the original author. Please visit the original repos or the [Intention Repeater](https://www.intentionrepeater.com/) website for more information.

Thank you and namaste.

### END jsire1111

# repeater-max-cuda
The CUDA version of the Repeater MAX. Repeats intentions up to 1.5+ Billion times per second.

Requires Visual Studio 2019 Community for C++: https://visualstudio.microsoft.com/downloads/

and CUDA Toolkit: https://developer.nvidia.com/cuda-toolkit

To compile: nvcc intention_repeater_max_cuda.cu -O 3 -o "intention_repeater_max_cuda.exe"

Discussion: https://forums.intentionrepeater.com/t/new-repeater-max-cuda-most-powerful-version/540?u=anthroteacher

Special thanks to Karteek Sheri for providing the CUDA functionality.
