---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**This section is still under construction!**
{: .notice}

Education
======

* B.S. both in Physics & Mathematics, [Wuhan University](http://www.whu.edu.cn/), China
* M.S. in Physics, [Peking University](http://www.pku.edu.cn/), China
* Ph.D (with Excellence) in Computer Science, [Heidelberg University](http://www.uni-heidelberg.de/), Germany
  * Supervisor: Prof. Christoph Schnoerr
  * Thesis: Modern Convex Optimization Methods to Image Processing and Computer Vision 
  
  
Work experience
======

* Aug. 2009 - July 2011: Postdoc Research Fellow (affiliated with Prof. Yuri Boykov and Prof. Olga Veksler)
  * [Computer Science Department, Western University, Canada](http://csd.uwo.ca/)
  * Researches: new convex optimization theories and algorithms, with applications to image processing, computer vision and machine learning

* Aug. 2011 - July 2016: Research Scientist
  * [Robarts Research Institute](http://www.robarts.ca/), [Western University, Canada](http://www.uwo.ca/)
  * Researches: large-scale and parallel optimization methods, with applications to medical image analysis (segmentation / registration), machine learning

* April 2013 - July 2016: Adjunct Research Professor
  * [Schulich Medical School](http://www.schulich.uwo.ca/), [Western University, Canada](http://www.uwo.ca/)
  * Researches: high-performance optimization algorithms to medical image segmentation and registration, with applications to many different topics such as prostate zone segmentation in MRIs, cardiac left and right ventr. segmentation in MRIs, brain segmentation in MRIs, infant brain MRI registration and analysis, prostate ultrasound image segmentation, lung segmentation in functional MRIs etc.
  
* Aug. 2016 - now: Professor
  * [School of Mathematics and Statistics](http://math.xidian.edu.cn/), [Xidian University, China](http://www.xidian.edu.cn/)
  * Researches: new theries and methods in optimization and variational analysis, with applications to computer vision and machine learning
  
  
Recent Publications 
======

{% if site.author.googlescholar %}
  The complete list of my articles can be found on <u><a href="https://scholar.google.ca/citations?user=eMPV_ZkAAAAJ"><i class="fa fa-fw fa-google-plus-square" aria-hidden="true"></i>my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

* T. De Silva, Derek Cool, Jing Yuan, C. Romognoli, Aaron Fenster, Aaron Ward, <ins>Improving 2D-
3D Registration Optimization using Learned Prostate Motions</ins>, **IEEE Transactions on Medical
Imaging**, to appear.

* John Baxter, Martin Rajhl, Jing Yuan, Terry Peters, <ins>Directed Acyclic Graph Continuous Max-
Flow Image Image Segmentation for Unconstrained Label Orderings</ins>, **International Journal of
Computer Vision**, 123(3): 415–434 (2017).

* Wu Qiu, Yimin Chen, Sandrine de Ribaupierre, Aaron Fenster, Jing Yuan, <ins>Longitudinal Analysis of Pre-Term Neonatal Cerebral Ventricles from 3D Ultrasound Images Using Spatial-Temporal Deformable Registration</ins>, **IEEE
Transactions on Medical Imaging**, 36(4): 1016-1026 (2017).

* Wu Qiu, Yimin Chen, Jessica Kishimoto, Sandrine de Ribaupierre, Bernard Chiu, Aaron Fenster,
Jing Yuan, <ins>Automatic Segmentation Approach to Extracting Neonatal Cerebral Ventricles from
3D Ultrasound Images</ins>, **Medical Image Analysis**, 35(1): 181-191 (2016).

* Martin Rajchl, John Baxter, Jing Yuan, Terry Peters, <ins>Hierarchical Max-Flow Segmentation Framework
For Multi-Atlas Segmentation with Kohonen Self-Organizing Map Based Gaussian Mixture
Modeling</ins>, **Medical Image Analysis**, 27: 45-56 (2016).

* Eranga Ukwatta, Jing Yuan∗, Martin Rajchl, Wu Qiu, Bernard Chiu, Aaron Fenster, <ins>Joint Segmentation
of Lumen and Outer Wall from 3D Femoral Artery MR Images: Towards 3D Imaging
Measurements of Peripheral Arterial Disease</ins>, **Medical Image Analysis**, 26(1): 120-132 (2015).

* E. Ukwatta, H. Arevalo, K. Li, J. Yuan, P. Malamas, W. Qiu, K. C. Wu, N. A. Trayanova, F.
Vadakkumpadan, <ins>Myocardial Infarct Segmentation from Magnetic Resonance Images for Personalized
Modeling of Cardiac Electrophysiology</ins>, **IEEE Transactions on Medical Imaging**, 35(6):
1408 - 1419 (2016).

* Qiu Wu, Jing Yuan, Martin Rajchl, Jessica Kishimoto, Sandrine de Ribaupierre, Aaron Fenster,
<ins>3D MR Ventricle Segmentation in Pre-Term Infants with Post-Hemorrhagic Ventricle Dilatation
(PHVD) Using Multi-Phase Geodesic Level-Sets</ins>, **NeuroImage**, 118: 13-25 (2015).

* Yue Sun, Wu Qiu, Jing Yuan, Cesare Romagnoli, Aaron Fenster, <ins>Three-Dimensional Non-Rigid
Landmark-Based Magnetic Resonance to Transrectal Ultrasound Registration for Image-Guided
Prostate Biopsy</ins>, **Journal of Medical Imaging**, 2(2): 025002-025002 (2015).

* Fumin Guo, Jing Yuan, Sarah Svenningsen, Dante Capaldi, Aaron Fenster, Grace Parraga, <ins>Globally
Optimal Co-Segmentation of Three-dimensional Pulmonary 1H and Hyperpolarized 3He MRI
with Spatial Consistence Prior</ins>, **Medical Image Analysis**, 23(1): 43-55 (2015).

* Yue Sun, Jing Yuan, Wu Qiu, Martin Rajchl, Cesare Romagnoli, Aaron Fenster, <ins>Three-Dimensional
Non-Rigid MR-TRUS Registration Using Dual Optimization</ins>, **IEEE Transactions on Medical
Imaging**, 34(5): 1085-1095 (2015).

* Wu Qiu, Jing Yuan, Jessica Kishimoto, Jonathan McLeod, Yimin Chen, Sandrine de Ribaupierre,
Aaron Fenster, <ins>User-Guided Segmentation of Preterm Neonate Ventricular System from 3D Ultrasound
Images Using Convex Optimization</ins>, **Ultrasound in Medicine and Biology**, 41(2): 542-556 (2015).

* Wu Qiu, Jing Yuan, Eranga Ukwatta, Aaron Fenster, <ins>Rotationally Resliced 3D Prostate TRUS
Segmentation Using Convex Optimization with Shape Priors</ins>, **Medical Physics**, 42(2): 877-891
(2015).

* with Caroline Petitjean etc., <ins>Right Ventricle Segmentation from Cardiac MRI: a Collation Study</ins>,
**Medical Image Analysis**, 19(1): 187-202 (2015).

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
