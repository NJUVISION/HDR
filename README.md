# Robust High Dynamic Range (HDR) Imaging with Complex Motion and Parallax

<sup>1</sup>[Vision Lab](https://vision.nju.edu.cn/), Nanjing University

<sup>2</sup>University of California, Riverside, Riverside, CA, USA

Zhiyuan Pu<sup>1</sup>, Peiyao Guo<sup>1</sup>, [Salman Asif](https://intra.ece.ucr.edu/~sasif/index.html)<sup>2</sup>, and [Zhan Ma](https://vision.nju.edu.cn/fc/d3/c29470a457939/page.htm)<sup>1</sup>

<img src="./images/008Plot.png" width = "1000" alt="" align=center />

## Abstract
High dynamic range (HDR) imaging is widely used in consumer photography, computer game rendering, autonomous driving, and surveillance systems. Reconstructing ghosting-free HDR images of dynamic scenes from a set of multi-exposure images is a challenging task, especially with large object motion, disparity, and occlusions, leading to visible artifacts using existing methods. In this paper, we propose a Pyramidal Alignment and Masked merging network (PAMnet) that learns to synthesize HDR images from input low dynamic range (LDR) images in an end-to-end manner. Instead of aligning under/overexposed images to the reference view directly in pixel-domain, we apply deformable convolutions across multiscale features for pyramidal alignment. Aligned features offer more flexibility to refine the inevitable misalignment for subsequent merging network without reconstructing the aligned image explicitly. To make full use of aligned features, we use dilated dense residual blocks with squeeze-and-excitation (SE) attention. Such attention mechanism effectively helps to remove redundant information and suppress misaligned features. Additional mask-based weighting is further employed to refine the HDR reconstruction, which offers better image quality and sharp local details. Experiments demonstrate that PAMnet can produce ghosting-free HDR results in the presence of large disparity and motion. We present extensive comparative studies using several popular datasets to demonstrate superior quality compared to the state-of-the-art algorithms.

## Downloads
<img src="./images/PDF.png" height = "25" alt="" /> 
[Paper, PDF]()(will be updated soon)

<img src="./images/youtube_icon_darkCrop.png" height = "25" alt="" /> 
[video](http://yun.nju.edu.cn/f/a0f381de8b/?raw=1)

<img src="./images/PDF.png" height = "25" alt="" /> 
[more results]()

## Acknowledgments
We are grateful for the constructive comments from anonymous reviewers. The corresponding author is Dr. Zhan Ma (mazhan@nju.edu.cn).
