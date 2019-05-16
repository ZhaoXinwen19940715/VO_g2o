# VO_g2o

利用g2o对PnP计算出的结果进行优化

请按照高翔博士后的《视觉SLAM十四讲》安装前九讲中除g2o的所有库，g2o库请安装github上的版本

建议利用CMake进行编译：

mkdir build

cd build

cmake ..

make

调用时使用控制台，本程序的demo针对kitti数据集的序列三
在控制台中使用如下方法调用：

进入VO_g2o主目录：cd VO_g2o

启动程序：./bin/run_vo config/default.yaml /home/wen/dataset/1/03

ps：/home/wen/dataset/1/03为作者的kitti数据集所在目录，需根据自己的情况进行更改
