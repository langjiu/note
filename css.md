### user-select 属性

user-select 属性阻止用户突出显示或选择网页上的文本复制。

```css
div {
  user-select: none;
}
```

### object-fit 属性

object-fit 属性 允许我们设置成定义应如何调整替换元素的内容（img, video 等）以适应其容器。

**语法**

```css
object-fit: fill|contain|cover|scale-down|none|initial|inherit;
```

**属性值**
| 值 | 描述 |
| -- | -- |
|fill|默认，不保证保持原有的比例，内容拉伸填充整个内容容器。|
|contain|保持原有尺寸比例。内容被缩放。|
|cover|保持原有尺寸比例。但部分内容可能被剪切。|
|none|保留原有元素内容的长度和宽度，也就是说内容不会被重置。|
|scale-down| 保持原有尺寸比例。内容的尺寸与 none 或 contain 中的一个相同，取决于它们两个之间谁得到的对象尺寸会更小一些。|

**语法示例**

```css
.fill {object-fit: fill;}
.contain {object-fit: contain;}
.cover {object-fit: cover;}
.scale-down {object-fit: scale-down;}
.none {object-fit: none;}
```

### backface-visibility 属性

backface-visibility 属性定义当元素背面向屏幕时是否可见。
如果在旋转元素不希望看到其背面时，该属性很有用。

**语法**

```css
backface-visibility: visible|hidden;
```

**属性值**
| 值 | 描述 |
| -- | -- |
|visible|背面是可见的。|
|hidden|背面是不可见的。|

**语法示例**

```css
div
{
    backface-visibility:hidden;
    -webkit-backface-visibility:hidden; /* Chrome 、Safari */
    -moz-backface-visibility:hidden; /* Firefox */
    -ms-backface-visibility:hidden; /* Internet Explorer */
}
```

### mix-blend-mode 属性

mix-blend-mode 属性描述了元素的内容应该与元素的直系父元素的内容和元素的背景如何混合。
**语法**

```css
mix-blend-mod:  <blend-mode> // <blend-mode> 的值可以是以下几个：
mix-blend-mode: normal;
mix-blend-mode: multiply;
mix-blend-mode: screen;
mix-blend-mode: overlay;
mix-blend-mode: darken;
mix-blend-mode: lighten;
mix-blend-mode: color-dodge
mix-blend-mode: color-burn;
mix-blend-mode: hard-light;
mix-blend-mode: soft-light;
mix-blend-mode: difference;
mix-blend-mode: exclusion;
mix-blend-mode: hue;
mix-blend-mode: saturation;
mix-blend-mode: color;
mix-blend-mode: luminosity;
```

### background-blend-mode 属性

background-blend-mode 属性定义了背景层的混合模式（图片与颜色）。

**语法**

```css
background-blend-mode: normal|multiply|screen|overlay|darken|lighten|color-dodge|saturation|color|luminosity;
```

**属性值**
| 值 | 描述 |
| -- | -- |
|normal|默认值。设置正常的混合模式。|
|multiply|正片叠底模式。|
|screen|滤色模式。|
|overlay|叠加模式。|
|darken|变暗模式。|
|lighten|变亮模式。|
|color-dodge|颜色减淡模式。|
|saturation|饱和度模式。|
|color| 颜色模式。|
|luminosity|亮度模式。|

**语法示例**

```css
div { 
  width: 290px;
  height: 69px;
  background-size: 290px 69px;
  background-repeat:no-repeat;
  background-image: linear-gradient(to right, green 0%,white 100%), url('logo.png');
  background-blend-mode: color-dodge;
}
```

**效果图**
![image.png](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/6512fa615c4247ce9e117771d1e6ddc9~tplv-k3u1fbpfcp-watermark.image?)

### place-items 属性

### resize 属性

指定一个 div 元素，允许用户调整大小：
