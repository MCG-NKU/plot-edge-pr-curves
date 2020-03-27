# Plot edge PR curves
This repository contains the code to plot edge PR curves of many existing edge detectors on [BSDS500](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/resources.html) and [NYUD](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html).

<img src="https://raw.githubusercontent.com/yun-liu/plot-edge-pr-curves/master/pr_bsds.png" width="400"><img src="https://raw.githubusercontent.com/yun-liu/plot-edge-pr-curves/master/pr_nyud.png" width="400">

![#f03c15](https://placehold.it/15/f03c15/000000?text=+) ### Note: The first column of thresholds in *_bdry.txt and *_bdry_thr.txt has been removed.

If you are using the code/data provided here in a publication, please consider citing our papers which have been included in this benchmark:

    @article{liu2019richer,
      title={Richer convolutional features for edge detection},
      author={Liu, Yun and Cheng, Ming-Ming and Hu, Xiaowei and Bian, Jia-Wang and Zhang, Le and Bai, Xiang and Tang, Jinhui},
      journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
      volume={41},
      number={8},
      pages={1939--1946},
      year={2019},
      publisher={IEEE}
    }
    
    @inproceedings{cheng2016hfs,
      title={{HFS}: Hierarchical Feature Selection for Efficient Image Segmentation},
      author={Cheng, Ming-Ming and Liu, Yun and Hou, Qibin and Bian, Jiawang and Torr, Philip and Hu, Shi-Min and Tu, Zhuowen},
      booktitle={European Conference on Computer Vision},
      pages={867--882},
      year={2016},
      organization={Springer}
    }
    
    @conference{liu2018deep,
      title={{DEL}: Deep Embedding Learning for Efficient Image Segmentation},
      author={Yun Liu and Peng-Tao Jiang and Vahan Petrosyan and Shi-Jie Li and Jiawang Bian and Le Zhang and Ming-Ming Cheng},
      booktitle={International Joint Conference on Artificial Intelligence},
      pages={864--870},
      year={2018}
    }

### Citations

[1] RCF

    @article{liu2019richer,
      title={Richer convolutional features for edge detection},
      author={Liu, Yun and Cheng, Ming-Ming and Hu, Xiaowei and Bian, Jia-Wang and Zhang, Le and Bai, Xiang and Tang, Jinhui},
      journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
      volume={41},
      number={8},
      pages={1939--1946},
      year={2019},
      publisher={IEEE}
    }
    
[2] COB

    @article{maninis2017convolutional,
      title={Convolutional oriented boundaries: From image segmentation to high-level tasks},
      author={Maninis, Kevis-Kokitsi and Pont-Tuset, Jordi and Arbel{\'a}ez, Pablo and Van Gool, Luc},
      journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
      volume={40},
      number={4},
      pages={819--833},
      year={2017},
      publisher={IEEE}
    }
    
[3] HED

    @article{xie2017holistically,
      title={Holistically-Nested Edge Detection},
      author={Xie, Saining and Tu, Zhuowen},
      journal={International Journal of Computer Vision},
      volume={125},
      number={1-3},
      pages={3--18},
      year={2017},
      publisher={Kluwer Academic Publishers Norwell, MA, USA}
    }
    
[4] HFS
    
    @inproceedings{cheng2016hfs,
      title={{HFS}: Hierarchical Feature Selection for Efficient Image Segmentation},
      author={Cheng, Ming-Ming and Liu, Yun and Hou, Qibin and Bian, Jiawang and Torr, Philip and Hu, Shi-Min and Tu, Zhuowen},
      booktitle={European Conference on Computer Vision},
      pages={867--882},
      year={2016},
      organization={Springer}
    }
    
[5] DEL
    
    @conference{liu2018deep,
      title={{DEL}: Deep Embedding Learning for Efficient Image Segmentation},
      author={Yun Liu and Peng-Tao Jiang and Vahan Petrosyan and Shi-Jie Li and Jiawang Bian and Le Zhang and Ming-Ming Cheng},
      booktitle={International Joint Conference on Artificial Intelligence},
      pages={864--870},
      year={2018}
    }
    
[6] HFL

    @inproceedings{bertasius2015high,
      title={High-for-low and low-for-high: Efficient boundary detection from deep object features and its applications to high-level vision},
      author={Bertasius, Gedas and Shi, Jianbo and Torresani, Lorenzo},
      booktitle={IEEE International Conference on Computer Vision},
      pages={504--512},
      year={2015}
    }

[7] DeepContour

    @inproceedings{shen2015deepcontour,
      title={Deep{C}ontour: A deep convolutional feature learned by positive-sharing loss for contour detection},
      author={Shen, Wei and Wang, Xinggang and Wang, Yan and Bai, Xiang and Zhang, Zhijiang},
      booktitle={IEEE Conference on Computer Vision and Pattern Recognition},
      pages={3982--3991},
      year={2015}
    }

[8] DeepEdge

    @inproceedings{bertasius2015deepedge,
      title={Deep{E}dge: A multi-scale bifurcated deep network for top-down contour detection},
      author={Bertasius, Gedas and Shi, Jianbo and Torresani, Lorenzo},
      booktitle={IEEE Conference on Computer Vision and Pattern Recognition},
      pages={4380--4389},
      year={2015}
    }

[9] OEF

    @inproceedings{hallman2015oriented,
      title={Oriented edge forests for boundary detection},
      author={Hallman, Sam and Fowlkes, Charless C},
      booktitle={IEEE Conference on Computer Vision and Pattern Recognition},
      pages={1732--1740},
      year={2015}
    }

[10] MCG

    @article{pont2016multiscale,
      title={Multiscale combinatorial grouping for image segmentation and object proposal generation},
      author={Pont-Tuset, Jordi and Arbelaez, Pablo and Barron, Jonathan T and Marques, Ferran and Malik, Jitendra},
      journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
      volume={39},
      number={1},
      pages={128--140},
      year={2016},
      publisher={IEEE}
    }

[11] SE

    @inproceedings{dollar2013structured,
      title={Structured forests for fast edge detection},
      author={Doll{\'a}r, Piotr and Zitnick, C Lawrence},
      booktitle={IEEE International Conference on Computer Vision},
      pages={1841--1848},
      year={2013}
    }

[12] gPb-UCM

    @article{arbelaez2011contour,
      title={Contour detection and hierarchical image segmentation},
      author={Arbelaez, Pablo and Maire, Michael and Fowlkes, Charless and Malik, Jitendra},
      journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
      volume={33},
      number={5},
      pages={898--916},
      year={2011},
      publisher={IEEE}
    }

[13] ISCRA

    @inproceedings{ren2013image,
      title={Image segmentation by cascaded region agglomeration},
      author={Ren, Zhile and Shakhnarovich, Gregory},
      booktitle={IEEE Conference on Computer Vision and Pattern Recognition},
      pages={2011--2018},
      year={2013}
    }

[14] Pb

    @article{martin2004learning,
      title={Learning to detect natural image boundaries using local brightness, color, and texture cues},
      author={Martin, David R and Fowlkes, Charless C and Malik, Jitendra},
      journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
      volume={26},
      number={5},
      pages={530--549},
      year={2004},
      publisher={IEEE}
    }

[15] BEL

    @inproceedings{dollar2006supervised,
      title={Supervised learning of edges and object boundaries},
      author={Dollar, Piotr and Tu, Zhuowen and Belongie, Serge},
      booktitle={IEEE Conference on Computer Vision and Pattern Recognition},
      pages={1964--1971},
      year={2006},
      organization={IEEE}
    }

[16] NCut

    @article{shi2000normalized,
      title={Normalized cuts and image segmentation},
      author={Shi, Jianbo and Malik, Jitendra},
      journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
      volume={22},
      number={8},
      pages={888--905},
      year={2000},
      publisher={IEEE}
    }

[17] EGB

    @article{felzenszwalb2004efficient,
      title={Efficient graph-based image segmentation},
      author={Felzenszwalb, Pedro F and Huttenlocher, Daniel P},
      journal={International Journal of Computer Vision},
      volume={59},
      number={2},
      pages={167--181},
      year={2004},
      publisher={Springer}
    }

[18] Canny

    @article{canny1986computational,
      title={A computational approach to edge detection},
      author={Canny, John},
      journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
      number={6},
      pages={679--698},
      year={1986},
      publisher={IEEE}
    }

[19] MShift

    @article{comaniciu2002mean,
      title={Mean shift: A robust approach toward feature space analysis},
      author={Comaniciu, Dorin and Meer, Peter},
      journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
      volume={24},
      number={5},
      pages={603--619},
      year={2002},
      publisher={IEEE}
    }

[20] Sobel
    
    @techreport{sobel1972camera,
      title={Camera models and machine perception},
      author={Sobel, Irwin},
      year={1972},
      institution={Computer Science Department, Technion}
    }

[21] Roberts

    @phdthesis{roberts1963machine,
      title={Machine perception of three-dimensional solids},
      author={Roberts, Lawrence G},
      year={1963},
      school={Massachusetts Institute of Technology}
    }

[22] SE+NG+

    @inproceedings{gupta2014learning,
      title={Learning rich features from RGB-D images for object detection and segmentation},
      author={Gupta, Saurabh and Girshick, Ross and Arbel{\'a}ez, Pablo and Malik, Jitendra},
      booktitle={European Conference on Computer Vision},
      pages={345--360},
      year={2014},
      organization={Springer}
    }

[23] gPb+NG

    @inproceedings{gupta2013perceptual,
      title={Perceptual organization and recognition of indoor scenes from RGB-D images},
      author={Gupta, Saurabh and Arbelaez, Pablo and Malik, Jitendra},
      booktitle={IEEE Conference on Computer Vision and Pattern Recognition},
      pages={564--571},
      year={2013}
    }
