# Task 2
# num_workers是什么？线程和进程是什么？
# listdir() takes at most 1 argument (2 given)怎么解决？——>在本地文件途径后面加上"+'utf-8'"编译器理解为两个途径，why???
# window系统输入途径一定要把'\'改成'/'！！！！！！！！！！！！
# 将照片中的像素的BGR坐标进行线性运算（？）可以对图像进行灰度化处理——>m = img[i,j]
# img_gray[i,j] = int(m[0]*x + m[1]*y + m[2]*z) 其中x+y+z=1
# 为什么该代码第37行改为plt.imshow(img_gray)，无论对BGR坐标如何改动图像都一样（偏绿）？
# cudart64_110.dll到底要放在哪里？？？！！！！
# 配置虚拟环境，把packages重新下到新的虚拟环境真的好麻烦...
# 为什么一共有七个表情，最后一个model.add一定要输出一个八维的向量？
# 卷积网络的理解：以表情举例，将同一种表情的不同图片通过池化层抽取出特征后，进行不同表情的测试，判断表情错误则减少学习率，被错误的判断所导致的表情误解就会减少，受错误判断的影响就少，随着训练次数的增加，正确率越来越高，正反馈调节下机器判断表情种类的目的达成
# Q5：用flow_from_directory导入图像的数据；用model.fit设置训练批数，次数，导入callback回调函数用于记录数据并反向传播，达到训练的目的；卷积神经网络
