动态rem方案
1浏览器禁止980px的缩放
2设置`html {font-size: 页面宽度/10px}`
3 10rem == 页面宽度
4 所有单位都用rem == 所有长度都以页面宽度为基准
5 页面可以兼容任何手机屏幕

因像素对齐导致的1px问题
retina屏幕下，
css 1px = 物理2px

副作用
所有div都变为原来的50%
解决方法
先缩放50%，在放大两倍
`border: 1px solid red`只进行了缩放，而没有进行放大，因此由css的1px(物理2px)缩小为css的0.5px(物理1px)


