#lib.gesture

## 最新版本

**1.0rc1**

## 依赖

无

## 如何使用

引入js文件后，任何DOM结点都可以监听手势事件。例如：


	document.querySelector('.viewport').addEventListener('pan', function(){
		console.log('getsture pan');
	}, false);
	

手势事件有：

- tap 轻击
- doubletap 快速双击
- panstart 开始平移
- horizontalpanstart 开始水平平移
- verticalpanstart 开始垂直平移
- pan 平移中
- horizontalpan 水平平移中
- verticalpan 垂直平移中
- panend 平移结束
- flick 轻弹
- horizontalflick 水平轻弹
- verticalflick 垂直轻弹
- press 长按
- pressend 长按结束
