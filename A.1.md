# A.1 初歩的事項

## 前提知識
数学II, III レベルのベクトルや微分の知識は必要そう。  
内容的には[『これなら分かる最適化数学』](https://www.amazon.co.jp/%E3%81%93%E3%82%8C%E3%81%AA%E3%82%89%E5%88%86%E3%81%8B%E3%82%8B%E6%9C%80%E9%81%A9%E5%8C%96%E6%95%B0%E5%AD%A6%E2%80%95%E5%9F%BA%E7%A4%8E%E5%8E%9F%E7%90%86%E3%81%8B%E3%82%89%E8%A8%88%E7%AE%97%E6%89%8B%E6%B3%95%E3%81%BE%E3%81%A7-%E9%87%91%E8%B0%B7-%E5%81%A5%E4%B8%80/dp/4320017862)が参考になりそう。

## A.1.1 ベクトル、関数、微分
- スカラー(scalar) : 一つの数字で表せる量。ex) 2, 3.1, -10000
- ベクトル(vector) : 二つ以上の数字を並べて表す量。ex) (1, 2), (3, 3, 3)  
  実数からなるd次元のベクトルの集合を![](https://texclip.marutank.net/render.php/texclip20180508112617.png?s=%24R%5Ed%24&f=c&r=150&m=p&b=f&k=f)で表す。  

二つのベクトル **x** と **y** の内積は、 **x** ･ **y** = ![](https://texclip.marutank.net/render.php/texclip20180508113605.png?s=%5Cbegin%7Beqnarray*%7D%0A%5Csum%20x_iy_i%0A%5Cend%7Beqnarray*%7D&f=c&r=150&m=p&b=f&k=f) と定義される。  
ex) **x** = (1, 2), **y** = (3, 4)とすると  
**x** ･ **y** = x1･y1 + x2･y2 = 1･3 + 2･4 = 3 + 8 = 11

- 関数：ある入力を与えると出力を返してくれるもの
- ベクトル値関数：出力がベクトルであるような関数 ex) f(x) = (x^2, 2x)
