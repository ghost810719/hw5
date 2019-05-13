
# Homework5_team3


1. Take multi-view images by yourselves
![](https://i.imgur.com/Bq9IMiy.jpg)
![](https://i.imgur.com/m3Tx9ui.jpg)
![](https://i.imgur.com/nzb0Ggt.jpg)
![](https://i.imgur.com/bt2SHUk.jpg)
![](https://i.imgur.com/Ad9UZLa.jpg)


2. Show image alignment results between different images
以下是每張圖和前一張圖片做alignment的結果，第一張因為沒有可以比對的圖片，所以是和原圖一樣。
![](https://i.imgur.com/zobEe95.jpg)
![](https://i.imgur.com/pXpp9OA.jpg)
![](https://i.imgur.com/rCt9nDF.jpg)
![](https://i.imgur.com/aKgLdlL.jpg)
![](https://i.imgur.com/HRCyK7o.jpg)



3. Generate the multi-view 3D visual effects
https://drive.google.com/open?id=1WTe8049Re5eOk43SAG-2nAITiDcJ7Cl9
4. Exploit creativity to add some image processing to enhance effect (Using post-production software is allowed)
雪景效果:
https://drive.google.com/open?id=1HaoEiuQLPG9k0pu-scSoV_2tGetjY2bv

## Conclusion

   要製作出multi-view 3D的圖，首先要先拍出多個角度的圖，再把這些圖先用Image alignment 的方式來對齊圖片。其中會用到ORB feature detector找出對應特徵，再來進行匹配(Match Features)、計算和變形(Warping image)，而產生不同角度的圖像對齊。最後再把這些照片集合起來，產生GIF。



