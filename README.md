# dn11 元数据

用于 monitor web展示

```json
{
    "display":"yolande",
    "appendix":{
        "geo": "杭电生活区32号楼"
    },
    "customNode":{
        "itemStyle":{
            "color":"#d83b01"
        }
    }
}
```

| 字段       | 解释                                                              |
| ---------- | ----------------------------------------------------------------- |
| display    | 展示名称                                                          |
| appendix   | 附加tooltip内容，请使用 map[string]string 的格式                  |
| customNode | 参考<https://echarts.apache.org/zh/option.html#series-graph.data> |

前面两个选项是提供给想要特效但是不像看echarts的懒狗的，后面的customNode的属性会被合并到as的那个node，

这已经可以修改很多配置了，后续可能会开放模板渲染，提供一些计算功能
