# 数据分析

> 贡献者：[@ImPerat0R\_](https://github.com/tssujt)

使用数据生产效率的一部分是拥有正确的武器来分析您正在使用的数据。Airflow 提供了一个简单的查询界面来编写 SQL 并快速获得结果，以及一个图表应用程序，可以让您可视化数据。

## 临时查询

adhoc 查询 UI 允许与 Airflow 中注册的数据库连接进行简单的 SQL 交互。

![https://airflow.apache.org/_images/adhoc.png](img/bfbf60f9689630d6aa1f46aeab1e6cf0.jpg)

## 图表

基于 flask-admin 和 highcharts 构建的简单 UI 允许轻松构建数据可视化和图表。使用标签，SQL，图表类型填写表单，从环境的连接中选择源数据库，选择其他一些选项，然后保存以供以后使用。

在编写 Airflow 管道，参数化查询和直接在 URL 中修改参数时，您甚至可以使用相同的模板和宏。

这些图表是基本的，但它们很容易创建，修改和共享。

### 图表截图

![https://airflow.apache.org/_images/chart.png](img/a7247daabfaa0606cbb0d05e511194db.jpg)

* * *

### 图表表格截图

![https://airflow.apache.org/_images/chart_form.png](img/a40de0ada10bc0250de4b6c082cb7660.jpg)
