# React学习笔记 

## React元素渲染
* ReactDOM.render(element, Ele) ==> 将element渲染到Ele中

## 定时器
* setInterval(func, gap) ==> 每隔gap时间执行一次func, 其中gap是以毫秒为单位
* {new Date().toLocaleTimeString()} => 获取当前时间

## 函数 ==> 不需要显示的声明返回值, 直接用return返回即可
* func(params) {   
	return ....
}   
注意：函数名需要大写, 因为小写开头的组件被认为是原生的组件, 例如div.

## 基于ReactComponet的ES6类
class Love extends React.Component {   
	render(){   
		return (   
			<div>   
				<h2>I love you!</h2>   
				<h2>{this.props.Name}</h2>   
			</div>   
		);   
	}   
}   
* extends ==> 继承自什么类
* render() ==> 渲染不可缺少
* {this.props.Name} ==> 用大括号括起来表示引用变量或函数

## JSX


