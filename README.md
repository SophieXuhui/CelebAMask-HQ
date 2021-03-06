# CelebAMask-HQ
![image](https://github.com/switchablenorms/CelebAMask-HQ/blob/master/images/front.jpeg)
**CelebAMask-HQ** is a large-scale face image dataset that has **30,000** high-resolution face images selected from the CelebA dataset by following CelebA-HQ. Each image has segmentation mask of facial attributes corresponding to CelebA.

The masks of CelebAMask-HQ were manually-annotated with the size of **512 x 512** and **19 classes** including all facial components and accessories such as skin, nose, eyes, eyebrows, ears, mouth, lip, hair, hat, eyeglass, earring, necklace, neck, and cloth. 

CelebAMask-HQ can be used to **train and evaluate algorithms of face parsing, face recognition, and GANs for face generation and editing**.

* If you need the identity labels and the attribute labels of the images, please send request to the [CelebA team](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html).

* Demo of interactive facial image manipulation
![image](https://github.com/switchablenorms/CelebAMask-HQ/blob/master/images/demo.gif)

## Sample Images
![image](https://github.com/switchablenorms/CelebAMask-HQ/blob/master/images/sample.png)

## Research Projects with CelebAMask-HQ
CelebAMask-HQ can be used on several research fields including: facial image manipulation, face parsing, face recognition, and face hallucination. We construct an application on interactive facial image manipulation as bellow:

* Samples of interactive facial image manipulation
![image](https://github.com/switchablenorms/CelebAMask-HQ/blob/master/images/sample_interactive.png)

## Downloads
* Google Drive: [downloading link](https://drive.google.com/open?id=1badu11NqxGf6qM3PTTooQDJvQbejgbTv)
* Baidu Drive: [downloading link](https://pan.baidu.com/s/1wN1E-B1bJ7mE1mrn9loj5g)

## Related work
* **CelebA** dataset :<br/>
Ziwei Liu, Ping Luo, Xiaogang Wang and Xiaoou Tang, "Deep Learning Face Attributes in the Wild", in IEEE International Conference on Computer Vision (ICCV), 2015 
* **CelebA-HQ** was collected from CelebA and further post-processed by the following paper :<br/>
Karras et. al, "Progressive Growing of GANs for Improved Quality, Stability, and Variation", in Internation Conference on Reoresentation Learning (ICLR), 2018

## License and Citation
The use of this software is RESTRICTED to **non-commercial research and educational purposes**.
```
@article{CelebAMask-HQ,
  title={MaskGAN: Towards Diverse and Interactive Facial Image Manipulation},
  author={Cheng-Han Lee and Ziwei Liu and Lingyun Wu and Ping Luo},
  journal={Technical Report},
  year={2019}
}
```
The above work is still in submission.
