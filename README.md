# 前言

欢迎来到基于SSM（Spring、SpringMVC、MyBatis）的药品进销存系统项目。该项目旨在为药品销售企业提供一套高效的药品库存管理系统，实现药品的采购、销售、库存等业务流程的数字化管理。以下是关于本项目的详细介绍。

## 内容介绍

基于SSM的药品进销存系统主要包含以下功能模块：药品信息管理、供应商管理、客户管理、采购管理、销售管理、库存管理等。通过这些模块，企业可以实时了解药品库存状况，提高库存周转率，降低运营成本。

系统采用前后端分离的开发模式，前端负责展示数据和接收用户操作，后端处理业务逻辑和数据存储。此外，系统还提供了完善的权限控制功能，确保数据安全。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12、14、16

## 核心代码

以下是一段关于药品信息管理的核心代码示例：

```java
// 药品信息管理Service层
@Service
public class DrugService {

    @Autowired
    private DrugMapper drugMapper;

    // 查询药品信息
    public List<Drug> getDrugList() {
        return drugMapper.getDrugList();
    }

    // 根据药品ID查询药品信息
    public Drug getDrugById(int id) {
        return drugMapper.getDrugById(id);
    }

    // 添加药品信息
    public int addDrug(Drug drug) {
        return drugMapper.addDrug(drug);
    }

    // 修改药品信息
    public int updateDrug(Drug drug) {
        return drugMapper.updateDrug(drug);
    }

    // 删除药品信息
    public int deleteDrug(int id) {
        return drugMapper.deleteDrug(id);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/340277/39/8926/156566/68c06ef7F834a6eb0/4ea0ffda00637481.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/328139/6/18027/19314/68c06ecfF298b4d65/14b04f4ce51e7c5b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327280/9/18138/102123/68c06ecfF3a62e5cf/3294d4e73e4d2160.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/341651/5/1406/26706/68c06ecfF82c22230/cd0e6c0129675b38.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/346346/25/1108/97787/68c06ed0Fb305b239/7e3f149e1f627193.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/324992/28/18008/39229/68c06ed0Fabc9d73c/70a2bc6cf99661a2.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/323177/36/16370/115103/68c06ed1Fe13e3854/79545ac8233b9adc.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/324833/1/18152/66263/68c06ed1F0c7c6cfa/f98354e850325550.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/337991/39/8838/48844/68c06ed1F9e75a837/c84ba774c699cd82.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/329503/31/11356/17195/68c06ed2F7be59529/41bf8ff7d381853b.jpg)

