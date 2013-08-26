rDialog
=======

> 一个基于jQuery的轻量级dialog

使用说明
=======

<pre>
$.dialog({
	content: '您是否同意当前模式？',		// 内容
	title: '会员注册',					// 标题
	width: 500,							// 宽度
	height: 200,						// 高度
	ok: function() {					// ok按钮回调函数
		alert('确定按钮回调函数');
	},
	cancel: function() {				// cancel按钮回调函数
		alert('取消按钮回调函数');
	},
	okText: '确定',						// ok按钮文字
	cancelText: '取消',					// cancel按钮文字
	time: 3000,							// 自动关闭时间(毫秒)
	lock: true,							// 是否锁屏
	zIndex: 9999						// z-index值
});
</pre>
