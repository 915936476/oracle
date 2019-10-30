#  实验四

### 在实验三时创建user02的分区以及给luzheng授权

### 创建DEPARTMENTS表，PRODUCTS表，EMPLOYEES表，ORDERS表，ORDER_DETAILS表

![截图1](img/1.png);
![截图1](img/2.png);
![截图1](img/3.png);
![截图1](img/4.png);
![截图1](img/5.png);
![截图1](img/6.png);
![截图1](img/8.png);

### 创建触发器


![截图1](img/7.png);
![截图1](img/9.png);
![截图1](img/10.png);
![截图1](img/11.png);
![截图1](img/12.png);
![截图1](img/13.png);
![截图1](img/14.png);
![截图1](img/15.png);
![截图1](img/16.png);

### 向表中插入数据

![截图1](img/17.png);
![截图1](img/18.png);
![截图1](img/19.png);
![截图1](img/20.png);


### 查询数据

####  1.查询某个员工的信息
![截图1](img/21.png);

####  2.递归查询某个员工及其所有下属，子下属员工。
![截图1](img/22.png);

####  3.查询订单表，并且包括订单的订单应收货款: Trade_Receivable= sum(订单详单表.ProductNum*订单详单表.ProductPrice)- Discount。
![截图1](img/26.png);

####  4.查询订单详表，要求显示订单的客户名称和客户电话，产品类型用汉字描述。
![截图1](img/23.png);

####  5.查询出所有空订单，即没有订单详单的订单。
![截图1](img/24.png);

####  6.查询部门表，同时显示部门的负责人姓名。
![截图1](img/25.png);
