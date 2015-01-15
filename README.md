# Fooling Code

This is the code base used to reproduce the "fooling" images in the paper:

[Anh Nguyen](http://anhnguyen.me), [Jason Yosinski](http://yosinski.com/), and [Jeff Clune](http://jeffclune.com). "Deep Neural Networks are Easily Fooled: High Confidence Predictions for Unrecognizable Images." arXiv preprint arXiv:1412.1897 (2014).

**If you use this software in an academic article, please cite:**

@article{nguyen2014deep,
  title={Deep Neural Networks are Easily Fooled: High Confidence Predictions for Unrecognizable Images},
  author={Nguyen, Anh and Yosinski, Jason and Clune, Jeff},
  journal={arXiv preprint arXiv:1412.1897},
  year={2014}
}

For more information regarding the paper, please visit www.evolvingai.org/fooling

## Requirements
This is an installation process that requires two main software packages (included in this package):

1. Caffe: http://caffe.berkeleyvision.org
  * Our libraries installed to work with Caffe
    * Cuda 6.0
    * Boost 1.52
2. Sferes: https://github.com/jbmouret/sferes2
  * Our libraries installed to work with Sferes
    * OpenCV 2.4.10
    * Boost 1.52
    * g++ 4.9 (a C++ compiler compatible with C++11 standard)

Note: These are specific versions of the two frameworks with our additional work necessary to produce the images as in the paper. They are not the same as their master branches.

## Installation

Please see the Installation_Guide.pdf for more details.

## Usage

* An MNIST experiment (Fig. 4, 5 in the paper) can be run directly on a local machine (4-core) within a reasonable amount of time (around ~5 minutes or less for 200 generations).
* An ImageNet experiment needs to be run on a cluster environment. It took us ~4 days x 128 cores to run 5000 generations and produce 1000 images (Fig. 8 in the paper).

## License

Please refer to the licenses of Sferes and Caffe projects.
