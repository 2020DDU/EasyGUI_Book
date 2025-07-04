# 1 软件工作界面介绍

## 1.1 软件安装

XX软件是深圳XX公司自主创新开发的一款功能强大帮助客户快速进行GUI开发的调试软件。

> 环境：windows
>
> 软件下载：



根据提示选择安装目录，按照提示完成安装。



## 1.2 工作界面介绍

成功安装软件后，打开工程案例，工作界面如下：

<div align="left"><figure><img src="../.gitbook/assets/软件工作界面.jpg" alt=""><figcaption><p>软件工作界面</p></figcaption></figure></div>

{% stepper %}
{% step %}
**菜单栏**

工作区域包括文件/编辑/视图/布局/项目/生成/设置/帮助 等栏目
{% endstep %}

{% step %}
**视图工具栏**

包括：属性/工具箱/输出窗口/文件导航/画面结构/图片管理/变量管理/交互编辑器/动画编辑器/变量编辑器/结构体定义
{% endstep %}

{% step %}
**生成区域**

生成区域主要有生成、运行、停止等

生成：可以在输出窗口看到生成的结果，以及错误提示。

运行：对生成的文件，在模拟器中运行

停止：停止模拟器运行
{% endstep %}

{% step %}
**文件导航面板**

可以查看已经创建的窗体画面，加载图片，文本等列表。\
可以新建窗体，导入已有窗体文件，设置启动窗体，对窗体文件重命名、移除等操作。

<div align="left"><figure><img src="../.gitbook/assets/文件导航.gif" alt=""><figcaption><p>文件导航操作</p></figcaption></figure></div>
{% endstep %}

{% step %}
**画面结构面板**

打开的工程文件中，可以查看选中窗体下所有控件及树的层级结构，通过拖动树中对象的顺序或层级来改变其在Z轴顺序。操作如下图：

<div align="left"><figure><img src="../.gitbook/assets/画面结构窗体.gif" alt=""><figcaption><p>画面结构展示了当前窗体中所有控件的在树中的层级</p></figcaption></figure></div>


{% endstep %}

{% step %}
**画布编辑窗口**

UI界面的编辑区，在此区域拖放控件，即可完成控件的创建。画布区还可以完成对控件的编辑，删除等操作。如果你希望在画布上显示标尺，可以点击工具栏的<img src="../.gitbook/assets/image.png" alt="" data-size="line">启用该功能。

<figure><img src="../.gitbook/assets/画布编辑2.gif" alt=""><figcaption><p>画布编辑窗口可以对控件进行添加、编辑、删除等操作，操作区域可以显示标尺</p></figcaption></figure>
{% endstep %}

{% step %}
**工具箱（控件组）**

工具箱选项卡中包含所有已分类的可用控件列表。点击某类的控件组选项卡，将会打开该类控件包含的可用控件列表。

点击其中一个控件，可将其添加到当前画布上。

“工具箱”下有一个搜索栏，输入控件名称，可帮助查找出最佳匹配的控件。

<div align="left"><figure><img src="../.gitbook/assets/如何查找-工具箱控件.gif" alt="" width="563"><figcaption><p>工具箱中的控件组以及如何查找</p></figcaption></figure></div>

**控件选择**&#x20;

在画布中选中，也可以多选，按住CTRL 键的同时，单击多个控件。

**控件Z轴顺序调节**

控件的Z轴顺序可以通过“画面结构”选项卡中，拖动树中的顺序或层级来改变。

**内容裁剪控制**

在画布上，屏幕、自定义容器及其子类的边界之外的控件会被裁剪掉。

![](../.gitbook/assets/容器之外的控件.jpg)\



{% endstep %}

