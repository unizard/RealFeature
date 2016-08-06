
## [AI-Robotics Summer School Materials](http://www.kros.org/summerschool2016/02web01.php)
- [Material] [LocalFeatures](http://multispectral.kaist.ac.kr/ykchoi/RSS2016/RSS2016-Features.pdf) : From handcraft to deep learning
- [Supp #1] [Binary Features](http://multispectral.kaist.ac.kr/ykchoi/RSS2016/RSS2016-BinaryFeatures.pdf) : BRIEF, ORB, BRISK, FREAK, BIO
- [Supp #2] [Deep Features](http://multispectral.kaist.ac.kr/ykchoi/RSS2016/RSS2016-DeepFeatures.pdf) : DeepCompare, MatchNet, DeepDesc, PN-Net


## [Feature's History](http://multispectral.kaist.ac.kr/ykchoi/RSS2016/History.png)


### Corner
- [Harris][OpenCV] [Harris Corner Detector](http://faculty.cse.tamu.edu/jchai/csce641/harris_detector.pdf), 2004  [[ppt](http://www.cse.psu.edu/~rtc12/CSE486/lecture06.pdf)] York 
- [[FAST](http://www6.in.tum.de/Main/ResearchAgast)][OpenCV][C++] [FAST corner detection](https://arxiv.org/pdf/0810.2434.pdf), PAMI 2010 [[ppt](http://web.eecs.umich.edu/~silvio/teaching/EECS598_2010/slides/11_16_Hao.pdf)] Cambridge

### Conventional Feature
- [[SIFT](http://docs.opencv.org/3.1.0/da/df5/tutorial_py_sift_intro.html#gsc.tab=0)][OpenCV][Vlfeat] [Object recognition from local scale-invariant features, ICCV 1999](http://www.cs.ubc.ca/~lowe/papers/iccv99.pdf), Lowe 
- [[SURF](http://docs.opencv.org/3.1.0/df/dd2/tutorial_py_surf_intro.html#gsc.tab=0)][OpenCV] [Speeded up robust features, ECCV 2006](http://www.vision.ee.ethz.ch/en/publications/papers/articles/eth_biwi_00517.pdf), ETH
- [[DAISY](http://cvlab.epfl.ch/software/daisy)] [DAISY: An Efficient Dense Descriptor Applied to Wide Baseline Stereo, PAMI 2010](https://infoscience.epfl.ch/record/138785/files/tola_daisy_pami_1.pdf), EPFL

### Binary Feature
- [[BRIEF] (http://docs.opencv.org/3.1.0/dc/d7d/tutorial_py_brief.html#gsc.tab=0)][OpenCV] [BRIEF: Binary Robust Independent Elementary Features, PAMI2012](https://infoscience.epfl.ch/record/167678/files/top.pdf), [ECCV2010](https://www.robots.ox.ac.uk/~vgg/rg/papers/CalonderLSF10.pdf), EPFL
- [[ORB] (http://docs.opencv.org/3.1.0/d1/d89/tutorial_py_orb.html#gsc.tab=0)][OpenCV] [ORB: An efficient alternative to SIFT or SURF, ICCV 2011](http://www.willowgarage.com/sites/default/files/orb_final.pdf), Willowgarage
- [[BRISK](http://docs.opencv.org/2.4/modules/features2d/doc/feature_detection_and_description.html#brisk)][OpenCV] [BRISK: Binary Robust Invariant Scalable Keypoints, ICCV 2011](https://www.robots.ox.ac.uk/~vgg/rg/papers/brisk.pdf), Oxford 
- [[FREAK](http://docs.opencv.org/2.4/modules/features2d/doc/feature_detection_and_description.html)][OpenCV] [FREAK: Fast Retina Keypoint, CVPR 2012](https://infoscience.epfl.ch/record/175537/files/2069.pdf), EPFL
- [[AKAZE](https://github.com/pablofdezalc/akaze)][OpenCV] [Fast Explicit Diffusion for Accelerated Features in Nonlinear Scale Spaces, BMVC 2013](http://www.robesafe.com/personal/pablo.alcantarilla/papers/Alcantarilla13bmvc.pdf), GIT
- [[BIO](https://sites.google.com/site/ykchoicv/feature_bio)][Matlab-mex] [Robust Binary Feature using Intensity Order, ACCV2014](https://www.dropbox.com/s/3glkyn0w0xxysij/ACCV2014_Robust%20Binary%20Feature%20Using%20Intensity%20Order.pdf?dl=0), KAIST

### Intensity based
- [[LIOP](http://zhwang.me/publication/liop/index.html)][Matlab][Vlfeat] [Local Intensity Order Pattern for Feature Description, ICCV 2011](http://vision.ia.ac.cn/Students/bfan/LIOP-ICCV2011.pdf), CASIA
- [[MROGH](http://www.openpr.org.cn/index.php/86-MROGH/View-details.html)][Matlab] [Aggregating Gradient Distributions into Intensity Orders, CVPR 2011](http://vision.ia.ac.cn/Students/bfan/BinFan_MROGH_CVPR11.pdf), CASIA

### Learning based
- [[D-BREIF] (http://cvlab.epfl.ch/research/detect/dbrief)][Matlab] [Efficient Discriminative Projections for Compact Binary Descriptors, ECCV2012](http://cvlabwww.epfl.ch/~lepetit/papers/trzcinski_eccv12.pdf), EPFL
- [[BinBOOST] (http://cvlab.epfl.ch/research/detect/binboost)] [[BinBoost: Boosting Binary Keypoint Descriptors](https://infoscience.epfl.ch/record/183635/files/top.pdf?version=1)], EPFL
- [[VGG](http://www.robots.ox.ac.uk/~vgg/research/learn_desc/)] [Learning Local Feature Descriptors Using Convex Optimisation, PAMI 2014](http://www.robots.ox.ac.uk/~vgg/publications/2014/Simonyan14/simonyan13a.pdf), Oxford

### Neural Network based
- [[DeepCompare](http://imagine.enpc.fr/~zagoruys/deepcompare.html)][Torch] [Learning to Compare Image Patches via Convolutional Neural Networks, CVPR 2015] (http://arxiv.org/pdf/1504.03641.pdf)
- [[MatchNet](https://github.com/hanxf/matchnet)][Pycaffe] [MatchNet: Unifying Feature and Metric Learning for Patch-Based Matching, CVPR2015](http://www.cs.unc.edu/~xufeng/cs/papers/cvpr15-matchnet.pdf), Google
- [[DeepDesc](http://cvlab.epfl.ch/research/detect/deepdescriptorlearning)][Torch] [Discriminative Learning of Deep Convolutional Feature Point Descriptors, ICCV 2015](https://infoscience.epfl.ch/record/213228/files/iccv-2015-deepdesc.pdf), [supp](http://hi.cs.waseda.ac.jp/~esimo/publications/supplemental/SimoSerraICCV2015_supp.pdf), [poster](http://hi.cs.waseda.ac.jp/~esimo/publications/posters/SimoSerraICCV2015_poster.pdf), EPFL 
- [[PN-Net](https://github.com/vbalnt/pnnet)][Torch] [PN-Net: Conjoined Triple Deep Network for Learning Local Image Descriptors, Arxiv 2016](http://arxiv.org/pdf/1601.05030v1.pdf), Imperial
- [GLoss] [Learning Local Image Descriptors with Deep Siamese and Triplet Convolutional Networks by Minimising Global Loss Functions, CVPR 2016](http://arxiv.org/pdf/1512.09272v1.pdf), ACRV
- [[LIFT](https://github.com/cvlab-epfl/LIFT)][Torch] [*LIFT: Learned Invariant Feature Transform, ECCV2016](http://arxiv.org/pdf/1603.09114v1.pdf), EPFL

### Evalation
- [[Detector](http://www.robots.ox.ac.uk/~vgg/research/affine/evaluation.html#eval_soft)][Matlab] [A comparison of affine region detectors, IJCV 2005](http://www.robots.ox.ac.uk/~vgg/research/affine/det_eval_files/vibes_ijcv2004.pdf), Oxford, 
- [[Descriptor](http://www.robots.ox.ac.uk/~vgg/research/affine/desc_evaluation.html#code)][Matlab] [A performance evaluation of local descriptors, PAMI 2005](http://www.robots.ox.ac.uk/~vgg/research/affine/det_eval_files/mikolajczyk_pami2004.pdf), Oxford
- [[Binary](http://cs.unc.edu/~jheinly/binary_descriptors.html)] [Comparative Evaluation of Binary Features, ECCV 2012](https://www.cs.unc.edu/~jheinly/publications/eccv2012-heinly.pdf), UNC
- [[Orientation](https://github.com/cvlab-epfl/benchmark-orientation)] [Learning to Assign Orientations to Feature Points, CVPR2016](https://infoscience.epfl.ch/record/217982/files/top.pdf), EPFL
- [Matching] [Evaluation of Local Detectors and Descriptors for Fast Feature Matching, ICPR] (http://www.miksik.co.uk/papers/miksik2012icpr.pdf), Krystian Mikolajczyk

### Evaluation Report
- [A battle of three descriptors, 2012] (http://computer-vision-talks.com/2012-08-18-a-battle-of-three-descriptors-surf-freak-and-brisk/)
- [Comparison of the OpenCV’s feature detection algorithms, 2011] (http://computer-vision-talks.com/2011-01-04-comparison-of-the-opencv-feature-detection-algorithms/)
- [Comparison of the OpenCV’s feature detection algorithms – II, 2011] (http://computer-vision-talks.com/2011-07-13-comparison-of-the-opencv-feature-detection-algorithms/)
- [Comparison of feature descriptors, 2011] (http://computer-vision-talks.com/2011-01-28-comparison-of-feature-descriptors/)


### Book
- [Local Image Descriptor: Modern Approaches, 2015](http://www.springer.com/gb/book/9783662491713), Bin Fan
- [Local Invariant Feature Detectors: A Survey, 2008](http://www.eng.auburn.edu/~troppel/courses/7970%202015A%20AdvMobRob%20sp15/literature/%5B2008%5D%20Local%20Invariant%20Feature%20Detectors-%20A%20Survey.pdf), Krystian Mikolajczyk



### Tutorial
- [[Tutorial on Binary Descriptors](https://gilscvblog.com/2013/08/26/tutorial-on-binary-descriptors-part-1/)] [BRIEF](https://gilscvblog.com/2013/09/19/a-tutorial-on-binary-descriptors-part-2-the-brief-descriptor/), [ORB](https://gilscvblog.com/2013/10/04/a-tutorial-on-binary-descriptors-part-3-the-orb-descriptor/), [BRISK](https://gilscvblog.com/2013/11/08/a-tutorial-on-binary-descriptors-part-4-the-brisk-descriptor/), [FREAK](https://gilscvblog.com/2013/12/09/a-tutorial-on-binary-descriptors-part-5-the-freak-descriptor/), 2013

