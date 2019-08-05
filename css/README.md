css study

background-image:url() 
  --url中的路径不要加引号、加了引号也是可以跑的
  --默认背景图片在盒子的底部。

border-collapse:collapse
  --让边框重叠

margin--橙色
padding--浅蓝色

块级元素的居中
  --前提条件
    宽度确定
    设置margin:auto;

text-center
  --可以让盒子内的文本和行内元素、行内块元素居中对齐

嵌套盒子设置margin
  --如果子盒子设置margin、同时这个margin也是父元素的。
    --解决方法为父元素设置border:1px solid transparent;
    --父元素设置padding
    --父元素设置overflow:hidden;

继承的权重为0

float
   I、--脱离文档流、为了不让后面的标准流重叠在浮动元素的下面
      --会将浮动元素用一个标准流的盒子装起来、这样就不会让后面的标准流重叠到浮动元素的下面。
   II、浮动元素与父元素的关系
      --如果父元素设置了padding、border浮动元素是不会重叠在他之上与之紧挨着。
   III、浮动元素与平级元素的关系。
      --如果前面元素是标准流、当前元素是浮动的、则不会影响到前面的标准流元素。只会影响到后面的标准流清除浮动clear:noth
      --如果发现其中一个盒子中其中一个元素浮动了那么其他元素都得浮动、不然会影响这个盒子的布局。
      --浮动的元素是不占用位置的。