{% step %}
**输出窗口/图片管理/**<mark style="color:red;">**变量编辑**</mark>**/动画编辑/**<mark style="color:red;">**结构体编辑器**</mark>

* **输出窗口**\
  ​编译当前工程时，显示所有错误、警告。

<div align="left"><figure><img src="../.gitbook/assets/输出窗口.jpg" alt="" width="563"><figcaption><p>输出窗口编译当前工程文件时，显示所有错误、警告</p></figcaption></figure></div>



* **图片管理**

<div align="left"><figure><img src="../.gitbook/assets/图片管理窗口.jpg" alt="" width="375"><figcaption><p>图片管理窗口部分截图</p></figcaption></figure></div>

<mark style="color:red;">上图中1、2分别为：工程图片资源、软件自带图片库资源。</mark>

* **动画编辑器**

动画编辑器窗口可以对控件或画面进行渐变（fade animation）和移动（translate animation）两种动画操作。前者通过设置关键帧的alpha值来实现渐变；后者通过设置关键帧的XY值来实现位置的移动。

<div align="left"><figure><img src="../.gitbook/assets/动画编辑器1 (1).jpg" alt="" width="563"><figcaption><p>动画编辑器窗口</p></figcaption></figure></div>

**新建动画组**

首先在动画编辑器窗品使能动画后，选择<img src="../.gitbook/assets/image (10).png" alt="" data-size="line">新建动画组，当出现下图的弹出窗口后，再对动画组ID进行命名，选择要操作的对象（支持多选）。

<div align="left"><figure><img src="../.gitbook/assets/新建动画组 (1).jpg" alt=""><figcaption><p>弹出窗口</p></figcaption></figure></div>

如下图所示，操作对象出现在动画编辑窗口中，点击<img src="../.gitbook/assets/image (1).png" alt="" data-size="line">选择动画类型（支持多选）：fade animation、 translate animation。

<figure><img src="../.gitbook/assets/选择动画类型.jpg" alt=""><figcaption><p>动画编辑窗口和弹出窗口的动画类型选择</p></figcaption></figure>

**建立关键帧**

点击<img src="../.gitbook/assets/image (4).png" alt="" data-size="line">建立关键帧，并在属性窗口中对关键帧设置相关参数。

<figure><img src="../.gitbook/assets/动画编辑器-关键帧.jpg" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">具体请参考动画相关例程。</mark>



* **变量编辑器**


{% endstep %}

{% step %}
属性/交互编辑窗口

* **属性编辑器**

&#x20;画布右侧边栏允许查看和调整文件中对象的属性。每个控件都有相关预定义的属性，可以依具需求对这些属性进行设置，以实现自己需要的界面效果。相关的属性包括不限于控件尺寸、位置和颜色等位置属性，还包括控制其行为相关的外观属性，如是否可见、透明度等。<mark style="color:red;">还可以通过配置控件的控制属性，绑定相关变量，以达到其与外部硬件产生相关交互的目的。</mark>



* **交互编辑器**

交互编辑器是对控件、窗体或工程文件设置触发事件时要执行的动作。一个完整的交互由触发事件和动作组成。

> 触发事件是引起“交互”的条件，为了让“动作”发生，应用中需要发生的事件。
>
> 动作是触发事件发出时将发生的行为。

<div align="left"><figure><img src="../.gitbook/assets/交互编辑器事件-动作2.jpg" alt="" width="563"><figcaption><p>图1：全局交互逻辑中的事件和动作</p></figcaption></figure></div>

<div align="left"><figure><img src="../.gitbook/assets/交互编辑器事件-动作.jpg" alt="" width="563"><figcaption><p>图2：对象交互逻辑中的事件和动作</p></figcaption></figure></div>

图1：全局交互逻辑中的事件和动作；图2：对象交互逻辑中的事件和动作。

<div align="left"><figure><img src="../.gitbook/assets/两种交互逻辑切换.jpg" alt="" width="375"><figcaption><p>交互逻辑中的两种选择</p></figcaption></figure></div>

**添加、删除交互逻辑：**&#x5982;需要对某个对象作交互，首先选中对象，然后在交互编辑选项卡中点击左侧<img src="../.gitbook/assets/image (5).png" alt="" data-size="line">选择全局交互或对象交互，再点击“添加交互逻辑”，依次选中事件和动作。交互逻辑添加成功后，对对象的交互逻辑可以进行删除、编辑，具体操作如下所示：

<div align="left"><figure><img src="../.gitbook/assets/交互编辑-添加删除.gif" alt=""><figcaption><p>选中对象后添加、删除交互逻辑</p></figcaption></figure></div>
















{% endstep %}
{% endstepper %}

















































