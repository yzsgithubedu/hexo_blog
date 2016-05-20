---
title: Getting Started (Week 0)
date: 2016-05-19 19:47:45
category: Weekly_Report
tags: week_0

---

# Porject Introduction 
## topic
3D Scene Reconstruction and Rendering from Multiple Images
## brief description
3D scene reconstruction is usually a task where multiple images of a scene is taken and a 3D surface of that scene is reconstructed. A system of 3D scene reconstruction should estimates camera pose and 3D scene geometry i.e. depth information. Building such a system mainly requires knowledge of computer graphics and image processing. We three are really looking forward to have a try on such a challenge. **Over the next few weeks, we will update our progress in the project on this website. **
## course requirements
3D reconstruction from multiple images is the creation of three-dimensional models from a set of images. It is the reverse process of obtaining 2D images from 3D scenes.
The essence of an image is a projection from a 3D scene onto a 2D plane, during which process the depth is lost. The 3D point corresponding to a specific image point is constrained to be on the line of sight. From a single image, it is impossible to determine which point on this line corresponds to the image point. If two images are available, then the position of a 3D point can be found as the intersection of the two projection rays. This process is referred to as triangulation. The key for thsi process is the relations between multiple views which convey the information that corresponding sets of points must contain some structure and that this structure is related to the poses and the calibration of the camera.

BONUS (Reslizing each of the following tasks you can gain up to 10% mor scores of your project score, i.e. your final project score = basic project score * 110%)
1. Rendoring 3D scene on mobile devices(+10%)
2. Result evaluation on public datasets(+10%): Multi-View Stereo Dataset: http://vision.middlebury.edu/mview/

## video demo (from the web):

<embed src="http://player.youku.com/player.php/sid/XOTQ4OTk2NDM2/v.swf" allowFullScreen="true" quality="high" width="480" height="400" align="middle" allowScriptAccess="always" type="application/x-shockwave-flash"></embed>

# Group Members
* 杨子枢：2463454532@qq.com
* 龚逸凌：476174713@qq.com
* 王敬靖：413226895@qq.com


# Current Plan for Next Week
1. Read papers and learn basics about 3D scene reconstruction; dicussions will be held.
2. Learn Android programming
3. Confirm duties and responsibilities, i.e. division of labor

# References
[1] Multi-camera scene reconstruction via graph cuts, ECCV 2002
[2] 3D Reconstruction and Rendering from Image Sequences
[3] Scene Reconstruction and Visualization from Internet Photo Collections, 2008
