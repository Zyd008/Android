# notepad
1.	增加时间戳

在NotePadProvider这个类的insert方法中
变量now为获取到的1970年到现在的秒数

为便于观看需要将其转化为yyyy.MM.dd HH:mm:ss格式

Datatime代指当时时间

图片1


notelslist_item添加一个 textView

图片2

Notelist类参数添加

图片3/4

显示保存时间

图片5

2.	时间更新

由于时间只记录最早保存，所以不会更新

找到notepadprovider类更新的方法update

添加以下的代码

图片6

便可更新

图片7

3.	搜索功能

图片8
