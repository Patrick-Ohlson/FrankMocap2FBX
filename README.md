# FrankMocap2FBX
A brain dump for my FrankMocap explorations

I stumbled upon https://github.com/facebookresearch/frankmocap, these are my links and notes, use and abuse

This is my tweet thread during the exploration: https://twitter.com/pp3dp_se/status/1458434786838687746

FrankMocap is an awesome 3d motion extractor, sadly a bit hard to get FBX from it

For all eager to jump in, here's a great Google colab:  https://colab.research.google.com/drive/15LTkHCC79VdyBAsmrJmuLBlyUa1jLo_P?usp=sharing

Otherwise, use anaconda and setup FrankMocap by following the instructions in https://github.com/facebookresearch/frankmocap/blob/main/docs/INSTALL.md

(Windows users, see https://github.com/carlosedubarreto/frankmocap_win_install)

Install Blender ( https://anaconda.org/kitsune.one/python-blender )

Use my [fbx_output_FRANKMOCAP.py] modified for conda blender 2.7x , https://github.com/facebookresearch/frankmocap/files/5750266/fbx_output_FRANKMOCAP.zip (For newer Blender)
Needs SMPL models from: https://download.is.tue.mpg.de/download.php?domain=smpl&sfile=SMPL_unity_v.1.0.0.zip

This is also a good Blender plugin, although bone structure did not suit me https://github.com/carlosedubarreto/b3d_mocap_import

This one needs adjustments, but very good for removing the Blender requirement
https://github.com/mrhaiyiwang/Smplx2FBX

# SMPL links
https://smplify.is.tue.mpg.de/index.html
https://smpl-x.is.tue.mpg.de/index.html
