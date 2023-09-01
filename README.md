-----------------------权重文件-------------------------
##weight_self文件夹中##
best-data1.pt：检测电风扇、药瓶、消毒液、盒子、玩具五类物体的模型
best-show.pt：可以将办公室绿萝识别为杂草的检测+分割模型
best-weed.pt：一版效果不太好的杂草识别的检测模型
weed_corn.pt：玉米地杂草识别的检测模型
weed_seg.pt：玉米地杂草识别的检测+分割模型
-----------------------运行命令-------------------------
##orders文件夹中##
ros_predict2.sh：包含检测、检测框选择、深度计算（检测框中心）、坐标转换、ros话题发布和分割的代码运行
seg_train.sh：训练分割模型的命令
-----------------------模型训练--------------------------
train-explain.txt：训练流程提示
-----------------------数据集----------------------------
data1：电风扇、药瓶、消毒液、盒子、玩具五类物体的检测数据集
data_show：绿萝数据集
data_weed&corn2：玉米地杂草数据集

