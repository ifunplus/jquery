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

# 4 链式操作  
```  
$(function(){
	$('div').find('h3').eq(2).css('background','red');
});  
```
