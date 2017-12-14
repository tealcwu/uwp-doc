# 适应性设计中的屏幕大小和断点

建议阅读时长：2分钟

Windows 10生态圈中的设备类型和屏幕尺寸很多，开发者不可能针对每一种都单独优化界面设计。相反，我们建议你只为只个关键的宽度类型（也称为“断点”）进行设计：小（640px或更小），中（640px~1007px)，大（1008px及更大）

*注意：当会对断点设计时，注意你能用于设计的屏幕空间。当应用在全屏运行时，应用窗口和屏幕尺寸一样，否则是要小于屏幕尺寸的。*

# 断点

下面这个表格描述了不同的尺寸类型并提供了适用于它们的断点。

![rspd breakpoints](https://docs.microsoft.com/zh-cn/windows/uwp/design/layout/images/rsp-design/rspd-breakpoints.png)


<table>
    <tbody>
        <tr>
            <th>尺寸类型</th>
            <th>小</th>
            <th>中</th>
            <th>大</th>
        </tr>
        <tr>
            <td>有效像素下窗口宽度断点</td>
            <td><640px</td>
            <td>640px~1007px</td>
            <td>>1008px</td>
        </tr>
        <tr>
            <td>典型屏幕尺寸（对角线）</td>
            <td>4''~6''</td>
            <td>7''~ 12'', 电视</td>
            <td>>13''</td>
        </tr>
        <tr>
            <td>典型设备</td>
            <td>手机</td>
            <td>平板，电视</td>
            <td>PC，笔记本，Surface Hubs</td>
        </tr>
        <tr>
            <td>有效像素下普通窗口尺寸</td>
            <td>320x569, 360x640, 480x854</td>
            <td>960x540</td>
            <td>1024x640, 1366x768, 1920x1080</td>
        </tr>
        <tr>
            <td>建议</td>
            <td>
                <ul>
                    <li>窗口的外边距设置为12px</li>
                    <li>将App bar放在底部</li>
                    <li>每次只用一列</li>
                    <li>用图标代表搜索（不要显示搜索框）</li>
                    <li>折叠导航面板以节省空间</li>
                    <li>在主从模式中使用折叠模式</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>窗口的外边距设置为24px</li>
                    <li>将App bar放在顶部</li>
                    <li>最多两列</li>
                    <li>显示搜索框</li>
                    <li>将导航面板设置为紧凑模式</li>
                    <li>考虑应用在电视上的体验</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>窗口的外边距设置为24px</li>
                    <li>将App bar放在顶部</li>
                    <li>最多三列</li>
                    <li>显示搜索框</li>
                    <li>将导航面板设置为展开模式</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>


通过手机上的Continuum功能，用户可以把Windows 10移动设备连接到一个显示器上，鼠标和键盘上以使它可以像笔记本一样工作。 请在为特定断点设计时留意这个功能 - 移动手机并不总是处于小的屏幕类型中。

# 有效像素和缩放比率

缩放比率决定了文字和界面元素显示在屏幕上的尺寸。缩放比率越大会增加系统用于渲染特定界面元素的像素数量。 Windows会根据屏幕的DPI自动选择一个合适的缩放比率和查看距离。用户也可以通过设置 > 显示 > 缩放与布局 更改默认设置。