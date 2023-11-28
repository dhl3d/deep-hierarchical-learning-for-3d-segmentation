<img src="https://dhl3d.github.io/images/dhl3d_logo.png" height="70px" align="left">

# Deep Hierarchical Learning for 3D Segmentation

[Chongshou Li](https://scholar.google.com.sg/citations?user=pQsr70EAAAAJ&hl=en)<sup>1</sup>, [Yuheng Liu](https://yuheng.ink/)<sup>1,2</sup>, [Xinke Li](https://shinke-li.github.io/)<sup>3</sup>, [Yuning Zhang](https://github.com/yuningzhang2022)<sup>1</sup>, [Tianrui Li](https://scholar.google.com/citations?hl=en&authuser=1&user=CQ1HneMAAAAJ)<sup>1</sup>, [Junsong Yuan](https://cse.buffalo.edu/~jsyuan/)<sup>4</sup>

<sup>1</sup>Southwest Jiaotong University, <sup>2</sup>University of Leeds, <sup>3</sup>National University of Singapore, <sup>4</sup>University at Buffalo

![Endpoint Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Fhits.dwyl.com%2Fdhl3d%2Fdhl3dgithubio.json&label=visitors&color=blue) [![Static Badge](https://img.shields.io/badge/Project%20Page-blue?logo=Google%20Chrome&logoColor=white)](https://dhl3d.github.io/)

In the realm of computer vision, 3D objects and scenes are inherently hierarchical, offering an opportunity to break down complex visual entities into simpler components and abstract the visual world across multiple levels. However, effectively harnessing this hierarchy remains a critical challenge in the field of 3D segmentation. One of the key issues is ensuring that predictions at different hierarchical levels maintain coherence. In this paper, we define hierarchical learning within a probabilistic framework and introduce an aggregation matrix to quantitatively model the relationships among different levels of the hierarchy. Building upon these foundations, we design coherence loss functions and establish a theoretical relationship between class accuracy and coherence. To facilitate effective learning of the hierarchy, we present a deep hierarchical learning architecture that includes a dedicated hierarchical embedding learning module. Additionally, we propose a method that leverages a pre-trained Large Language Model and clustering techniques to generate a hierarchical structure for fine-grained 3D segmentation. Our extensive experiments demonstrate the effectiveness of the proposed solution in addressing these challenges.

## NEWS

- [2023/11/29] Official repo is created, code will be released soon, access our [Project Page](https://dhl3d.github.io/) for more details.

## NOTES

This repository will be maintained by [Yuheng](https://yuheng.ink). For any issues regarding code, dataset downloads, or the official website, you can contact Yuheng at the following email addresses: sc20yl2@leeds.ac.uk & yuhengliu02@gmail.com.
