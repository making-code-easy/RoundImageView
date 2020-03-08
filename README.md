# RoundImageView

## It is a customImageView with extra attribute to round the image

![Screenshot from 2020-03-08 19-11-45](https://user-images.githubusercontent.com/60314231/76164155-914b0400-6172-11ea-860c-a594426d677a.png)


## Code
 `This is the custom image view
  there is one atttribute` 
  
  
  app:imageViewRadius="50dp" 
  
  
 ` which is deciding the radius of ImageView
  `

``` xml
<com.vishnu.roundedimageview.RoundImageView
        android:layout_width="100dp"
        android:layout_height="100dp"
        android:src="@mipmap/ic_launcher"
        app:imageViewRadius="50dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
```
