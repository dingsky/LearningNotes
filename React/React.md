# Reactѧϰ�ʼ� 

## ReactԪ����Ⱦ
* ReactDOM.render(element, Ele) ==> ��element��Ⱦ��Ele��

## ��ʱ��
* setInterval(func, gap) ==> ÿ��gapʱ��ִ��һ��func, ����gap���Ժ���Ϊ��λ
* {new Date().toLocaleTimeString()} => ��ȡ��ǰʱ��

## ���� ==> ����Ҫ��ʾ����������ֵ, ֱ����return���ؼ���
* func(params) {   
	return ....
}   
ע�⣺��������Ҫ��д, ��ΪСд��ͷ���������Ϊ��ԭ�������, ����div.

## ����ReactComponet��ES6��
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
* extends ==> �̳���ʲô��
* render() ==> ��Ⱦ����ȱ��
* {this.props.Name} ==> �ô�������������ʾ���ñ�������

## JSX


