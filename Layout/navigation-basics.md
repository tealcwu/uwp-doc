**[回到设计首页](../README.md)**

阅读时长：5分钟

## 本文内容

- [正确导航的原理](#正确导航的原理)
- [一般性建议](#一般性建议)
- [使用正确的结构](#使用正确的结构)
- [使用正确的控件](#使用正确的控件)

---

如果你把一个App看作页面的集合，导航就是在不同页面之间以及某一页面内的切换。用户的体验就从这里开始，通过这种方式用户可以找到他感兴趣的内容和功能。这一点很重要但也不是轻而易举就能做好的。

它之所以困难是因为作为应用的设计者，我们有太多的选择。我们可以要求用户按照顺序访问一系列页面，或者我们可以提供一个菜单这样用户可以直接访问任何页面，我们也可以把所有内容放在一个页面而通过筛选来让用户选择内容。

没有一个通用的导航设计能适用于任何应用，但有一些原理和指导能帮助你做出正确的设计。

![Navigation diagram](https://docs.microsoft.com/zh-cn/windows/uwp/design/basics/images/navigation_diagram.png "Diagram of an app's navigation")

## 正确导航的原理

在开始之前让我们看看好的导航设计是什么样的：

- 一致：符合用户的期望
- 简单：没有多余的功能
- 明确：提供清晰的路径和选项

### 一致
导航应该符合用户的期望。在设计中使用用户熟知的标准控件，并按照标准设计图标、位置和样式，能使用户更直观的使用导航。

![](https://docs.microsoft.com/zh-cn/windows/uwp/design/basics/images/nav/nav-component-layout.png)

### 简单
较少的导航选项能使用户更容易做出选择。使用户更容易访问重要内容，并隐藏不太重要的选项，能帮助用户更快地找到他们所需要的。

![](https://docs.microsoft.com/zh-cn/windows/uwp/design/basics/images/nav/nav-simple-menus.png)

*左边的菜单项比较少，这样用户理解和使用起来更容易*

### 明确
明确的路径符合用户的逻辑。导航的设置要显眼，页面间的联系要清晰，这样用户才不会被弄糊涂。

![](https://docs.microsoft.com/zh-cn/windows/uwp/design/basics/images/nav/nav-pages.png)

## 一般性建议
现在，我们从以上提到的设计原理 **一致、简单、明确** 可以得到一些一般性建议。

1. 为用户着想。
2. 避免导航层次过深。
3. 避免“跳杆”。

## 使用正确的结构


```csharp
private void main()
{
	Console.WriteLine();
}
```

<a href="">asdf</a>

## 使用正确的控件