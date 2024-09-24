---
layout: publication
title: "Sequential Dexterity: Chaining Dexterous Policies for Long-Horizon Manipulation"
authors: "Yuanpei Chen*, Chen Wang*, Li Fei-Fei, and C. Karen Liu*"
pub_info_name: "Conference on Robot Learning"
pub_info_date: November 2023
excerpt: Many real-world manipulation tasks consist of a series of subtasks that are significantly different from one another. Such long-horizon, complex tasks highlight the potential of dexterous hands, which possess adaptability and versatility, capable of seamlessly transitioning between different modes of functionality without the need for re-grasping or external tools. However, the challenges arise due to the high-dimensional action space of dexterous hand and complex compositional dynamics of the long-horizon tasks. We present Sequential Dexterity, a general system based on reinforcement learning (RL) that chains multiple dexterous policies for achieving long-horizon task goals. The core of the system is a transition feasibility function that progressively finetunes the sub-policies for enhancing chaining success rate, while also enables autonomous policy-switching for recovery from failures and bypassing redundant stages. Despite being trained only in simulation with a few task objects, our system demonstrates generalization capability to novel object shapes and is able to zero-shot transfer to a real-world robot equipped with a dexterous hand.
images:
  thumb: wang-corl23-seqdex.png
  main: wang-corl23-seqdex.png
paper_link: "https://arxiv.org/pdf/2309.00987"
webpage_link: "https://sequential-dexterity.github.io/"
video_link: "https://www.youtube.com/watch?v=2mmqQYO4KlY"
code_link: "https://github.com/sequential-dexterity/SeqDex"
---