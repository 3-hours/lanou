review 
1. DOM 文档对象模型
	元素 新增/删除/插入/替换/复制 cloneNode(bol)
	属性 新增ele.setAttribute(name, value)/获取ele.getAttribute(name)/移除ele.removeAttribute(name)
	文本 innerHTML/innerText/value

2. JSON 轻量级的数据交换格式
   XML 
   XHTML
 	{ 
 		"name": "Shafee",
 		"age": 20,
 		"schools": [{}, {}, {}]
 	}


效果： 碰壁反弹/瀑布流/懒加载/预加载


瀑布流
页面的可视区宽高
document.documentElement.clientWidth/document.documentElement.clientHeight


懒加载，资源[img]需要使用到才请求加载，减少首屏加载时间

预加载，预先将消耗网络带宽的资源[img]请求回来，加载完成之后才进一步操作