# My Project Plan

***Note:*** This document is written merely as an illustrative example, and does not provide any working guide to an actual project.

### Proposal
---

I am planning to make a computer vision software that detects objects in images.  
In order to build it, I will use OpenCV, deep learning libraries, such as [TensorFlow](https://www.tensorflow.org/?hl=ko) or [PyTorch](https://www.tensorflow.org/?hl=ko), and other open-source software.  
For example, the objects in the following images were detected using [MMDetection](https://github.com/open-mmlab/mmdetection):  
![Detected Objects](https://user-images.githubusercontent.com/12907710/137271636-56ba1cd2-b110-4812-8221-b4c120320aa9.png)

---

### Dependencies
- Python
- opencv-python
- TensorFlow
- openmmlab
- Package manager

**Installation**  
In a bash terminal, run the following commands (*Do NOT actually run these commands on your computer*):

```bash
$ sudo apt update
$ conda create -n cv_detection
$ conda activate cv_detection
$ python --version
$ python example.py
```
