---
layout: publication
title: "DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation"
authors: "Chen Wang, Haochen Shi, Weizhuo Wang, Ruohan Zhang, Li Fei-Fei, and C. Karen Liu"
pub_info_name: "Robotics: Science and Systems"
pub_info_date: June 2024
excerpt: Imitation learning from human hand motion data presents a promising avenue for imbuing robots with human-like dexterity in real-world manipulation tasks. Despite this potential, substantial challenges persist, particularly with the portability of existing hand motion capture (mocap) systems and the complexity of translating mocap data into effective robotic policies. To tackle these issues, we introduce DexCap, a portable hand motion capture system, alongside DexIL, a novel imitation algorithm for training dexterous robot skills directly from human hand mocap data. DexCap offers precise, occlusion-resistant tracking of wrist and finger motions based on SLAM and electromagnetic field together with 3D observations of the environment. Utilizing this rich dataset, DexIL employs inverse kinematics and point cloud-based imitation learning to seamlessly replicate human actions with robot hands. Beyond direct learning from human motion, DexCap also offers an optional human-in-the-loop correction mechanism during policy rollouts to refine and further improve task performance. Through extensive evaluation across six challenging dexterous manipulation tasks, our approach not only demonstrates superior performance but also showcases the system's capability to effectively learn from in-the-wild mocap data, paving the way for future data collection methods in the pursuit of human-level robot dexterity.
images:
  thumb: wang-rss24-dexcap.png
  main: wang-rss24-dexcap.png
paper_link: "https://arxiv.org/abs/2403.07788"
webpage_link: "https://dex-cap.github.io/"
video_link: "https://www.youtube.com/watch?v=-PmjRjgXKuo"
code_link: "https://github.com/j96w/DexCap"
---