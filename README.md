# 效果图
![效果图](https://github.com/OneGreenHand/CenterEdittext/blob/master/pictor/gif.gif?raw=true)  
## 如何使用
dependencies {  
　`implementation 'com.github.OneGreenHand:CenterEdittext:v1.0'`   
}  
## 布局中  
     <com.green.hand.mylibrary.CenterEdittext
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="icon居中效果"
        app:drawableIcon="@drawable/search_black"
        app:isCenter="true"
        app:isShowHint="true"
        app:isShowLeft="false" />           

## **其他方法**  
isOpen　　　　~~~~~~~~>　是否开启使用，默认为true,为false时和普通Edittext一致  
isCenter　　　~~~~~~~~>　是否居中显示，默认为false  
isShowLeft　　~~~~~~~~>　输入后icon是否居左显示,默认为false  
isShowHint　　~~~~~~~~>　输入后hint是否显示，默认为true  
drawableIcon　~~~~~~~~>　icon资源，不填有默认图片  
#### **欢迎Start或提issues！**