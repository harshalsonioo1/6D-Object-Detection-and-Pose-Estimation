# MM811
6D pose estimation for texture-less objects

Link to our output video: https://drive.google.com/file/d/1ZAqdDL_1SRXoqvDgrJrdtlK29OeypVzU/view?usp=sharing

The files are arranged in order. 
1. init is loaded and envirment is set up
2. download T-less dataset from http://cmp.felk.cvut.cz/t-less/ and run prepare data
3. train the data using train.py
4. test the data using test.py

References:
1. @inproceedings{you2018pvnet,
  title={Pvnet: A joint convolutional network of point cloud and multi-view for 3d shape recognition},
  author={You, Haoxuan and Feng, Yifan and Ji, Rongrong and Gao, Yue},
  booktitle={2018 ACM Multimedia Conference on Multimedia Conference},
  pages={1310--1318},
  year={2018},
  organization={ACM}
}
2. @inproceedings{li2018deepim,
  title={Deepim: Deep iterative matching for 6d pose estimation},
  author={Li, Yi and Wang, Gu and Ji, Xiangyang and Xiang, Yu and Fox, Dieter},
  booktitle={Proceedings of the European Conference on Computer Vision (ECCV)},
  pages={683--698},
  year={2018}
}

