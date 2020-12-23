# Nuclear-power-investment-project-resarch
背景：
随着中国大陆经济增长，对电力的需求不断增加，同时受制于能源结构和环保（碳排放）责任，导致大陆必须在电力上采用更多清洁能源，而其中光伏、风力、水电的装机已经铺开，但这三种都局限于地理环境，不能在东南多省的地方实施，只能通过特高压进行传输，这样又提高了电力成本，而且非常局限于输电线的传输效率和最大能力。从实际场景来看，能够解决东南诸省电力缺口较为合适的发电应该是核电，但核电的危险性很高，因此中国大陆在发展核电建设上非常谨慎，虽然技术能力很强，但开工建设，尤其是新增核电厂很少。另外，中国属于贫铀国家（今年来也发现了一些大型铀矿），但铀矿也是制约核电发展的瓶颈。从预感上核电会加快进程，2030年要实现碳排放峰值，同时满足经济发展，核电投资建设应该从“十四五”开始做起。
综上，未来中国的核电是否可投资，需要评估（1）经济增长导致的电力缺口。（2）清洁能源的电力装机数。（3）铀矿的供给。（4）政策管制的放松情况。

目的：调研下中国大陆未来核电的投资可行性。
主要步骤需求如下：
1。获取近几年中国大陆经济发展和电力需求的数据，建立模型预测未来的电力需求。精细的话需要获取各省的电力与经济数据。
2。获取清洁能源和火力发电的装机数，配合电力来预测缺口。
3。获取中国铀矿探测、开采、储备和进口数量，分析其趋势走向。
4。获取近几年核电在中国的发展规划。

数据获取文档：

部分数据分析结论：
1.通过excel 拟合 GDP和电力消耗总量，可得如下公式：
电力：y
GDP: X
 y = 0.0001x2 + 3.5811x + 24102
通过此可以通过预测GDP增长来预测电力需求总量。
当然也可以对GDP/电力消耗分别进行拟合计算预估。 
2.分析各类发电中各类火力、水力、风力、太阳能、核电的占比及数据增长情况。
2000-2018年火力占比：
![image](https://github.com/Gitrege/Nuclear-power-investment-project-resarch/blob/main/images/fire.png)
2000-2018年水力占比：
![image](https://github.com/Gitrege/Nuclear-power-investment-project-resarch/blob/main/images/water.png)
2000-2018年风力占比：
![image](https://github.com/Gitrege/Nuclear-power-investment-project-resarch/blob/main/images/wind.png)
2000-2018年核电占比：
![image](https://github.com/Gitrege/Nuclear-power-investment-project-resarch/blob/main/images/nuclear.png)
2000-2018年太阳能占比：
![image](https://github.com/Gitrege/Nuclear-power-investment-project-resarch/blob/main/images/solar_energy.png)
