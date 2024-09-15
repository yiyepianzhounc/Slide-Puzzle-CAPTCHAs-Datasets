# Slide Puzzle CAPTCHAs Datasets

## Introduction
- This is the datasets constructed in our paper "SPC-GAN-Attack: Attacking Slide Puzzle CAPTCHAs by Human-Like Sliding Trajectories Based on Generative Adversarial Network". We select Tencent CAPTCHA, GeeTest CAPTCHA v3, Shumei CAPTCHA, NetEase CAPTCHA, GeeTest CAPTCHA v4, Dingxiang CAPTCHA to test the security of slide puzzle CAPTCHAs. For each type of slide puzzle CAPTCHA, we construct a Notch Detection Dataset (ND-Dataset) and a Two-Dimensional Sliding Trajectory Dataset (2D-ST-Dataset).

## Notch Detection Datasets (ND-Datasets)
- For each type of slide puzzle CAPTCHA, we download 500 background images by a crawler, and manually label the notches in the background images to construct the ND-Dataset.
- We use labelimg to label the notches in the background images, the results are saved in the txt files.

## Two-Dimensional Sliding Trajectory Datasets (2D-ST-Datasets)
- For each type of slide puzzle CAPTCHA, we collect 500 verified  human two-dimensional sliding trajectories to construct the 2D-ST-Dataset.
### The sample of a trajectory:
108_[[1, 0], [26, -4], [21, -4], [7, -2], [4, -1], [8, 0], [18, 0], [11, 0], [4, 0], [3, 0], [1, 0], [1, 0], [2, 0], [1, 0], [0, 0], [0, 0]]_1.2
- "108" represents the sliding distance.
- "[[1, 0], [26, -4], [21, -4], [7, -2], [4, -1], [8, 0], [18, 0], [11, 0], [4, 0], [3, 0], [1, 0], [1, 0], [2, 0], [1, 0], [0, 0], [0, 0]]" represents the sliding trajectory.
- "1.2" represents the human sliding time.
