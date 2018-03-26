#MACDOWN基础语法#
##标题##
###标题###
####标题####
#####标题#####
######标题######

## 列表
### 无序列表
+ 文本	
	+ 文本
+ 文本

## 有序列表
1. 文本
2. 文本2
3. 文本3	
	1.子列表

## 换行
+ tab键

## 引用
###引用单行句子
>呜呜啦呜呜啦呜呜啦	

###引用多行句子
>小猪佩奇身上纹	
>掌声送给社会人	

###引用代码
`hello word`
###引用多行代码
```<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
			<style type="text/css">
			
				div{
					height: 100px;
					width: 100px;
					background-color: #FF0000;
					display: inline-block;
					margin-left: 10px;
				}
			</style>
		
	</head>
	<body>
		<script type="text/javascript">
			for(var i = 1; i <= 7 ;i++){
				for(var j = 1;j <= i;j++){
					document.write("<div></div>")
				}
				document.write("<br />")
			}
		</script>
	</body>
</html>
```
###分割线
***
___
---
##强调
###斜体
*斜体*
###加粗
**加粗**
##插入链接
[百度](http://www.baidu.com "百度")
##插入图片
![哎呀呀](/Users/dllo/Desktop/WechatIMG57.jpeg)
##表格
<table  border="1">
			<tr>
				<td>123</td>
				<td>456</td>
				<td>789</td>
			</tr>
			<tr>
				<td>123</td>
				<td>456</td>
				<td>789</td>
			</tr>
			
		</table>
00|第一列|第二列|第三列
---|:---:|:---|---:
第一行|居中|左对齐|右对齐
第二行|111111111111|22222222|333333333
第三行|1|2|3
