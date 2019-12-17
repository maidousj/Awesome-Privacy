# Awesome-Privacy  

This is a repository for resources on all kinds of things on privacy. Currently its' maintained by [Yanqi Gu](https://guyanqi.github.io).   
The papers are sorted by time and seperated by category. Any suggestions and pull requests are welcome.  
The sharing is only for research purpose. If any authors don't want their paper to be listed here, please feel free to contact me(you can find my email address on my homepage).  
In my opinion, there're currently several things that researchers in this area need to pay attention to:   
Mathematical Frameworks(Theoretical research in differential privacy is very hot, including private learning algorithms and fair learning)   
Privacy in practice(Since we already have these privacy algorithms, it's important to think about how to implement them efficiently and securely)   
Domains Usage(Currently privacy is important and need to be studied in CPS systems, mobile systems and tracking systems)    

## Framework

### General DP theory  
* pMSE Mechanism: Differentially Private Synthetic Data with Maximal Distributional Similarity [[paper]](https://arxiv.org/pdf/1805.09392.pdf) by Joshua Snoke and Aleksandra Slavkovic. 2018
* Differentially Private Continual Learning [[paper]](https://arxiv.org/pdf/1902.06497.pdf) by S.Farquhar and Yarin Gal. 2018
* Individual Fairness Under Composition [[paper]](http://www.fatml.org/media/documents/individual_fairness_under_composition.pdf) by Cynthia Dwork and Christina Ilvento. 2018  
* Differentially Private Fair Learning [[paper]](https://arxiv.org/abs/1812.02696) by Matthew Jagielski, Michael Kearns, Jieming Mao, Alina Oprea, Aaron Roth, Saeed Sharifi-Malvajerdi, Jonathan Ullman. 2018  
* Differentially Private False Discovery Rate Control [[paper]](https://arxiv.org/abs/1807.04209) by Cynthia Dwork, Weijie J. Su, Li Zhang. 2018  
* Accuracy First: Selecting a Differential Privacy Level for Accuracy-Constrained ERM [[paper]](https://arxiv.org/abs/1705.10829) [[code]](https://github.com/steven7woo/Accuracy-First-Differential-Privacy) by Katrina Ligett, Seth Neel, Aaron Roth, Bo Waggoner, Z. Steven Wu. 2017  
* Penalizing Unfairness in Binary Classification [[paper]](https://arxiv.org/abs/1707.00044) by Yahav Bechavod, Katrina Ligett. 2017  
* Concentrated Differential Privacy [[paper]](https://arxiv.org/abs/1603.01887) by Cynthia Dwork, Guy N. Rothblum. 2016  
* Protecting Privacy when Disclosing Information: k-Anonymity and Its Enforcement through Generalization and Suppression [[paper]](https://epic.org/privacy/reidentification/Samarati_Sweeney_paper.pdf) by Pierangela Samarati and Latanya Sweeney  

### Local Differential Privacy  
* Local Differential Privacy for Evolving Data [[paper]](https://arxiv.org/abs/1802.07128) by Matthew Joseph, Aaron Roth, Jonathan Ullman, Bo Waggoner. 2018  
* Privacy at Scale: Local Differential Privacy in Practice [[paper]](http://dimacs.rutgers.edu/~graham/pubs/papers/ldptutorial.pdf) by Graham Cormode, Somesh Jha, Tejas kulkarni, Ninghui Li, Divesh Srivastava, Tianhao Wang. 2018  
* Locally Private Gaussian Estimation [[paper]](https://arxiv.org/abs/1811.08382) by Matthew Joseph, Janardhan Kulkarni, Jieming Mao, Zhiwei Steven Wu. 2018  

### Image Privacy
* Learning to Anonymize Faces for Privacy Preserving Action Detection [[paper]](https://web.cs.ucdavis.edu/~yjlee/projects/eccv2018-privacy.pdf) by Zhongzheng Ren, Yong Jae Lee and Michael S.Ryoo. 2019
* Image Privacy Prediction Using Deep Neural Networks [[paper]](https://arxiv.org/pdf/1903.03695.pdf) by Ashwini Tonge, Cornelia Caragea. 2019

### Adversarial Training
* TBA

### Privacy and Generative Model
* DP-CGAN : Differentially Private Synthetic Data and Label Generation [[paper]](http://openaccess.thecvf.com/content_CVPRW_2019/papers/CV-COPS/Torkzadehmahani_DP-CGAN_Differentially_Private_Synthetic_Data_and_Label_Generation_CVPRW_2019_paper.pdf) by Peter Kairouz etc. 2019
* Siamese Generative Adversarial Privatizer for Biometric Data [[paper]](https://arxiv.org/pdf/1804.08757.pdf) [[code]](https://github.com/WUT-ML/privacy) by WUT and peter kairouz. 2018
* Generative Adversarial Models for Learning Private and Fair Representations(GAPF) [[paper]](https://arxiv.org/abs/1807.05306) [[code]](https://github.com/cabreraalex/private-fair-GAN) by Chong Huang, Peter Kairouz, Lalitha Sankar. 2018
* Context-Aware Generative Adversarial Privacy(GAP) [[paper]](https://arxiv.org/abs/1710.09549) by Chong Huang, Peter Kairouz, Xiao Chen, Lalitha Sankar, Ram Rajagopal. 2017  
* Differentially Private Generative Adversarial Networks for Time Series, Continuous, and Discrete Open Data
 [[paper]](https://arxiv.org/abs/1901.02477) by Lorenzo Frigerio, Anderson Santana de Oliveira, Laurent Gomez, Patrick Duverger. 2018   
* Generative Adversarial Nets [[paper]](https://arxiv.org/abs/1406.2661) by Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio. 2014  

### Privacy in Federated Learning  
* Beyond Inferring Class Representatives: User-Level Privacy Leakage From Federated Learning [[paper]](https://arxiv.org/pdf/1812.00535.pdf) by Zhibo Wang, etc. 2019
* Exploiting Unintended Feature Leakage in Collaborative Learning [[paper]](https://arxiv.org/pdf/1805.04049.pdf) [[code]](https://github.com/csong27/property-inference-collaborative-ml) by Vitaly's group. 2019
* How To Backdoor Federated Learning [[paper]](https://arxiv.org/abs/1807.00459) [[code]](https://github.com/ebagdasa/backdoor_federated_learning) by Vitaly's group. 2018
* Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning [[paper]](https://arxiv.org/abs/1702.07464) by Briland Hitaj, Giuseppe Ateniese, Fernando Perez-Cruz. 2017  

### Private ML  
* Learning with differential privacy: stability, learnability and the sufficiency and necessity of ERM principle [[paper]](https://dl.acm.org/citation.cfm?id=3053465) by Yu-Xiang Wang, Jing Lei, Stephen E.Fienberg. 2016  
* Privacy-Preserving Deep Learning [[paper]](https://www.cs.cornell.edu/~shmat/shmat_ccs15.pdf) by Reza Shokri and Vitaly Shmatikov.2015  
* Differential Privacy and Machine Learning: a Survey and Review [[paper]](https://arxiv.org/abs/1412.7584) by Zhanglong Ji, Zachary C. Lipton, Charles Elkan. 2014  

### Privacy in MAB  
* Differentially Private Contextual Linear Bandits [[paper]](https://arxiv.org/pdf/1810.00068.pdf) by Roshan Shariff and Or Sheffet. 2018  
* Achieving Privacy in the Adversarial Multi-Armed Bandit [[paper]](https://arxiv.org/abs/1701.04222) by Aristide C. Y. Tossou, Christos Dimitrakakis. 2017  
* Differentially Private Policy Evaluation [[paper]](https://arxiv.org/abs/1603.02010) by Borja Balle, Maziar Gomrokchi, Doina Precup. 2016  
* Algorithms for Differentially Private Multi-Armed Bandits [[paper]](https://arxiv.org/abs/1511.08681) by Aristide Tossou, Christos Dimitrakakis. 2015  
* MAB problems [[paper]](http://web.eecs.umich.edu/faculty/teneketzis/papers/MAB-Survey.pdf) by Aditya Mahajan and D.teneketzis  
* (Nearly) Optimal Differentially Private Stochastic Multi-Arm Bandits [[paper]](http://auai.org/uai2015/proceedings/papers/58.pdf) by Nikita Mishra and Abhradeep Thakurta  
* Taming the Monster: A Fast and Simple Algorithm for Contextual Bandits [[paper]](http://proceedings.mlr.press/v32/agarwalb14.pdf) by A.A, D.H, S.K, J.L, L.L, R.E.S  

### Privacy-preserving Encrypted Neural Network
* SHE: A Fast and Accurate Deep Neural Network for Encrypted Data [[paper]](https://arxiv.org/abs/1906.00148) [[code]](https://github.com/safednn/SHE) by Qian Lou, Lei Jiang. 2019
* 2P-DNN : Privacy-Preserving Deep Neural Networks Based on Homomorphic Cryptosystem [[paper]](https://arxiv.org/abs/1807.08459) [[code]](https://github.com/zhustrong/pigstrong/tree/master/pigstrong) by Qiang Zhu, Xixiang Lv. 2018


## Differential Privacy Tutorial
* For dummies [[link]](https://robertovitillo.com/2016/07/29/differential-privacy-for-dummies/)
* Emory University CS 573 Data Privacy and Security, Fall 2018 [[course website]](http://www.cs.emory.edu/~lxiong/cs573/)
* KDD 2018 Privacy tutorial [[link]](https://sites.google.com/view/kdd2018privacytutorial)
* KDD 2018 Privacy at scale: Local Differential Privacy in Practice [[link]](https://sites.google.com/view/kdd2018-tutorial/home)
* NIPS 2017 Privacy tutorial: Differentially Private Machine Learning: Theory, Algorithms, and Applications [[link]](https://www.ece.rutgers.edu/~asarwate/nips2017/)
* University at Buffalo, SUNY. CSE 660 Fall 2017 DP by Marco Gaboardi [[link]](https://www.acsu.buffalo.edu/~gaboardi/teaching/CSE660-fall17.html) 

## Influential Authors 

* Kamalika Chaudhuri [[link]](http://cseweb.ucsd.edu/~kamalika/), UCSD. Mainly focus on ML. Initiate research on **private ERM** with her student Shuang Song [[link]](http://cseweb.ucsd.edu/~shs037/). 
* Ashwin Machanavajjhala [[link]](https://users.cs.duke.edu/~ashwin/index.html), Duke University. Some teaching maybe helpful.
* Tianhao Wang [[link]](https://tianhao.wang), Purdue University. DP and LDP.
* Yuxiang Wang [[link]](https://sites.cs.ucsb.edu/~yuxiangw/index.html), UCSB. Make differential privacy practical and develop a statistical foundation for off-policy reinforcement learning.
* Di Wang [[link]](http://www.acsu.buffalo.edu/~dwang45/), State University of New York at Buffalo. DPML. 
* Bargav Jayaraman [[link]](https://bargavjayaraman.github.io), University of Virginia. PPML.
* Jun Zhao [[link]](https://junzhao-cmu.wixsite.com/resume), Nanyang Technological University. PPML.
* BorjaBalle [[Homepage]](https://borjaballe.github.io), [[Github]](https://github.com/BorjaBalle), DeepMind. ML related Theorem, Algorithm and Application. PPML.

## Codes
* Diffprivlib: The IBM Differential Privacy Library [[code]](https://github.com/IBM/differential-privacy-library)

## Blogs
* cleverhans-blog: a blog by Ian Goodfellow and Nicolas Papernot about security and privacy in machine learning. [[link]](https://www.cleverhans.io)
* Frank McSherry. [[link]](https://github.com/frankmcsherry/blog)
