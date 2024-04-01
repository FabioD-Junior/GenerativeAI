# Generative AI - Human Faces Generation
This repository contains notebooks with academic projects to practice and explore image creation using AI, where the use of VAE (Variational Autoencoders) and GANs (Generative Adversarial Networks) was explored to generate human faces based on a dataset with examples.

This is an extraction from the project carried out in the postgraduate course in AI and Data Science, term 3, week 10, at Loyalist College Campus Toronto.

**Disclaimer**

> This project was solely created for educational purposes. I drew inspiration from the original work done by myself and my colleagues in class to create an enhanced version of my own.
> This code is made for academic purposes. Despite all the care and attention to best practices by the author, this work is considered incomplete due to time constraints and computational resources. Therefore, it may contain inaccuracies, code errors, as well as not explore the full potential of the techniques involved.
> The data used in this work were provided by the college, thus I am not distributing them along with this code, as I am not aware of the original source, nor do I have the powers or license to distribute them.
> Within the jupyter notebook file, you will find a references section listing the names of the authors of the original work submitted for the course.

#### 2023F-T3 AISC2007 - Deep Learning

---

#### CASE STUDY Week 10 - Term 4: Use AI generative techniques to create at least 5 images of human faces that do not actually exist.

> Teacher : **Bhavik Gandhi**
---

#### Description
- The professor provided us with a dataset of images of human beings in a variety of positions and scenarios, moods, with one or more faces, complete or partially obscured.
- It was defined that the evaluation score would depend on the success of implementing various techniques, with the highest grade awarded to those who implemented all successfully, including: VAE (Variational Autoencoder), GANs (Generative Adversarial Networks), WGANs (Wasserstein Generative Adversarial Networks), and DCGANs (Deep Convolutional Generative Adversarial Networks).


#### Author
> Fabio Duarte Junior <br> fabioduartejunior@loyalistcollege.com / fabiojr@skiff.com


#### Objective
> Objective: Explore generative AI techniques to generate human faces


#### Notebooks

> All implementations use PyTorch leveraging the APPLE Silicon GPU, known as Metal Performance Shaders or MPS, which is somewhat akin to NVIDIA's CUDA.

| Notebook    | Implementation |  
|------------ | ------------------- | 
| VAE.ipynb   | Variational Autoencoder | 
| GAN.ipynb   | Generative Adversarial Networks | 
| WGAN.ipynb  | Wasserstein Generative Adversarial Networks      |  
| DCGAN.ipynb | Deep Convolutional Generative Adversarial Networks |   

#### Conclusion
>> Generating images using AI, specifically human faces, is quite a challenging task, especially with time and resource constraints (since it's an academic project with less than a week for completion).
>> I wasn't able to generate an image that was 100% like a human face, but I did come very close with some approaches, particularly in the implementation of CNNs.
>> It clearly was able to capture the features of a human face, including color variation and, to the point I managed to run it, it was beginning to reproduce textures and lighting with more precise variance.
>> The professor praised the work, offered some tips for improvement, and acknowledged that achieving a result like what my team managed with the original work from which these notebooks are derived is very difficult.
>> I didn't have time to apply improvements to these notebooks, but I already have some ideas on how to improve them thanks to the professor's help.
 
<br>
<h6><small>Part of  work is based on the original study case project created by Group E for the term 3 A.I. students of Loyalist College  (2023), in which I had the honor to participate.<br>
It is intended solely for educational purposes.
Please refer to the reference section.<br>
We do not have information about the source of the images, they are provided by the professor in moodle without credits, for that reason I am not making it available, just the code.</small></h6>
