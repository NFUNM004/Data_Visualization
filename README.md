## 数据可视化项目

### pythonanywhere连接入口：http://skyworth0130.pythonanywhere.com/

### 选题
全球麻疹案例数量、死亡率及麻疹疫苗接种情况分析

### 背景：
麻疹是最常见的急性呼吸道传染病之一，传染性很强，严重时可导致死亡，在人口密集而未普种疫苗的地区容易发生流行。随着麻疹疫苗的普及，
麻疹大流行基本上得到控制，但麻疹疫情在世界各地仍会偶尔爆发。因此我们通过全球麻疹案例的数量、疫苗接种情况等进行可视化，分析全球麻疹疫情的现状。


### 数据及来源

来源：
- 世界卫生组织官网
- 相关论文

数据收集：
- [麻疹第一剂（MCV1）各国接种率估算](http://http://apps.who.int/gho/data/node.main.A826?lang=en)
- [区域麻疹，第一剂疫苗（MCV1）覆盖率](http://apps.who.int/gho/data/view.main.81100?lang=en)
- [2011- 2019年按国家和月份分类的麻疹病例分布](https://www.who.int/immunization/monitoring_surveillance/burden/vpd/surveillance_type/active/measles_monthlydata/en/)
- [2000年与2018年麻疹疫情对比](https://s3.amazonaws.com/wp-agility2/measles/wp-content/uploads/2019/12/Progress-Toward-Regional-Measles-Elimination-2018.pdf)

---

### 数据分析及故事：
**图片无法显示可点击网页链接**

![全球各地区疫苗接种率](https://upload-images.jianshu.io/upload_images/9779994-c5cc3c414577f3af.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- http://skyworth0130.pythonanywhere.com/seven
- 此图表现的是从1980到2018年这38年来全球各地区的第一支麻疹疫苗接种率，随着疫苗接种知识的普及和医疗条件的提升，从1980开始麻疹疫苗接种率呈快速增长趋势，到1990年呈最高值，同时增长趋势开始放缓。

![近十年全球各国第一支疫苗接种率](https://upload-images.jianshu.io/upload_images/9779994-aff25c44cb65a727.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



![2018年各地区接种麻疹疫苗避免的麻疹死亡比例](https://upload-images.jianshu.io/upload_images/9779994-f66ab5f8fa80d034.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- http://skyworth0130.pythonanywhere.com/five 
- 上图是近十年各国第一支麻疹疫苗的接种率，可以看到疫苗接种率较低的地区主要还是非洲地区。
- http://skyworth0130.pythonanywhere.com/four 
- 下图是2018年各地区接种麻疹疫苗避免的麻疹死亡案例比例，随着非洲地区医疗条件逐渐改善，非洲地区疫苗接种率不断提升，2018年接种疫苗避免的麻疹死亡比例非洲占比最多，其次是亚洲。

- 值得注意的是，根据地图，从2015年之后，部分国家疫苗接种率逐渐在降低，南美洲接种率下降得较为明显。


![2000年与2018年麻疹病例报道对比](https://upload-images.jianshu.io/upload_images/9779994-9f46471045072ac1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![2000年与2018年麻疹发病率](https://upload-images.jianshu.io/upload_images/9779994-1ba7783ba14ae59b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



- http://skyworth0130.pythonanywhere.com/one 
- 对比2000年和2018年麻疹病例报道和麻疹发病率，非洲、东南亚、西太平洋地区麻疹病例和发病率都有明显降低，但地中海东部、欧洲、美洲则不降反升。

---

- 麻疹疫苗接种率下降，地中海东部、欧洲、美洲麻疹病例和发病率增长，近几年麻疹疫情是否不太乐观？



![2011到2019年全球各国麻疹案例](https://upload-images.jianshu.io/upload_images/9779994-615bd5750578d224.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


![2018年与2019年麻疹病例对比](https://upload-images.jianshu.io/upload_images/9779994-6db45a704c32bc64.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


 -  http://skyworth0130.pythonanywhere.com/six 
 - 透过2011年到2019年各国麻疹病例的时间轴地图，能够看到近三年麻疹病例激增。通过对比18年与19年的麻疹病例数量也证实了这一点，2019年麻疹病例确实比2018年有所提升。


#### 总结：
- 结合数据得知，经过麻疹疫苗这么多年的普及，麻疹病情在一定程度上得到了有效的遏制，特别是非洲、东南亚地区效果明显。但近几年全球麻疹疫苗接种率有所降低，麻疹疫情也有不断增长的趋势。

- 相关报道也有显示2018、2019年全球多个地区暴发大规模的麻疹疫情。中低收入国家疫苗短缺、疫苗覆盖不平衡、部分西方国家受“疫苗犹豫”（即“反疫苗”）情绪的影响等原因，也使得麻疹疫苗接种的情况不太乐观。世界卫生组织和各国国家也在对此情况进行努力，抑制麻疹疫情地增长。
