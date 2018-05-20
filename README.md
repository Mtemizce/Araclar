## **İçerik:**
1. [Margin ve Padding](https://github.com/Mtemizce/CssColors/blob/master/README.md#-margin-ve-padding-tan%C4%B1mlamalar%C4%B1-)
   -[Toplam Margin ve Padding] (https://github.com/Mtemizce/CssColors/blob/master/README.md#toplam-margin-ve-padding-kullan%C4%B1m%C4%B1)
   -[Dikey Margin ve Padding] (https://github.com/Mtemizce/CssColors/blob/master/README.md#dikey-margin-ve-padding-kullan%C4%B1m%C4%B1)
   -[Yatay Margin ve Padding] (https://github.com/Mtemizce/CssColors/blob/master/README.md#yatay-margin-ve-padding-kullan%C4%B1m%C4%B1)
   -[Top Margin ve Padding] (https://github.com/Mtemizce/CssColors/blob/master/README.md#top-margin-ve-padding-kullan%C4%B1m%C4%B1)
   -[Right Margin ve Padding] (https://github.com/Mtemizce/CssColors/blob/master/README.md#right-margin-ve-padding-kullan%C4%B1m%C4%B1)
   -[Bottom Margin ve Padding] (https://github.com/Mtemizce/CssColors/blob/master/README.md#bottom-margin-ve-padding-kullan%C4%B1m%C4%B1)
   -[Left Margin ve Padding] (https://github.com/Mtemizce/CssColors/blob/master/README.md#left-margin-ve-padding-kullan%C4%B1m%C4%B1)
   
2. [CSS Renkler](https://github.com/Mtemizce/CssColors/blob/master/README.md#css-renkler)
   -[Yazı Örnek](https://github.com/Mtemizce/CssColors/blob/master/README.md#yaz%C4%B1-%C3%96rnek)
   -[Arkaplan Örnek](https://github.com/Mtemizce/CssColors/blob/master/README.md#arkaplan-%C3%96rnek)
   -[Koyu ve açık ton renk uygulaması](https://github.com/Mtemizce/CssColors/blob/master/README.md#koyu-ve-a%C3%A7%C4%B1k-ton-renk-uygulamas%C4%B1)
   - [Renk Listesi](https://github.com/Mtemizce/CssColors/blob/master/README.md#renk-listesi-ve-tan%C4%B1mlamalar)
   

### **Margin ve Padding Tanımlamaları**
[Css dosyası için tıkla](docs/mar-pad.css)<br>
Çoğumuz bootstrap gibi css framework kullanma taraftarı olsakta bi yanımız kendi framework hayalini kurar. Bazılarımızda bunun çok zaman alıcı olduğunu düşünerek vazgeçer. Vaktinizi almaması için hazır hali ile css şeklinde paylaştım umarım faydalı olur.

Verilen sayısal değerler şu şekilde: 0-5-10-15-20-30-40-50-60

## **Margin kullanımı:**
 4 tip kullanımı mevcut. Toplam, Yatay, Dikey ve ayrı ayrı uygulamalar.<br>
## **Toplam Margin ve padding kullanımı:**
 ```
 <div class="mar-5">Toplam 5px Margin Uygulandı</div>
 <div class="pad-5">Toplam 5px Padding Uygulandı</div>
```

## **Dikey Margin ve padding kullanımı:**
 ```
 <div class="mar-y-10">Dikey 10px Margin Uygulandı</div>
 <div class="pad-y-10">Dikey 10px Padding Uygulandı</div>
```

## **Yatay Margin ve padding kullanımı:**
 ```
 <div class="mar-x-15">Yatay 15px Margin Uygulandı</div>
 <div class="pad-x-15">Yatay 15px Padding Uygulandı</div>
```

## **Normal Margin ve Padding kullanımı:**
 Margin ve Padding i tek yönde de kullanabilirsiniz. Bunun için aşağıdaki örnekleri inceleyin.
 
## **Top Margin ve Padding kullanımı:**
 ```
 <div class="mar-t-30">Margin Top 30px Uygulandı</div>
 <div class="pad-t-30">Padding Top 30px Uygulandı</div>
```
## **Right Margin ve Padding kullanımı:**
 ```
 <div class="mar-r-40">Margin Right 40px Uygulandı</div>
 <div class="pad-r-40">Padding Right 40px Uygulandı</div>
```
## **Bottom Margin ve Padding kullanımı:**
 ```
 <div class="mar-b-50">Margin Bottom 50px Uygulandı</div>
 <div class="pad-b-50">Padding Bottom 50px Uygulandı</div>
```
## **Left Margin ve Padding kullanımı:**
 ```
 <div class="mar-l-60">Margin Left 60px Uygulandı</div>
 <div class="pad-l-60">Padding Left 60px Uygulandı</div>
```

### **CSS Renkler:**
Kendi projelerimde kullanmak için less olarak hazırlayıp css compile etmiştim ama fazla bu işe vakit ayrırmak istemeyen arkadaşlarımız için css compile halini paylaşıyorum. Zor değil herkesin yapabileceği şeyler ama olur ya uğraşmak istemeynde çıkabilir.<br>
Renkleri Normal, 20% Koyu ve 10% Açık olarak 3 kısma ayırdım. Yazı ve Arkaplan olarak 2 kısımdır.<br>
Yazı olarak kullanmak için class kısmına txt-(renk ismi)<br>
Arkaplan olarak kullanmak için class içerisine bg-(renk ismi)<br> 

## **Yazı Örnek:**
```
<div class="txt-yellow">Sarı Renkli Yazı</div>
```

## **Arkaplan Örnek**
```
<div class="bg-yellow">Sarı Arkaplanlı</div>
```

## **Koyu ve açık ton renk uygulaması**
```
<div class="txt-dark-yellow">Koyu Sarı Yazı</div>
<div class="txt-light-yellow">Açık Sarı Yazı</div>
<div class="bg-light-yellow">Açık Sarı Arkaplan</div>
<div class="bg-dark-yellow">Koyu Sarı Arkaplan</div>
```

## **Renk Listesi ve Tanımlamalar**
 ```
 - Red:		#FF0000
 - Blue:		#0000FF
 - Orange:	#FFA500
 - Yellow:	#FFFF00
 - Black:	#000000
 - White:	#FFFFFF
 - Gray:		#808080
 - Green:	#008000
 - Purple:	#800080
 - Olive:	#556B2F
 - Begie:	#F5F5DC
 - Pink:		#FFC0CB
 - Indigo:	#6574CD
 - Teal:		#4DC0B5
 - Brown:	#5D4037
 - Bluegray:	#78909c
```
