**Spanning Tree-Based Edge Detection for Robust Image Segmentation**

**Authors:** Shriya Negi and Vijay Kumar Bhat

**Acknowledgment:** The author acknowledges the financial support provided by the Department of Science and Technology (DST), Government of India through the INSPIRE Fellowship [IF210606].

**Article Overview:** The edges of an image are the most noticeable features. By analysing the borders of an image, one might unveil its fundamental framework. Edge detection is a widely used technique in computer vision processing systems. Edge detection is the process of determining the boundaries of objects in an image. This technique is employed in the fields of computer vision, image processing, and analysis. The foundation of edge detection is the identification of major fluctuations in pixel intensity within an image. These modifications emphasise the boundaries of an image, enabling the extraction or enhancement of specific features. Given the increasing prevalence of digital media, the utilisation of edge detection algorithms has become necessary for many applications such as image segmentation, tracking, mapping, and pattern recognition. Conventional edge detection techniques such as Sobel and Robert Cross, which rely on the first derivative, are not impeccable. The Canny operator is complex, tedious and computationally costly. The article introduces a novel technique for edge detection based on graph theory. Instead of using the shortest spanning tree to detect similar regions, our approach will use the largest spanning tree to identify an edge or differentiate between foreground and background.

**Abstract:** Edge detection is a fundamental task in image processing and computer vision, crucial for various applications such as object recognition, image segmentation, and feature extraction. This paper presents a novel approach utilizing the Maximum Spanning Tree (MST) algorithm for edge detection. The MST algorithm, a simple yet efficient segmentation strategy, is adapted to extract edges from images by treating pixels as nodes and their intensities as node weights. By constructing the MST on the image graph, we identify the most prominent edges based on intensity variations, leading to precise edge maps. Experimental results demonstrate the effectiveness of the proposed MST-based edge detection method in accurately capturing edges while preserving important image structures. This research contributes to advancing edge detection techniques by leveraging the inherent properties of the MST algorithm for enhanced edge extraction in digital images.

**Scripts:** 

Following is the flow chart diagram of the proposed algorithm.

![](Aspose.Words.2255e77f-939f-4b2a-929e-cf95ed4a0bda.001.png)
