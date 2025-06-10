HI!
This is the code repository for a project in the course "Statistical Learning" in Spring 2025.

This project explores whether robotic manipulation behaviors can be grouped
and classified based solely on control signals and sensor observations. Using data
recorded from a bimanual robot interacting with a kitchen environment, we perform
episode-level feature engineering, dimensionality reduction using PCA, and earlystage
exploratory analysis to guide classification efforts.

We investigate whether it is possible to classify robotic manipulation behaviors from lowlevel
sensorimotor data. Each episode is labeled as one of three behaviors—pick, place
on bench, or place in cabinet. The challenge is to create a representation of each episode
that is informative enough for reliable behavior classification.

We use the PhysicalAI-Robotics-Manipulation-Objects dataset, released by NVIDIA and
available on Hugging Face1. It consists of thousands of manipulation episodes performed
by a simulated Kinova Gen3 bimanual robot in a virtual kitchen environment.

**To check the code you need to downlaod the data from the next link:**

https://drive.google.com/drive/folders/1LGkG5QTCbALlGeL7Za6Qk89XxeKhTRlg?usp=drive_link
