# jquery学习

## write less, do more

## 1 选择网页元素  
css选择器  
jquery特有表达式：$('a:first')  $('td:odd') 

## 2 方法函数化  
原始的js: window.onload  innerhtml onclick  
jquery: $() html() click()  

## 3 改变结果集  
强大的过滤器  
相邻元素查找  

## 4 链式操作  
```  
$(function(){
	$('div').find('h3').eq(2).css('background','red');
});  
```
## 5 取值与赋值合体  
html(); val(); attr(); width();

## 6 元素移形换位  
$('div').insertAfter($('p'));//div 放 p 后面  
$('div').appendTo($('p'));//div 放 p 后面  里面
$('p').after($('div'));//div 放 p 后面   
$('div').append($('p'));//p放div 里面 后面  

## 7 元素的创建  
$('div').append('<p>22222222</p>')';

```  
	var oSpan = $('<span>'); //创建元素
	oSpan.html('hello span');
	$('div').append(oSpan);  
```  
clone() 复制节点 	$('div').clone().append(oSpan);   

## 8 工具方法  
1 原型上的方法  
