---
title: "A Learnable Safety Measure"
collection: publications
permalink: /publication/2019-01-01-A-Learnable-Safety-Measure
date: 2019-01-01
venue: 'In the proceedings of Proceedings of The 3rd Conference on Robot Learning (CoRL)'
authors: ' Steve Heim,  Alexander Rohr,  Sebastian Trimpe,  Alexander Badri-Spröwitz'
citation: ' Steve Heim,  Alexander Rohr,  Sebastian Trimpe,  Alexander Badri-Spröwitz, &quot;A Learnable Safety Measure.&quot; In the proceedings of Proceedings of The 3rd Conference on Robot Learning, 2019.'
---

**Abstract:** Failures are challenging for learning to control physical systems since they risk damage, time-consuming resets, and often provide little gradient infor- mation. Adding safety constraints to exploration typically requires a lot of prior knowledge and domain expertise. We present a safety measure which implicitly captures how the system dynamics relate to a set of failure states. Not only can this measure be used as a safety function, but also to directly compute the set of safe state-action pairs. Further, we show a model-free approach to learn this measure by active sampling using Gaussian processes. While safety can only be guaranteed after learning the safety measure, we show that failures can already be greatly reduced by using the estimated measure during learning.  

[arXiv](https://arxiv.org/pdf/1910.02835.pdf)  

bibtex:  
```
@inproceedings{heim2019learnable,  
  title={A Learnable Safety Measure},  
  author={Heim, Steve and von Rohr, Alexander and Trimpe, Sebastian and Badri-Spr{\"o}witz, Alexander},  
  booktitle =    {Proceedings of The 3rd Conference on Robot Learning},  
  year =   {2019},  
  series =   {Proceedings of Machine Learning Research},  
  publisher =    {PMLR}
}
```