# 切换进程视图

在不同视图之间切换：

在调试期间，新点击了：

* `Debug Memory Graph`
* `Debug View Hierarchy`

后，回不去调试的Thread了

后来发现了，是点击：

`View process in different ways`

![view_process_diff_ways](../assets/img/view_process_diff_ways.jpg)

即可看到几种方式：

* 当前的是：`View UI Hierarchy`
  * ![view_ui_hierarchy](../assets/img/view_ui_hierarchy.jpg)

切换到：

* `View Process by Thread`
  * ![change_to_view_process](../assets/img/change_to_view_process.jpg)

就是Debug默认的，常见的形式了：

以线程方式查看进程，其中能看到函数调用堆栈的内容：

![debug_view_threads](../assets/img/debug_view_threads.jpg)
