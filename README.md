### 目录引用
1. [subfolder](./subfolder)
2. [subfolder1](./subfolder1)
### QR第三方库
1. [ThoughtWorks.QRcode](https://www.nuget.org/packages/ThoughtWorks.QRCode), :star:$null 1.1.0$, 下载78694次. 现用版本1.0
2. [QrCode.Net](https://www.nuget.org/packages/QRCoder/), QRCoder is a simple library, written in C#.NET, which enables you to create QR codes. It **hasn't any dependencies** to other libraries and is available as .NET Framework and .NET Core PCL version on NuGet.:star:$1.7k - 1.1.0$

```cs
using System.Drawing;  // Bitmap, Image

QRCodeGenerator qrGenerator = new QRCodeGenerator();
QRCodeData qrCodeData = qrGenerator.CreateQrCode("The text which should be encoded.", 
                        QRCodeGenerator.ECCLevel.Q);
QRCode qrCode = new QRCode(qrCodeData);
Bitmap qrCodeImage = qrCode.GetGraphic(20);
```

3. [ZXing.Net](https://github.com/micjahn/ZXing.Net/), .Net port of the original java-based barcode reader and generator library zxing, [java 版本](https://github.com/zxing/zxing), 读写都可以用
4. [其他](https://www.nuget.org/packages?q=qr), 主要还是前边3个
