# 理财网站响应式设计

## 预览
[Demo](https://angelpray.github.io/project/RWD/rwd_imooc/index.html)

## 学习总结 :orange_book:

### 技术要点
1. 采用了HTML5标准的响应式结构，比如使用`mete`提供了`name、content、http-equiv`属性,相关的更语义化的元素。

2. 使用了传统的float布局，而没用使用flex布局。

3. 使用了工具样式，也就是类似Bootstrap中的`.pull-right`的样式（看到类名就能知道他的样式会怎么样），使用这种样式的好处在于非常快速方便让一个元素进行修饰，可重用。

4. 使用了基于`JQ`的carousel，[Owl.carousel()](https://github.com/OwlCarousel2/OwlCarousel2).非常强大的carousel实现，支持触摸移动，还有其他选项可以对carousel进行自定义。类似的还有slick,lory,flickity.

5. 使用了CSS3的一些属性，比如CSS3的选择器，盒阴影，rgba等非常实用的东西。

6. 使用了[normalize.css](https://necolas.github.io/normalize.css/)，这种可以让网页在大多浏览器中看上去不会相差太多的开源样式表，相比reset.css是一种进步。

7. 学会了响应式图片的实现原理，比如可以使用JS或者服务器实现，但在前端我们可以使用`picture + media媒体查询`来实现。

