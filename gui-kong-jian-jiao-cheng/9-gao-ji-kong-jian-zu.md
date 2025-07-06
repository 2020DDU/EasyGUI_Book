# 9 高级控件组

<div align="left"><figure><img src="../.gitbook/assets/高级控件.jpg" alt="" width="375"><figcaption><p>工具箱中的高级控件组</p></figcaption></figure></div>

## 9.1 模拟时钟

模拟时钟控件，可以通过绑定主机系统，显示时间的模拟时钟，时钟使用背景图像作为钟面，时针、分针、秒针都使用图像，围绕一个可配置的中心旋转。

<div align="left"><figure><img src="../.gitbook/assets/模拟时钟.gif" alt="" width="300"><figcaption><p>模拟器中运行的模拟时钟效果</p></figcaption></figure></div>

### 属性

<table><thead><tr><th width="115.74661254882812">属性组</th><th width="655.0386047363281">属性说明</th></tr></thead><tbody><tr><td>名称</td><td>控件名称，可以修改，具有唯一性</td></tr><tr><td>位置</td><td>锁定 锁定/解锁对象的大小和位置</td></tr><tr><td></td><td>X/Y 指定控件坐标（坐标原点为画布左上角）</td></tr><tr><td></td><td>宽度/高度 对像的宽度/高度值（单位：像素）此处由图片大小决定，不可以更改</td></tr><tr><td>外观</td><td>显示  设置显示或隐藏本对象，True/False 或绑定变量</td></tr><tr><td></td><td>不透明度（0-100），0完全透明，100完全不透明 可以绑定变量</td></tr><tr><td>控制</td><td>设置时间源  设置时钟绑定到时间类型的变量（System:Time)</td></tr><tr><td></td><td>时针线性随动  设置为NO时，时针将在分钟走完一圈后才移动一格</td></tr><tr><td></td><td>分针线性随动  设置为NO时，分针将在秒钟走完一圈后才移动一格</td></tr><tr><td>图片</td><td>背景图  选择模拟时钟的背景图片</td></tr><tr><td></td><td>中心xy  设置背景中心X坐标Y坐标</td></tr><tr><td></td><td>时针图 选择时针图</td></tr><tr><td></td><td>时针旋转中心X/Y 设置时针图旋转中心的XY坐标</td></tr><tr><td></td><td>分针图 选择分针图</td></tr><tr><td></td><td>分针旋转中心X/Y 设置分针图旋转中心的XY坐标</td></tr><tr><td></td><td>秒针图 选择秒针图</td></tr><tr><td></td><td>秒针旋转中心X/Y 设置秒针图旋转中心的XY坐标</td></tr></tbody></table>





## 9.2 二维码

二维码是一种能绘制二维码的控件，其中提供了要编码的内容，可以指定前景和背景颜色。

<div align="left"><figure><img src="../.gitbook/assets/模拟器中运行的QR控件.jpg" alt="" width="290"><figcaption><p>模拟器中运行的QR控件</p></figcaption></figure></div>

### 属性

<table><thead><tr><th width="112.942138671875">属性组</th><th>属性说明</th></tr></thead><tbody><tr><td>名称</td><td>控件名称，可以修改，具有唯一性</td></tr><tr><td>位置</td><td>锁定 锁定/解锁对象的大小和位置</td></tr><tr><td></td><td>X/Y 指定控件坐标（坐标原点为画布左上角）</td></tr><tr><td></td><td>宽度/高度 对像的宽度/高度值（单位：像素）</td></tr><tr><td>外观</td><td>显示 设置显示或隐藏本对象</td></tr><tr><td></td><td>不透明度（0-100），0完全透明，100完全不透明 可以绑定变量</td></tr><tr><td></td><td>前景颜色 设置二维码的颜色</td></tr><tr><td></td><td>背景颜色 设置二维码的背景颜色</td></tr><tr><td></td><td>包边厚度 设置二维码四周留白区域厚度</td></tr><tr><td>数据</td><td>文本 设置需要生成二维码的文本数据 也可以绑定变量</td></tr><tr><td></td><td>纠错等级 设置需要二维码数据的纠错级别</td></tr></tbody></table>
