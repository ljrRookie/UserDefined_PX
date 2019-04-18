# UserDefined_PX
自定义像素适配方法



### 适配前：
<img src=https://github.com/ljrRookie/UserDefined_PX/blob/master/image/snipaste_20190418_150905.png></img>
<img src="https://github.com/ljrRookie/UserDefined_PX/blob/master/image/snipaste_20190418_143140.png"></img>


### 适配方法
根据屏幕宽高和设计稿宽高比，在父布局的onMeasure()中为子控件重新设置布局属性
<img src="https://github.com/ljrRookie/UserDefined_PX/blob/master/image/snipaste_20190418_152546.png"></img>

在布局文件中直接按照设计稿像素设值
<img src="https://github.com/ljrRookie/UserDefined_PX/blob/master/image/snipaste_20190418_151033.png"></img>

### 适配后
<img src=https://github.com/ljrRookie/UserDefined_PX/blob/master/image/snipaste_20190418_150133.png></img>
<img src="https://github.com/ljrRookie/UserDefined_PX/blob/master/image/snipaste_20190418_150212.png"></img>
