### General

This directory contains the necessary code to reproduce the gradient
ascent images in the paper: Figures 13, S3, S4, S5, S6, and S7. This
is research code, and so it may contain paths and such that are
particular to our setup that will need to be changed for your own
setup.

If you find any bugs, please submit a PR!

If you have any trouble getting the code to work, please get in touch, and we'll help where we can.


### Notes on running the gradient ascent code

 * The gist of the gradient ascent code (along with a lot of
experimental bookkeeping) is in the
[find_image function in find_fooling_image.py](https://github.com/Evolving-AI-Lab/fooling/blob/master/caffe/ascent/find_fooling_image.py#L68-L274).
 * If you happen to be working in a
cluster environment that uses ```qsub```, you may find the shell scripts
useful; otherwise they probably won't help you much.
 * If you don't have a trained net around, you can download the trained model we used here: http://yosinski.cs.cornell.edu/yos_140311__caffenet_iter_450000
 * A file containing class labels is also used by the script and can be downloaded here: http://s.yosinski.com/synset_words.txt


