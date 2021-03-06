# UI/截图

> 贡献者：[@ImPerat0R\_](https://github.com/tssujt)、[@ThinkingChen](https://github.com/cdmikechen)

通过 Airflow UI，您可以轻松监控 data pipeline（管道）并对其进行故障排除。如下是一些特性的简单预览和一些您可以在 Airflow 的 UI 中找到的可视化效果。

## DAGs 查看

您环境中的 DAG 列表，以及一系列进入常用页面的快捷方式。您可以一目了然地查看成功、失败及当前正在运行的任务数量。

* * *

![https://airflow.apache.org/_images/dags.png](img/31a64f6b60a7f97f88c4b557992d0f14.jpg)

* * *

## 树视图

跨越时间的 DAG 的树表示。如果 pipeline（管道）延迟了，您可以很快地看到哪里出现了错误的步骤并且辨别出堵塞的进程。

* * *

![https://airflow.apache.org/_images/tree.png](img/ad4ba22a6a3d5668fc19e0461f82e192.jpg)

* * *

## 图表视图

图形视图可能是最全面的一种表现形式了。它可以可视化您的 DAG 依赖以及某个运行实例的当前状态。

* * *

![https://airflow.apache.org/_images/graph.png](img/bc05701b0ed4f5347e26c06452e8fd76.jpg)

* * *

## 变量视图

变量视图允许您列出、创建、编辑或删除作业期间使用的变量的键值对。如果密钥默认包含（'password'，'secret'，'passwd'，'authorization'，'api_key'，'apikey'，'access_token'）中的任何单词，则隐藏变量的值，但可以配置以明文显示。

* * *

![https://airflow.apache.org/_images/variable_hidden.png](img/9bf73cf3f89f830e70f800145ab51b10.jpg)

* * *

## 甘特图

甘特图可让您分析任务持续时间和重叠情况。您可以快速识别系统瓶颈和哪些特定 DAG 在运行中花费了大量的时间。

* * *

![https://airflow.apache.org/_images/gantt.png](img/cfaa010349b1e40164cabb36c3b7dc1b.jpg)

* * *

## 任务持续时间

过去 N 次运行的不同任务的持续时间。通过此视图，您可以查找异常值并快速了解 DAG 在多次运行中花费的时间。

* * *

![https://airflow.apache.org/_images/duration.png](img/f0781c3598679db6605d7dfffc65c6a9.jpg)

* * *

## 代码视图

透明就是一切。虽然您的 pipeline（管道）代码在源代码管理中，但这是一种快速获取 DAG 代码并提供更多上下文的方法。

* * *

![https://airflow.apache.org/_images/code.png](img/b732d0bdc5c1a35f3ef34cc2d14b5199.jpg)

* * *

## 任务实例上下文菜单

从上面的页面（树视图，图形视图，甘特图......）中，始终可以单击任务实例，并进入此丰富的上下文菜单，该菜单可以将您带到更详细的元数据并执行某些操作。

* * *

![https://airflow.apache.org/_images/context.png](img/c6288f9767ec25b7660ae86679773f69.jpg)
