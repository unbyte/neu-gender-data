# 东北大学 性别统计

> 当前版本数据存在缺漏

## 数据格式

```
{
  学院名: {
    专业名: {
      年级名: {
        班级名: [男生人数，女生人数]     
      }    
    }  
  }
}
```



## 一些问题

爬虫就不放出来了

目前得到的人数有几种情况是被我**删除**掉了的

- 班级人数为0

- 班级人数为1

- 班级人数小于4，且年级早于2016级

同时数据存在以下几种**问题**：

- 缺失部分专业（被上文的规则删除或数据源未录入）

- 缺失部分班级（被上文的规则删除或数据源未录入）

- 数据不一定准确（数据源可能存在测试数据）

> 如果感兴趣的人多的话，我会用可信且完整的数据做一个东大性别报告
>
> ~~如果没有就咕咕咕~~