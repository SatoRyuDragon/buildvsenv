# Visual Studio & OpenCVSharp の環境構築 for セキュ実験後半組 Part3
← [part2](./part2.md)

## 1.はじめに
* たぶん最終回です
* この記事は[part1](./part1.md)を読み、環境構築を済ませた前提で書いています。ただIED環境でもほぼ同じだと思います...

## 2. 今回は
* 「Windows フォームアプリケーション」テンプレートを用いてOpenCVSharpを使用する環境構築の仕方を紹介します。

## 3. Hello world!
Part1の3.3.2を参考に、Windows フォームアプリケーション テンプレートでコードが書ける状態にしてください。
![](./picture/part3/1.PNG)  
上図の左側にある「ツールボックス」を押してください。  
![](./picture/part3/2.PNG)  
「すべてのWindows フォーム」の左側にある▷を押し  
![](./picture/part3/3.PNG)  
「TextBox」をダブルクリックすると、マウスのポインタが変わるのでフォーム内の適当な場所をクリックすると  
![](./picture/part3/4.PNG)  
このようにテキストボックスが作れます！  
![](./picture/part3/6.PNG)  
右下のオプションで今作ったTextBoxのオプションが弄れます、「(Name)」の内容は使うので覚えておきましょう  
![](./picture/part3/6-1.PNG)  
ソリューション エクスプローラから「Form1.cs/Form1/Form1()」をダブルクリックすると  
![](./picture/part3/7.PNG)  
Form1.csが弄れます！Form1の内容を上図のように設定し

![](./picture/part3/8.PNG)  
「▷開始」を押すと  
![](./picture/part3/9.PNG)  
「Form1」というウィンドウが表示され、真ん中のTextBoxに「Hello world!」と書かれていますね！ここまでできれば成功です！
## 4. OpenCVSharpの使用
次はOpenCVSharpを使用する方法を学んでみましょう！  
![](./picture/part3/10-1.PNG)  
事前にPart2と同様にWebClassからダウンロードしたOpenCVSharp2.4.10の中身をすべてプロジェクトフォルダ内の"bin/Debug"内にコピーしてください。  
![](./picture/part3/10-2.PNG)  
参照は"OpenCVSharp.dll","OpenCVSharp.CPlusPlus.dll","OpenCVSharp.Extensions.dll"のすべてを参照してください。  
![](./picture/part3/10.PNG)  
ツールボックス/すべてのWindows フォーム/PictureBoxを選択して作成すると
![](./picture/part3/11.PNG)  
上図のようなボックスが作成されます。  
![](./picture/part3/12.PNG)  
大きさを適当に決めて  
![](./picture/part3/13.PNG)  
Form1.csを上図のように書いて  

![](./picture/part3/8.PNG)  
開始を押すと

![](./picture/part3/14.PNG)  

このようなウィンドウが出れば成功です！お疲れさまでした！（戦いはこれから）

← [part2](./part2.md)  
