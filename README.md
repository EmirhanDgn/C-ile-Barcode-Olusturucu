# C-ile-Barcode-Olusturucu
C# Form Uygulaması ile Yazılan Metini Barcode Şekline Dönüştürme


Textbox üzerine girmiş olduğunuz herhangi bir metini barcode biçimine dönüştürerek PictureBox içerisinde göstermektedir.

<h2> Uygulama Resimleri</h2>

![barcode1](https://user-images.githubusercontent.com/76941464/165888848-90913d72-c6ab-4e8e-857a-09e1b61533f8.png)


![barcode2](https://user-images.githubusercontent.com/76941464/165888850-866926be-0ba2-4a45-8f2d-4bfa61274f35.png)


<h2> Function Kodu </h2>
<pre>
Zen.Barcode.Code128BarcodeDraw barcode = Zen.Barcode.BarcodeDrawFactory.Code128WithChecksum;
pictureBox1.Image = barcode.Draw(txtBarcode.Text, 50);
</pre>
