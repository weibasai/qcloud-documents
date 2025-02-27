## 什么是 TCBI
TCBI 是一款企业级、现代化、开放式的智能可视化分析平台。
您可通过拖拽式零代码的简单操作“自助式”制作多种可视化分析图表。并可以即时有效的把数据通过任意终端设备分享给同事，合作伙伴和客户。为公司里每个角色定制快速准确的分析和数据探索体验，更有效的辅助决策，帮助企业真正实现数字化驱动。

## 基本概念
**工作空间**：工作空间是一个或多个成员创建内容的地方，同一工作空间内的成员共享该空间下的资源和内容。
**TCBI v1.0 版本的空间规则**：在腾讯云当前登录体系下，腾讯云主账号拥有一个个人空间，个人空间里的内容只有主账号可以查看、访问和操作。主账号还拥有一个默认空间，每一个主账号下的所有子账号也都在这个默认空间下。
**仪表板**：仪表板是由一个或多个图表、文字、图片等一种或多种元素组成的可视化视图。
**数据集**：数据集是创建仪表板的基础，在获取数据后，如果需要对从数据库连接进 TCBI 的数据进行二次处理和清洗时，您可以在数据集的创建界面进行如下操作：重命名、创建字段、排序、数据表关联等。处理加工完成的数据既是一个数据集。
**工作簿**：工作簿是由一个或多个仪表板组成的。在工作空间内，用户可以发布、分享和订阅工作簿。还可以对工作簿进行分组，如您同时工作于多个项目，每个项目下都需要创建多个工作簿，此时为每个项目新建一个组就解决了给工作簿分类管理的作用。
**数据表**：从数据库中获取过来的，是一系列二维数组的集合，用来代表和储存数据对象之间的关系。
**字段**：数据表中代表数据的名称标识。
**维度**：维度是描述属性的数据字段，例如颜色、分类、性别。
**度量**：度量是描述数字的数据字段，例如个数、价格、长度。

## 数据类型

| 图标 | 数据类型 | 
|---------|---------|
| ![](https://qcloudimg.tencent-cloud.cn/raw/8c2e0c93c8cd320182cafec0b5e06ca0.png) | 文字| 
|![](https://qcloudimg.tencent-cloud.cn/raw/d2a9bef003459c1407a65ca48c14a790.png) | 数字 | 
| ![](https://qcloudimg.tencent-cloud.cn/raw/859440b9af64727fb18ccc60239d6ee5.png) | 日期 | 
| ![](https://qcloudimg.tencent-cloud.cn/raw/cc45b4fe5b23bb58690d2518a5d8c01f.png) | 地理位置 | 
| ![](https://qcloudimg.tencent-cloud.cn/raw/a3242bd1cc4a6429357585195caf56ca.png) | 图片 | 

## 图表类型及使用

| 图表类型 | 样式 | 图标要求|
|---------|---------|---------|
| 柱状图| ![](https://qcloudimg.tencent-cloud.cn/raw/25a434d354fb120f892d8fb4b0870220.png) | 1+维度，和1+度量 |
| 条形图 | ![](https://qcloudimg.tencent-cloud.cn/raw/a105027f5a215fa96ec40383c55b36f2.png) | 2+维度，和1+度量 |
| 折线图 | ![](https://qcloudimg.tencent-cloud.cn/raw/db16ab60e00934c8eef32eb4b0eec463.png) | 1维度（推荐时间维度），和1+度量 |
| 面积图 | ![](https://qcloudimg.tencent-cloud.cn/raw/e42bbc0f55594d512bfb1cc8220d6fde.png)| 1维度（推荐时间维度），和1+度量 |
| 堆叠柱状图 |![](https://qcloudimg.tencent-cloud.cn/raw/0ccb7c59ed4c52da43355a43cd3d786f.png) | 2+维度，和1+度量 |
| 堆叠条形图 | ![](https://qcloudimg.tencent-cloud.cn/raw/b5c82f358c3f5e2a2d78679af477aef3.png)| 2+维度，和1+度量 |
| 饼图 | ![](https://qcloudimg.tencent-cloud.cn/raw/96d34edb30cec082302588a90cfb2466.png) | 1 维度，和1度量 |
| 环图 | ![](https://qcloudimg.tencent-cloud.cn/raw/261ec1a5bb30558304ddec4ef4d4ff5f.png) | 1 维度，和1度量 |
| 雷达图| ![](https://qcloudimg.tencent-cloud.cn/raw/a3637cf06604ab76f51620f1fbc0a23b.png) | 1+维度，和1+度量 |
| 雷达图（面） | ![](https://qcloudimg.tencent-cloud.cn/raw/29d7bf26818c266fce54bb6e944645a0.png) | 1+维度，和1+度量 |
| 表格 | ![](https://qcloudimg.tencent-cloud.cn/raw/f0c0f5b72ffb13d5cb3d78d879951eb5.png) | 1+维度，和/或1+度量 |

## 使用流程
![](https://qcloudimg.tencent-cloud.cn/raw/83393687b5af9e2d6e1212fa88ffd9a6.png)

## 应用场景
TCBI 不仅是一个工具，它是一个完整的企业级商务智能解决平台。TCBI 可以让企业更好的利用大数据、云计算等的优势，进行数据建模、数据分析和数据可视化，实现数据辅助决策。

**政务场景**：利用大数据商业智能是实现数字化智慧城市转型的关键，结合物联网信息，可以更快更优的管理城市的交通信息、民生信息、医疗信息、社保管理、疫情数据监测、党政培训管理、园区信息等。实现资源的最优分配，辅助政府部门进行公共管理，利用数据科学决策。
**金融场景**：可以应用于营销、风控、财富管理等方面。包括对客户画像，提升客户价值，客户关系管理，绩效管理，风险控制信用等级评分，精准营销，反欺诈反洗钱等应用场景。
**零售场景**：可以应用于顾客行为分析，成本控制，库存管理，供应商管理，商品销售分析、盈利分析及预测等。应用 TCBI 可帮助实现业务增长，降低成本，提高市场占有率。
**医疗场景**：通过分析患者的健康信息，住院信息，医生的诊疗信息，手术数据，康复信息，药品信息，医疗器械信息，财务数据，从而提高患者康复，帮助医院提高运营效率和监管质量。
**工业场景**：可以应用于库存管理，生产效率和产品合格率的分析和预测，销售和订货信息的管理，产品质量管理，根据掌握的数据分析经销商和客户的情况以及优化生产线、改善业务运营。
**教育场景**：可应用于教育经费管理，学生成绩分析及预测，教师教学质量及授课情况分析和统计，学生素质技能分析，学校运行监测等。以此提高学生的综合素质和辅助学校运营管理。


