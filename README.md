# Plot edge PR curves
This repository contains the code to plot edge PR curves of many existing edge detectors on [BSDS500](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/resources.html) and [NYUD](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html).

<img src="https://mmcheng.net/wp-content/uploads/2014/04/edge_eval_bsds.png" width="400"><img src="http://mmcheng.net/wp-content/uploads/2014/04/edge_eval_nyud.png" width="400">

If you are using the code/data provided here in a publication, please consider citing our paper:

    @inproceedings{liu2017richer,
      title={Richer Convolutional Features for Edge Detection},
      author={Liu, Yun and Cheng, Ming-Ming and Hu, Xiaowei and Wang, Kai and Bai, Xiang},
      journal={Proceedings of the IEEE conference on computer vision and pattern recognition (CVPR)},
      pages={5872--5881},
      year={2017},
      organization={IEEE}
    }
    
### Note

The first column of thresholds in *_bdry.txt and *_bdry_thr.txt has been removed.

### Citations

[1] RCF

    @inproceedings{liu2017richer,
      title={Richer Convolutional Features for Edge Detection},
      author={Liu, Yun and Cheng, Ming-Ming and Hu, Xiaowei and Wang, Kai and Bai, Xiang},
      journal={Proceedings of the IEEE conference on computer vision and pattern recognition (CVPR)},
      pages={5872--5881},
      year={2017},
      organization={IEEE}
    }
    
[2] COB

    @inproceedings{maninis2016convolutional,
      title={Convolutional oriented boundaries},
      author={Maninis, Kevis-Kokitsi and Pont-Tuset, Jordi and Arbel{\'a}ez, Pablo and Van Gool, Luc},
      booktitle={European Conference on Computer Vision},
      pages={580--596},
      year={2016},
      organization={Springer}
    }
    
[3] HED

    @inproceedings{xie2015holistically,
      title={Holistically-nested edge detection},
      author={Xie, Saining and Tu, Zhuowen},
      booktitle={Proceedings of the IEEE international conference on computer vision},
      pages={1395--1403},
      year={2015}
    }
    
[4] HFL

    @inproceedings{bertasius2015high,
      title={High-for-low and low-for-high: Efficient boundary detection from deep object features and its applications to high-level vision},
      author={Bertasius, Gedas and Shi, Jianbo and Torresani, Lorenzo},
      booktitle={Proceedings of the IEEE International Conference on Computer Vision},
      pages={504--512},
      year={2015}
    }
    
[5] DeepContour

    @inproceedings{shen2015deepcontour,
      title={Deepcontour: A deep convolutional feature learned by positive-sharing loss for contour detection},
      author={Shen, Wei and Wang, Xinggang and Wang, Yan and Bai, Xiang and Zhang, Zhijiang},
      booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
      pages={3982--3991},
      year={2015}
    }
    
[6] DeepEdge

    @inproceedings{bertasius2015deepedge,
      title={Deepedge: A multi-scale bifurcated deep network for top-down contour detection},
      author={Bertasius, Gedas and Shi, Jianbo and Torresani, Lorenzo},
      booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
      pages={4380--4389},
      year={2015}
    }
    
[7] OEF

    @inproceedings{hallman2015oriented,
      title={Oriented edge forests for boundary detection},
      author={Hallman, Sam and Fowlkes, Charless C},
      booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
      pages={1732--1740},
      year={2015}
    }
    
[8] MCG

    @inproceedings{arbelaez2014multiscale,
      title={Multiscale combinatorial grouping},
      author={Arbel{\'a}ez, Pablo and Pont-Tuset, Jordi and Barron, Jonathan T and Marques, Ferran and Malik, Jitendra},
      booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
      pages={328--335},
      year={2014}
    }
    
[9] SE

    @inproceedings{dollar2013structured,
      title={Structured forests for fast edge detection},
      author={Doll{\'a}r, Piotr and Zitnick, C Lawrence},
      booktitle={Proceedings of the IEEE International Conference on Computer Vision},
      pages={1841--1848},
      year={2013}
    }
    
[10] gPb-UCM

    @article{arbelaez2011contour,
      title={Contour detection and hierarchical image segmentation},
      author={Arbelaez, Pablo and Maire, Michael and Fowlkes, Charless and Malik, Jitendra},
      journal={IEEE transactions on pattern analysis and machine intelligence},
      volume={33},
      number={5},
      pages={898--916},
      year={2011},
      publisher={IEEE}
    }
    
[11] ISCRA

    @inproceedings{ren2013image,
      title={Image segmentation by cascaded region agglomeration},
      author={Ren, Zhile and Shakhnarovich, Gregory},
      booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
      pages={2011--2018},
      year={2013}
    }
    
[12] Pb

    @article{martin2004learning,
      title={Learning to detect natural image boundaries using local brightness, color, and texture cues},
      author={Martin, David R and Fowlkes, Charless C and Malik, Jitendra},
      journal={IEEE transactions on pattern analysis and machine intelligence},
      volume={26},
      number={5},
      pages={530--549},
      year={2004},
      publisher={IEEE}
    }
    
[13] BEL

    @inproceedings{dollar2006supervised,
      title={Supervised learning of edges and object boundaries},
      author={Dollar, Piotr and Tu, Zhuowen and Belongie, Serge},
      booktitle={Computer Vision and Pattern Recognition, 2006 IEEE Computer Society Conference on},
      volume={2},
      pages={1964--1971},
      year={2006},
      organization={IEEE}
    }
    
[14] NCut

    @article{shi2000normalized,
      title={Normalized cuts and image segmentation},
      author={Shi, Jianbo and Malik, Jitendra},
      journal={IEEE Transactions on pattern analysis and machine intelligence},
      volume={22},
      number={8},
      pages={888--905},
      year={2000},
      publisher={Ieee}
    }
    
[15] EGB

    @article{felzenszwalb2004efficient,
      title={Efficient graph-based image segmentation},
      author={Felzenszwalb, Pedro F and Huttenlocher, Daniel P},
      journal={International journal of computer vision},
      volume={59},
      number={2},
      pages={167--181},
      year={2004},
      publisher={Springer}
    }
    
[16] Canny

    @article{canny1986computational,
      title={A computational approach to edge detection},
      author={Canny, John},
      journal={IEEE Transactions on pattern analysis and machine intelligence},
      number={6},
      pages={679--698},
      year={1986},
      publisher={Ieee}
    }
    
[17] MShift

    @article{comaniciu2002mean,
      title={Mean shift: A robust approach toward feature space analysis},
      author={Comaniciu, Dorin and Meer, Peter},
      journal={IEEE Transactions on pattern analysis and machine intelligence},
      volume={24},
      number={5},
      pages={603--619},
      year={2002},
      publisher={IEEE}
    }
    
[18] Sobel

    @techreport{sobel1970camera,
      title={Camera models and machine perception},
      author={Sobel, Irwin},
      year={1970},
      institution={Stanford Univ Calif Dept of Computer Science}
    }
    
[19] SE+NG+

    @inproceedings{gupta2014learning,
      title={Learning rich features from RGB-D images for object detection and segmentation},
      author={Gupta, Saurabh and Girshick, Ross and Arbel{\'a}ez, Pablo and Malik, Jitendra},
      booktitle={European Conference on Computer Vision},
      pages={345--360},
      year={2014},
      organization={Springer}
    }
    
[20] gPb+NG

    @inproceedings{gupta2013perceptual,
      title={Perceptual organization and recognition of indoor scenes from RGB-D images},
      author={Gupta, Saurabh and Arbelaez, Pablo and Malik, Jitendra},
      booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
      pages={564--571},
      year={2013}
    }
