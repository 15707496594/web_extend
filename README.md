## web_extend
Odoo 界面美化

## 特性
- 模块安装即可使用，轻量简单，不改变原有结构
- 支持 odoo 11
- 支持 icon 图标，可以在odoo菜单页设置图片样式名 如“fa fa-circle-o


## 说明
要支持子菜单显示icon图标请做如下修改
```
#odoo/tools/convert.py 中

if not values.get('parent_id'):
改为
if 1:
```

## 参考
http://www.oejia.net/

