[英文文档](./README_CN.md)
# simple-image-slide-compare
一个简单的离线版滑动图片比较器

# 特性
* 无需上传图片，只需要选择本地图片即可使用。**注意** 对比图片最好是高宽比例相同。如左图分辨率512*1024，对比图可以为768*1536, 1024*2048等等
* 支持滚轮针对某块特定区域放大、缩小对比。

# 示例

0. 右键浏览器打开`image-slide-compare.html`

1. 左图上传一张1024*1536的图片
![image](./img/before.png)

2. 右图上传一张通过upscaly高清放大4096*6144后的图片
![image](./img/highres.png)

3. 上传后
![image](./example1.png)

4. 鼠标箭头移动到嘴巴区域，然后滚轮放大
![image](./example2.png)
 可以明显看出到upscaly高大后没有细节上的变化，放大4倍后效果一般。