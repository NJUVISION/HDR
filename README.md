# Robust High Dynamic Range (HDR) Imaging with Complex Motion and Parallax

[Vision Lab](https://vision.nju.edu.cn/), Nanjing University

Zhiyuan Pu, Peiyao Guo, [Salman Asif](https://intra.ece.ucr.edu/~sasif/index.html), and [Zhan Ma](https://vision.nju.edu.cn/fc/d3/c29470a457939/page.htm)

## Abstract
High dynamic range (HDR) imaging is widely used in consumer photography, computer game rendering, autonomous driving, and surveillance systems. Reconstructing ghosting-free HDR images of dynamic scenes from a set of multi-exposure images is a challenging task, especially with large object motion, disparity, and occlusions, leading to visible artifacts using existing methods. In this paper, we propose a Pyramidal Alignment and Masked merging network (PAMnet) that learns to synthesize HDR images from input low dynamic range (LDR) images in an end-to-end manner. Instead of aligning under/overexposed images to the reference view directly in pixel-domain, we apply deformable convolutions across multiscale features for pyramidal alignment. Aligned features offer more flexibility to refine the inevitable misalignment for subsequent merging network without reconstructing the aligned image explicitly. To make full use of aligned features, we use dilated dense residual blocks with squeeze-and-excitation (SE) attention. Such attention mechanism effectively helps to remove redundant information and suppress misaligned features. Additional mask-based weighting is further employed to refine the HDR reconstruction, which offers better image quality and sharp local details. Experiments demonstrate that PAMnet can produce ghosting-free HDR results in the presence of large disparity and motion. We present extensive comparative studies using several popular datasets to demonstrate superior quality compared to the state-of-the-art algorithms.

## Downloads
* [Paper, PDF]()

## Video
[[video](http://yun.nju.edu.cn/d/e91ba5275e/files/?p=/0886-spotlight.mp4)](./images/youtube_icon_darkCrop.png)

## Acknowledgments
We are grateful for the constructive comments from anonymous reviewers. The corresponding author is Dr. Zhan Ma (mazhan@nju.edu.cn).
