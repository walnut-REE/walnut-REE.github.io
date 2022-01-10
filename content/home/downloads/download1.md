+++
title = "Semantic Focal Stack Analysis"
image = "images/works/lfss.png"
video = ""
file = ""
weigth = 1
+++

**Stereo matching** typically involves assigning each pixel a discrete disparity label from a finite set. We present a novel approach that uses **scene semantic labeling** for finding an appropriate disparity label set that accelerates matching and improves accuracy.

Using a light field as input, our **semantic focal stack analysis (SFSA)** first locates salient objects and then estimate their approximate disparities. **Disparity redistribution** is then conducted to more densely sample disparity labels at the detected salient objects. The disparity map is generated at the object level and then fused via Markov Random Field optimization.

``Dec. 2018 - April 2019``