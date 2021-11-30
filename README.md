# 在线教育系统

## 课程模块

**tables design**

- lesson

  > code：课程编号varchar(100)

- chapter

  > title：章节标题













# 商城系统设计



## 订单-产品模块

**tables design**

- order_table
- order_setting`订单全局设置表`
- product
- sku_sock`商品sku库存表`

 ![order_task](D:\Users\26356\Desktop\MyNote\images\order_task.jpg)





















# 通用表设计



## 用户-角色-资源模块

**table design**

- admin

- login_log`登录日志表`

- admin_role_relation

- role

  > admin_count：拥有该角色的用户人数

- role_menu_lelation

- menu

  > parent_id：父类菜单id
  >
  > level：菜单级数

- role_rescourse_relation

- resource

- resouce_categoy`资源种类表[ˈkætəɡəri]`

 <img src="D:\Users\26356\Desktop\MyNote\images\login_authorization.png" alt="login_authorization" style="zoom:150%;" />







