# lzw's change
pdf_viewer.js中加入background（每一处修改均带有background，可直接检索关键字）

pdf_viewer.js:6497 加入 ignoreDestinationZoom = true; 保证跳转时不会改变页面缩放比例

pdf_viewer.js:1543-1550 将endOfContent改为startOfContent
