**1. 数字图像格式**

[数字图像](https://zh.wikipedia.org/wiki/%E6%95%B0%E5%AD%97%E5%9B%BE%E5%83%8F)
目前比较流行的图像格式包括光栅图像格式BMP、GIF、JPEG、PNG等，以及矢量图像格式WMF、SVG等。大多数浏览器都支持GIF、JPG以及PNG图像的直接显示。SVG格式作为W3C的标准格式在网络上的应用越来越广。

光栅图像指的是图像由点阵组成.就是把图像用一个光栅分成若干个小块或是点，然后识别存贮。光栅图像文件里包含的是点阵的坐标与颜色值。
相对的是失量图像，失量图不是直接由点阵构成而是由**描述**组成，重现时就是对描述进行解析复现。失量图像是由命令加参数组成。
jpg 就是光栅图像格式。

比如: 文件的信息在(1,1)这个坐标的像素是红色2。那么假设表示为112，然后由看图软件重绘出来。
失量图像文件里是一些指导看图软件如何重绘图像。比如:文件的信息在(1,1)这个坐标是红色2，假设表示为point(1,1) color(2)
表示只是假设简化的，真正的要复杂得多。

**2. pxm 格式**

pxm 是 Mac OS X 的图像编辑程序 Pixelmator 专有的光栅图像格式，包含多个图层、图层蒙版、色彩校正设置和图像元数据。是一种无损格式保存时不会丢失质量的文件。

涉及到图层的数据必须保存为 PixelMator 文件格式(*.pxm)，最终效果图可导出普通文件格式。
若保存为 pxm 文稿格式，重新打开时，可针对图层对象再编辑；若保存为普通文件格式，再次打开时将无图层信息。

[Pixelmator | Help | Tutorials](http://www.pixelmator.com/tutorials/)

[Pixelmator Tutorial - Layers introduction lesson](https://www.youtube.com/watch?v=dynt-eOSvlA)

[Pixelmator Tutorials – Layers in Image Editing](http://www.pixelmator.com/tutorials/image-editing-basics/layers-in-image-editing/)

[Pixelmator Tutorials – Layer Groups](http://www.pixelmator.com/tutorials/image-compositions/layer-groups/)

[How to Work With Layers in Pixelmator](https://www.youtube.com/watch?v=ZXLck8ChdRQ)

## Layers
[Layers in Image Editing](http://www.pixelmator.com/tutorials/basics/layers-in-image-editing/)

Layers are the basis for image editing. Gorgeous image compositions are created by combining several pictures into one final image. These pictures, the elements of the whole image, are called **_layers_**.

To understand the basics of layers within a composition, think of them as **stackable** elements, each of which holds part of your image. The higher a layer is in the stacking order, the more “in front” it will be. _Transparent_ areas on a layer allow you to see the layers _beneath_ it, and the final appearance of the picture depends on the layers’ **order**.

![layers-stack](http://tutorials-cdn.pixelmator.com/layers/1.png)

The place where you view and arrange the order of layers is called the **_Layers palette_**. The Layers palette shows individual layers and their content. Every time you open or place images, add text, or draw a shape, the **new layer** is created in the Layers palette. In Pixelmator, you can use the Layers palette to select, create new, remove, merge, show, and hide layers; arrange stacks of layers; create clipping masks; link layers; and preserve layers’ transparency.

![layers-demo](http://tutorials-cdn.pixelmator.com/layers/2.png)

With layers, you can do more than just arrange elements in your composition: You can edit each of them **individually** without affecting the rest of your image. Click to select the layer in the Layer palette, and then freely edit, move, resize, erase, paint, adjust colors, or do anything else to satisfy your artistic vision. By using layers, you can even quickly compare several effects to determine which one is the best for the image by hiding and unhiding layers.

The more you play with layers, the more you will discover creative ways to achieve your desired results. Also, because layers help you to edit images non-destructively, you should never be afraid of experimenting. Learn more about layers in practice by following any of the Pixelmator tutorials.

在当前画布（Canvas）右键 - Auto Select，将会随鼠标点击自动选择图层。

### Show
[View|Show Layers]：⌘2

Layer palette

### New
新建图层：⇧⌘N

### Duplicate
复制当前图层

### Hide
隐藏图层
可在 Layers 中勾选可以隐藏或显示。

### Preserve Transparency
保留透明度

### Layer Mask
Lock/Unlock Layer：锁定/解锁图层
Link/Unlink Layer：？？？
Select Linked Layers：
Group/Ungroup Layers：
Merge All Layers：

[Pixelmator Layers and Masks](http://macmost.com/pixelmator-layers-and-masks.html)  
[Adding Layer and Clipping Masks](https://photofocus.com/2014/12/28/learning-pixelmator-adding-layer-and-clipping-masks/)  
[**Playing with Masks in Pixelmator**](http://abduzeedo.com/playing-masks-pixelmator)  

[Pixelmator: Creating a Clipping Mask](http://digitalapplejuice.com/pixelmator-basics-creating-a-clipping-mask/)  
[How To Use Clipping Masks (And Bring Godzilla To Life)](http://www.pixelmatortemplates.com/pixelmator-tip-27-how-to-use-clipping-masks-and-bring-godzilla-to-life/)  
[How To Use Text And Clipping Masks To Make Beautiful Posters](http://www.pixelmatortemplates.com/pixelmator-tip-51-how-to-use-text-and-clipping-masks-to-make-beautiful-posters/)

### Hierarchy
Bring to Front
Bring Forward
Send Backward
Send to Back
