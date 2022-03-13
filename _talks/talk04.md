---
title: "Leveraging Synthetic Data to Learn Video Stabilization Under Adverse Conditions"
collection: talks
type: "Talk"
permalink: /talks/talk04
venue: "Lancaster University, Data Science Group"
date: 2021-12-03
location: "Lancaster, UK"
excerpt: 'Technical Talk'
---
The widespread availability of cameras and the growing popularity of video-sharing websites have led to the rapid growth of unedited and hard-to-watch videos. Video stabilization plays a central role to improve videos quality. Despite the substantial progress made by these methods, they were, mainly, tested under standard weather and lighting conditions, and may perform poorly under adverse conditions. In our work, we propose a new algorithm for video stabilization, which is more robust than the state-of-the-art methods across different weather conditions and outperforms previous approaches in foggy videos.
We present a novel rendering engine to generate the required training data with an automatic ground-truth extraction procedure. Our video stabilization model generalizes well on real-world videos and does not require large-scale synthetic training data to converge. Additionally, since no video stabilization datasets under adverse conditions are available, we propose the novel VSAC77Real dataset for evaluation. We compare our method to five state-of-the-art video stabilization algorithms.
Our results show that current approaches perform poorly in at least one weather condition, and we achieve the best performance in terms of stability average score, distortion score, success rate, and average cropping ratio when considering all weather conditions.


