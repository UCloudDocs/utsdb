# 实例管理

完成新建时序数据库实例后，可以在控制台上管理时序数据库实例，如：启动、重启、关闭、重启实例，配置升降级、更改实例名称、更改业务组、更改告警模板、删除、续费、创建数据、设置保留策略等。

## 实例操作
时序数据库实例控制台基本操作主要有：启动、重启、关闭、续费、删除等功能。

![image](/images/influxdb001.png)

### 重启时序数据库实例
1.如果要重启处于关闭状态的时序数据实例，首先选择需要重启的时序数据库实例，在列表右侧点击“重启”按钮，弹出的确认对话框选择确定，即可重启时序数据库实例。
![image](/images/influxdb002.png)

2.如果需要同时重启多个时序数据库实例，选择相应的时序数据库实例，在批量操作项中选择“重启”，弹出的对话框选择“确定”，即可重启多个时序数据库实例。

![image](/images/influxdb008.png)

![image](/images/influxdb009.png)

### 关闭时序数据库实例

关闭单个时序数据库实例，选择需要关闭实例，点击操作项中关闭按钮，弹窗确认关闭。关闭实例会中断数据库服务，请谨慎操作。

时序数据库实例支持批量关闭多个实例，关闭操作步骤请参考重启时序数据库实例。

### 启动时序数据库实例
时序数据库实例支持批量启动多个实例，关闭操作步骤请参考重启时序数据库实例。

### 删除时序数据库实例
时序数据库实例支持批量关闭多个实例，关闭操作步骤请参考重启时序数据库实例。

单个和批量时序数据库实例操作
控制台支持单个和批量操作两种模式。

单个操作支持对选中的时序数据库实例进行操作；批量操作支持对于多个时序数据库实例进行共性的操作。

## 数据库管理

1、创建influxdb数据库，选择实例，点击实例名称或“详情”，到达实例详情概览页面，切换至“数据库管理”，点击创建数据库：

![image](/images/influxdb004.png)

![image](/images/influxdb005.png)

2、用户可以在控制台上修改或设置保留策略，时序数据库默认的保留策略是永久保留，用户可以根据实际需求设置保留时长。用户设置了保留时长后，对于保留时长以前的数据会自动清除，请谨慎操作。

![image](/images/influxdb006.png)

![image](/images/influxdb007.png)

## 配置升降级

用户可以选择不同CPU及内存规格，进行配置升降级操作，选中时序数据库实例，在右侧下拉列表中选择配置升降级操作。

![image](/images/influxdb2020040704.png)

具体计费说明请参考“购买和计费”文档。
