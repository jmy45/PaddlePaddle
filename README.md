# 这是百度AISTUDIO七天打卡的作业  
1、第一天是熟悉PaddleDetection，主要是路标牌的检测。  
2、第二天是RCNN系列网络用于PCB缺陷检测。  
3、第三天是YOLO系列网络用于PCB缺陷检测。  
4、第四天是CVPR比赛冠军讲述商超检测以及目标检测比赛测量。  
5、第五天是Anchor-FREE系列网络用于PCB缺陷检测。  


PCB数据集下载地址：
http://robotics.pkusz.edu.cn/resources/dataset/

##  PPDETECTION官方给出的配置文件：  
 模型	| mAP(Iou=0.50:0.95)	| mAP(Iou=0.50)	| 配置文件
  ----  | :----:                | :----:        | :----:
  Faster-RCNN-R50_vd_FPN_3x	| 52.7	| 97.7	| faster_rcnn_r50_vd_fpn_3x.yml
  YOLOv3_darknet	| 44.8	| 94.6	| yolov3_darknet.yml
  FCOS_R50_FPN_multiscale_3x	| 54.9	| 98.5	| fcos_r50_fpn_multiscale_3x.yml


