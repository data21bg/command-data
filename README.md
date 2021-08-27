# 命令行中的数据科学
Data Science at the Command Line  
用久经考验的工具面向未来  

**linux bash 偏向**  
80个实用命令行工具，以及如何使用它们高效地获取、清洗、探索和建模数据。
https://github.com/jeroenjanssens/data-science-at-the-command-line
## 两个版本
2015年6月 第1版 使用 VirtualBox虚拟机    
  第2版 en   改vBox为docker    

个人网站是 http://jeroenjanssens.com/  
http://datascienceatthecommandline.com/

cut、sort、sed  
scrape、jq、json2csv  
这些工具本身并不是最重要的，用工具、管道和数据进行工作的思想才是最重要的。  

**数据获取 -> 清洗 -> 探索 -> 建模 -> 解释**    
## 第1章  数据科学就是OSEMN 

数据科学：(1)数据获取；(2)数据清洗；(3)数据探索；(4)数据建模；(5)数据解释。  
这5个步骤一起构成了OSEMN（发音同awesome）模型。  
  
1. 数据获取
* 从其他地方（如网页或服务器）下载数据
* 从数据库或API（如mysql或Twitter）中查询数据
* 从其他文件（如html文件或电子表格）中提取数据
* 自已生成数据（如读取传感器或进行调查）
2. 数据清洗
* 常见的操作：
* 行过滤
* 列抽取
* 值替换
* 单词提取
* 缺失值处理
* 数据格式转换
  
**任何数据项目中80%的工作都是数据清洗**

3. 数据探索
* 查看数据
* 从数据中推导统计量
* 创建有趣的可视化
4. 数据建模
* 为数据建立一个统计模型
* 包知聚类、分类、回归以及降维
5. 数据解释
* 从数据中得出结论
* 评估结查的含义
* 告知你的结果

## 第2章 VirtualBox