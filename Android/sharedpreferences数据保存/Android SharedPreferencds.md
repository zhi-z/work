# Android SharedPreferencds

- 创建一个文本编辑框和两个按钮，一个用于读取数据，一个用于保存数据

![1536066809108](C:\Users\RD007\AppData\Local\Temp\1536066809108.png)

添加一个公用的键：函数中放入的是一个键值对和对应的值，**这里后面两句好放好位置不然会出错。**

![1536066885766](E:\GitHub\work\Android\sharedpreferences数据保存\image\statement.png)



点击按钮进行数据保存：

![1536066975717](E:\GitHub\work\Android\sharedpreferences数据保存\image\put.png)



获取值：在这个函数中，第二个参数是当返回的数据不存在是，设置的默认值，当没有数据返回时，使用这个默认值。

![1536067345154](E:\GitHub\work\Android\sharedpreferences数据保存\image\getdata.png)