# project1
ʯ��Ԫ 19302010036  
*** 
github��ַ��github.com/hddjp  
git page:  https://hddjp.github.io/project1/
***
###pj������  
�������ܾ���ʵ�֡���ҳɫ��ʹ�úڡ��ס���ɫ��ɫ����Լ���ˣ�һĿ��Ȼ  
������ɫΪ��ɫ��������ɫ����ʾ���顣�ܺܺõر�������  
***
��ҳ��Ϊheader ͷͼ main footer�������а�ť��  
�����˵�ͨ���Ѷ�����ӷ���<div>�У���hoverʵ����������  
ͼƬչʾ������<table>ʵ�֣�֮�����������ͼƬ��������������ݶ���<table>
�̶�λ�ð�ťͨ��position:fixedʵ��  
![��ҳ](img/overview/index.png)  
***
����ҳ���header����ҳ����һ���ģ���ͬҳ���ڲ�ͬ��ǩ�����»���    
���ҳ��aside������ߣ���<ul><li>�ֳ�����   
main������scriptʵ�ֶ���ѡ����Ч��  
ҳ��Ϊ���<a>  
![���ҳ](img/overview/browser.png)  
***
searchҳ���main����������<h1>��һ��������<div>����ʾͼƬ�����������<table>  
ҳ�롢ҳ�ŵȶ���֮ǰ��ͬ  
![����ҳ](img/overview/search.png)  
***
uploadҳ����һ��һ�����е�table�������ͼƬ�ϴ����ұ�����������  
ͼƬ�ϴ�ʹ��<input type="file">����Ϊ���Ԫ���޷��趨��ʽ�����Խ�����Ϊ͸����ʹ��<button>��֮�ص�  
��scriptʵ��ͼƬ�ϴ����ϴ�ǰ������ʾ��δ�ϴ�����ͼƬ���ϴ���ı�ͼƬclass���Ըı���ʽ��  
���������ü���<p>���У��������ֶ��롣��Ϊinput�����������������textarea������ͼƬ����  
�����<input type="submit">��ť�ύ  
![�ϴ�](img/overview/upload.png)  
***
�ҵ���Ƭ����������ҳ���ơ�  
��ÿһ��td���������button��ɾ�����޸ģ�������float:right  
![�ҵ���Ƭ](img/overview/mypic.png)  
***
�ղؼв���Ҳ��ͬ   
����������һ��<td>��Ϊȡ���ղذ�ť  
![�ҵ��ղ�](img/overview/favorates.png)  
***
��¼���������ˣ�<h1>֮����<p>��ÿ��<p>�ڶ���ͼ��+�����  
����ṩ��¼��ť��ע������    
![��¼](img/overview/signin.png)  
***
ע����沼�����¼��ͬ  
![ע��](img/overview/register.png)  
***
ͼƬ����ҳ�б��⣬<table>һ�����У����ͼƬ�ұ���Ϣ�����·���ͼƬ������������һ���ַŴ�  
�ṩ�ղذ�ť  
�������¾���<hr>�ָ���  
![����](img/overview/details.png)  
###Bonus ������
bonus�����
ͼƬ�ü�ʹ������css��ʽ��
	`img.pic{
    width: 100%;
    height: 100%;
    object-fit: cover;
}

div.pic{
    height: 150px;
    width: 150px;
}`
����imgΪ ͼƬ��divΪ����ͼƬ�Ŀ飬�����Ϊpic  
object-fit :cover �ܹ��ñ������֣���֤�滻���ݳߴ���������ߴ磬��͸�������һ��������һ�� 
����ΪͼƬ�Ա�  
![ԭͼ](img/normal/medium/222222.jpg) 
![�ü���](img/overview/pic.png)
***
��Ӧʽ����ʹ�����´���ʵ�֣�  
	`<meta name="viewport" content="width=device-width,initial-scale=1.0">`
Ȼ��Ϳ��Ը��������Ŀ�ȴ�С����css��ʽ���Ĳ��á�  
������ҳ�������ģ�
	`<link rel="stylesheet" href="reset.css" type="text/css">
        <link rel="stylesheet" href="src/css/index-common.css" type="text/css">
        <link media="(max-width:1175px)" rel="stylesheet" href="src/css/index-middle.css" type="text/css">
        <link media="(max-width:1020px)" rel="stylesheet" href="src/css/index-small.css" type="text/css">       
        <link media="(max-width:600px)" rel="stylesheet" href="src/css/index-mobile.css" type="text/css">`
�����ĸ���ʽ����common ��middle ��small �� mobile  
һ��ʼ�̶�ʹ��common�����󡣵�������С������middle����������С����small ��600pxΪʶ���ƶ��˵ĳߴ磬С��600pxʹ���ƶ�����ʽ  
����ҳ��Ҳ������ͬ�����Ƿ����ĸ���ʽ������ע�����¼ֻ��Ҫcommon��mobile������ʽ������  
һ��ʼ������С����Ϊmain��margin-left��width�̶������ұ������ݲ��ֱ��ڸǣ������ڽӽ�mainʱ����Ϊmiddle��ʽ��main��floatΪright���������Ҳ࣬����С���ھ�����С��߾��롣����С����߾���Ҳ��ʣ�޼�����Ϊsmall������ҳ�汻main��ռ�ݡ���ʱ���ֽ�������С����ڸ�main�Ĳ������ݣ���Щ�򲻻ᡣ  
����С��mobile��ʽ�����������п�ȵ�λ��һ�㽫px�ĳ�%�����ڲ�ͬ�ֻ��϶�λ������ͼƬ�밴ť������Ҳ�������Ӧ����С  
���¾�����
![һ��ʼ](img/overview/common.png)
![��С](img/overview/middle.png)
![�ٱ�С](img/overview/small.png)
![�ƶ���](img/overview/mobile.png)
###����pj1�Ϳγ̵�����뽨��
���鿼�Լ�һЩ��A��һ�㣬���F~ 
