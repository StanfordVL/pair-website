---
layout: publication
title: "MimicPlay: Long-horizon Imitation Learning by Watching Human Play"
authors: "Chen Wang, Linxi Fan, Jiankai Sun, Ruohan Zhang, Li Fei-Fei, Danfei Xu, Yuke Zhu*, and Anima Anandkumar*"
pub_info_name: "Conference on Robot Learning"
pub_info_date: November 2023
excerpt: Imitation Learning from human demonstrations is a promising paradigm to teach robots manipulation skills in the real world, but learning complex long-horizon tasks often requires an unattainable amount of demonstrations. To reduce the high data requirement, we resort to human play data — video sequences of people freely interacting with the environment using their hands. We hypothesize that even with different morphologies, human play data contain rich and salient information about physical interactions that can readily facilitate robot policy learning. Motivated by this, we introduce a hierarchical learning framework named MimicPlay that learns latent plans from human play data to guide low-level visuomotor control trained on a small number of teleoperated demonstrations. With systematic evaluations of 14 long-horizon manipulation tasks in the real world, we show that MimicPlay dramatically outperforms state-of-the-art imitation learning methods in task success rate, generalization ability, and robustness to disturbances.
images:
  thumb: wang-corl23-mimicplay.png
  main: wang-corl23-mimicplay.png
paper_link: "https://arxiv.org/pdf/2302.12422"
webpage_link: "https://mimic-play.github.io/"
video_link: "https://www.youtube.com/watch?v=p8QsuOy6f_c"
code_link: "https://github.com/j96w/MimicPlay"
---