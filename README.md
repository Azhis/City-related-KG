城市相关知识图谱介绍
===
# 1 常识通用类知识图谱
## 1.1 CN-DBpedia
**链接**：[http://www.openkg.cn/dataset/cndbpedia](http://www.openkg.cn/dataset/cndbpedia)

**类型**：城市  
**属性**：下辖地区、中文名称、人口、人均支配收入、人均生产总值、人类发展指数、住户存款总额、别名、名人、地区生产总值、地理位置、城镇化率、城市简称、城市名片、城市定位、城市精神、城市轨道、外文名称、市树、市歌、市花、建成区面积、所属地区、政府驻地、方言、最高建筑、机场、民间信仰、气候条件、消费品零售额、火车站、现任领导、电话区号、著名景点、行政代码、行政区类别、车牌代码、邮政区码、面积、高等学府

**类型**：空气质量  
**属性**：分类、危害、外文名称、污染源

**类型**：风俗习惯  
**属性**：中文名、定义、性质、由于（一种历史形成）

## 1.2 Belief-Enginee
**链接**：[http://www.openkg.cn/dataset/belief-engine](http://www.openkg.cn/dataset/belief-engine)  
**类型**：城市  
**属性**：中文名称、气候条件、行政区类别、所属地区、地理位置、火车站、机场、语种、市花、市树、医院类型、医院等级、学校属性、别名、著名景点、政府驻地、主要食材、方言

## 1.3 BabelNet-多语言百科字典和语义网络
BabelNet采用的方法是将WordNet词典与Wikipedia百科集成。
**链接**：[http://www.openkg.cn/dataset/babelnet](http://www.openkg.cn/dataset/babelnet)  
**类型**：城市  
**属性**：中文名称、简称、国家、省份、下辖地区、市长、市委书记、时区、边界城市  

# 2 气象类知识图谱
## 2.1 空气质量语义描述
将空气质量等传感器数据离散化，增加上下文语义描述，外链到气象、相关疾病、健康等数据。本数据集提供实时流式数据API，可获取实时动态的语义化空气质量数据。  
**链接**：[http://www.openkg.cn/dataset/airquality](http://www.openkg.cn/dataset/airquality)  
**属性**：  
**本体属性**  
hasAir	空气质量					     value：优、严重污染、重度污染  
hasDayOfWeek	一周中的某天	value：工作日、休息日  
hasHourOfDay		一天中的某小时		value：早高峰时段、晚高峰时段、非高峰时段  
hasSensorLocation	观测点				value：广州观测站、杭州观测站...  
hasTimeInterval	观测时间			具体数值  
hasWind	风							value：清风、微风、大风...  
**数据属性**  
endTime	结束时间点  
hasAQIValue	AQI值        
hasCOValue	CO值  
hasCloudCoverValue	云量值  
hasDayValue	第几天值  
hasHourValue	第几小时值  
hasHumidityValue	有湿度值  
hasLatValue	有纬度值  
hasLocationCityValue	有所处城市值  
hasLonValue	经度值  
hasNO2Value	NO2值  
hasNameValue	名称  
hasO3Value	O3值  
hasPM10Value	PM10值  
hasPM25Value	PM2.5值  
hasPrecipitationValue	降水量值  
hasPressureValue	大气压值   
hasPrimaryPollutantValue	主要污染物值  
hasSO2Value	SO2值  
hasTemperatureValue	气温值  
hasVisibilityValue	能见度值  
hasWeatherDescriptionValue	天气描述值	value：多云、有雾  
hasWindBeaufortScaleValue	风力级别值	value：微风、清风、大风...  
hasWindDirectionValue	风向值  
startTime	开始时间点  
**举例**：
![Image text](https://github.com/Azhis/City-related-KG/blob/main/img/1.png)
## 2.2 城市内涝语义数据
提供结构化的城市内涝数据，外链至气象、交通、微博等数据。  
目前提供十个城市的数据。  
**链接**：[http://www.openkg.cn/dataset/groups/water-logging](http://www.openkg.cn/dataset/groups/water-logging)  
**属性**：  
**本体属性**  
hasCity	所在城市  
hasDayOfWeek	一周中的某天  
hasHourOfDay		一天中的某小时  
hasMeteorology	气象条件  
hasPrecipitation	降水量   
hasSensorLocation	观测点  
hasSeverity	严重程度					  
hasTerrain	地势  
hasTraffic		交通状况  
hasWaterloggingOccuranceLocation	地点	  
hasWeatherType	天气  
**数据属性**  
hasDayValue	第几天值  
hasHourValue	第几小时值  
hasLatValue	纬度值  
hasLocationCityValue	所处城市值  
hasLonValue	经度值  
hasPictureUrl	描述图片链接  
hasPrecipitationValue	降水量值			value：大雨  
hasSeverity	严重程度					value：无内涝、轻微  
hasTerrainValue	地势值					value：平地、高地  
hasTrafficValue	交通状态值				value：车速慢、通畅、拥堵  
hasWaterloggingLocation	内涝地点		value：成都、北京  
hasWaterloggingTime	内涝时间  
hasWeiboText	微博描述值  
**举例**：  
 ![Image text](https://github.com/Azhis/City-related-KG/blob/main/img/2.png)
## 2.3 天气语义数据  
提供语义化的气象数据，外链到相关疾病、健康等数据。  
**链接**：[http://www.openkg.cn/dataset/weather](http://www.openkg.cn/dataset/weather)  
**属性**  
**本体属性**  
hasAir	空气质量   
hasDayOfWeek	一周中的某天  
hasHourOfDay		一天中的某小时  
hasMeteorology	气象条件  
hasSensorLocation	观测点  
hasWeatherType	天气  
hasWind	有风  
**数据属性**  
endTime	结束时间点   
hasAQIValue	AQI值  
hasCOValue	CO值  
hasDayValue	第几天值  
hasHumidityValue	湿度值  
hasLatValue	纬度值  
hasLocationCityValue	所处城市值  
hasNO2Value	NO2值  
hasNameValue	名称值  
hasO3Value	O3值  
hasPM10Value	PM10值  
hasPM25Value	PM2.5值  
hasPrecipitationValue	降水量值  
hasPressureValue	大气压值  
hasSO2Value	SO2值  
hasTemperatureValue	气温值  
hasVisibilityValue	能见度值  
hasWeatherDescriptionValue		天气描述值  
hasWindDirectionValue	风向值  
startTime		开始时间点  
**举例**：  
![Image text](https://github.com/Azhis/City-related-KG/blob/main/img/3.png)
# 3 地理类知识图谱
## 3.1 OpenStreetMap和Wikidata的实体链接数据集（中国区域）  
**链接**：[http://www.openkg.cn/dataset/openstreetmap-wikidata](http://www.openkg.cn/dataset/openstreetmap-wikidata)  
**属性**：ID、类型、地点名称（中、英文）、经度、纬度、WKT格式的地理信息、与之有 same as关系的实体  
**举例**：  
 ![Image text](https://github.com/Azhis/City-related-KG/blob/main/img/4.png)
## 3.2 中国旅游景点知识图谱
中国旅游景点中文知识图谱是CASIA-KB知识图谱的一部分。抽取自百度百科和互动百科。旅游景点知识图谱可用于地理、生活、娱乐等应用。  
**链接**：[http://www.openkg.cn/dataset/tourist-attraction](http://www.openkg.cn/dataset/tourist-attraction)  
**属性**：中文名称、别名、行政级别、下辖地区、电话区号、邮政编码、地理位置、面积、人口、方言、气候条件、机场、火车站、区长、车牌代号  
**举例**：   
![Image text](https://github.com/Azhis/City-related-KG/blob/main/img/5.png)
## 3.3 Clinga  [中文地理链接数据集]  
数据源自最大的中文维基百科。手工构建了一个新的地理本体对各种自然地理和人文地理实体进行分类，并自动与现有知识库进行链接。所得到的Clinga数据集现包含50多万中文地理实体，并已公开访问。  
**链接**：[http://www.openkg.cn/dataset/clinga](http://www.openkg.cn/dataset/clinga)  
### 3.3.1 人文地理类  
**属性**：  
下辖地区、所属地区、国歌、现任校长、分类、院长、国家领袖、地点、政治体制、货币、学校类型、医院等级、气候、火车站、官方语言、方言、主要宗教、行政区类别、经济类型、医院类型、经营范围、机场、主要民族、首都、人口密度、面积  
**举例**：  
 ![Image text](https://github.com/Azhis/City-related-KG/blob/main/img/6.png)
![Image text](https://github.com/Azhis/City-related-KG/blob/main/img/7.png)
 
### 3.3.2 自然地理类
**属性**：起点、发现者、地理区域、所属山系、流经地区、发源地、所属洲、终点、植被类型  
**举例**：  
 ![Image text](https://github.com/Azhis/City-related-KG/blob/main/img/8.png)
# 4 医学类知识图谱（新冠专题）
## 4.1 新冠开放知识图谱-流行病
**链接**：[http://openkg.cn/dataset/covid-19-epidemiology](http://openkg.cn/dataset/covid-19-epidemiology)  
**属性**：  
流行病学调查报告（发病指标、死亡指标、时间范围、地域范围、流行强度）  
流行特征（人群分布、地域分布、时间分布）  
疫源地（疫区、疫点）  
被调查个体基本情况（ID、年龄、性别、种族、常住地、职业、归属地）  
被调查个体活动记录（时间/时间段、地点、事件类型、时间细节）  
疫区接触史  
## 4.2新冠开放知识图谱-事件
**链接**：[http://openkg.cn/dataset/covid-19-event](http://openkg.cn/dataset/covid-19-event)  
**属性**：标题、发布时间、创建时间、修改时间、时间地点id、时间地点名称、简介、网址、消息来源、之前发生、政策标题、政策发布日期、政策成文日期、政策成文日期、政策发文字号、政策发文机构、政策对象、政策依据、政策落款、政策有关事项、政策内容、后续政策  
## 4.3 新冠开放知识图谱-英雄
**链接**：[http://openkg.cn/dataset/covid-19-character](http://openkg.cn/dataset/covid-19-character)  
**属性**：人物、履历、任职机构、所在城市、参与战役、参与事件、所属救援队、事件地点、战役爆发地点  
# 5 金融类知识图谱
## 5.1 股票相关知识图谱 
爬取了港股、a股、美股的相关数据，搭建了一个知识图谱，基于REfO实现了一个简单的KBQA并且做了一些图相关分析。  
**链接**：[http://www.openkg.cn/dataset/stockdata](http://www.openkg.cn/dataset/stockdata)
**属性**：上市场所，公司名称，公司总裁，公司简称，公司网址，办公地址，员工人数，所属行业，注册地址，联系传真，联系电话，股票代码，英文名称，邮政编码  
## 5.2 企业投资事件知识图谱
主要包含企业的基础信息和企业之间的投资事件信息。  
**链接**：[http://www.openkg.cn/dataset/data2](http://www.openkg.cn/dataset/data2)  
**属性**：法定代表人，注册资本，实缴资本，经营状态，成立日期，统一社会信用代码，纳税人识别号，注册号，组织机构代码，企业类型，所属行业，核准日期，登记机关，所属地区，英文名，曾用名，参保人数，人员规模，营业期限，企业地址，经营范围，融资事件（投资人，轮次，金额，日期）  


