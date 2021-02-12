# G1「機械学習による手書き文字の識別」

## 概要
機械学習を用いた文字認識は主にCNNを用いた方法と、文字の特徴を選択し、識別する方法があることがわかった。そのため本実験では、上記の2つの方法で実験を行い、どのような差があるのか調べる。また、どのような学習方法や処理を行うことで文字認識をしているのか、精度を上げる方法はあるのかを実験し調べる。

## 環境 
データセット
> MNIST <http://yann.lecun.com/exdb/mnist/>

深層学習
>macOS Catelina version 10.15.7  
>Python                 3.7.6  
>pip                    21.0.1  
>numpy                  1.19.0  
>matplotlib             3.3.0  
>tensorflow             2.2.0  
>keras                  2.3.0   

特徴量選択
>#環境名を「hogehuga」として作成する場合。  
>conda create -n hogehuga python=3.7  
>  
>#環境をhogehugaに変更  
>conda activate hogehuga  
>  
>#必要なpackageをinstall。  
>pip install sklearn  
>pip install emnist  
>pip install matplotlib  



## 実行方法

深層学習  

・1つ目のモデル  
nal_G1.pyを実行  
  
・2つ目のモデル  
nal_G1_300.pyを実行  
  
・3つ目のモデル  
nal_G1_test1.pyを実行  
  
・4つ目のモデル  
nal_G1_test2.pyを実行  
  

特徴量選択  
引用引用
