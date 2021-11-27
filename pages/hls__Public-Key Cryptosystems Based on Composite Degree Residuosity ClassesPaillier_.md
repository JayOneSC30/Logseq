file:: [Public-Key Cryptosystems Based on Composite Degree Residuosity ClassesPaillier_.pdf](file://D:\Application\ZoteroBeta\data/storage/4QQCGQYW/Public-Key Cryptosystems Based on Composite Degree Residuosity ClassesPaillier_.pdf)
file-path:: file://D:\Application\ZoteroBeta\data/storage/4QQCGQYW/Public-Key Cryptosystems Based on Composite Degree Residuosity ClassesPaillier_.pdf

## 背景
- Diffie and Hellman
  hl-page:: 1
  ls-type:: annotation
  id:: 6171750d-ab22-4fc1-a2e6-accf61db6672
  这是不是最早的公钥加密文章呢？
## DCRA 问题
-
- $RSA[n, e]$
  hl-page:: 2
  ls-type:: annotation
  id:: 6175159b-4035-4793-a064-a4e966434a88
  这个表示方法应该表示的是解出 e 次剩余的根
- $polynomially\ reducible$ **(多项式规约)**
  hl-page:: 2
  ls-type:: annotation
  id:: 617519c4-48a9-4cf8-ae31-150d9c875141
  > Google: We say A is polynomially reducible to B if there exists a polynomial time algorithm that converts each input a to A and another input b to B such that the answer to input a for problem A is YES if and only if the answer to input b for problem B is YES.
  所以这里是双向的，但是论文里的证明是单向的？
- $CR[n]$
  hl-page:: 3
  ls-type:: annotation
  id:: 61721ae9-2e27-4e8c-aff5-039b8a95ab38
- **Conjecture 2.** $There\ exists\ no\ polynomial\ time\ distinguisher\ for\ n-th\ residues\ modulo\ n^2\ , i.e.\ CR [n]\ is\ intractable.$
  hl-page:: 3
  ls-type:: annotation
  id:: 61721928-b083-474d-8aa1-70672c640f45
  也就是说提出了一个假设，即 $n$ 次剩余的判定是困难的，
-
## Further Research
hl-page:: 14
ls-type:: annotation
id:: 61755200-f019-4500-8ba4-6749df68ac19
- [:span]
  hl-type:: area
  hl-stamp:: 1635078541741
  hl-page:: 14
  ls-type:: annotation
  id:: 6175518e-c7d3-493f-8cd8-8649970dbc2b
  可以讲一下 CCA 攻击下的安全性；
## 拓展阅读
- _"Provable Security of Cryptosystems: A Survey"_ 介绍随机自归约
  hl-page:: 15
  ls-type:: annotation
  id:: 61721b7d-4561-4a7b-96d8-3f0f383f5edf
- _"Locally Random Reductions in Interactive Complexity Theory,in Advances in Computational Complexity Theory"_ 
  hl-page:: 15
  ls-type:: annotation
  id:: 61721bd6-6dca-4b23-88f7-8f940e27057d
  [[@Locally Random Reductions in Interactive Complexity Theory]] 
  [[hls__1993_Locally Random Reductions in Interactive Complexity Theory_Feigenbaum]]
- _"A New Public-Key Cryptosystem Based on Higher Residues"_
  hl-page:: 15
  ls-type:: annotation
  id:: 61722a77-15c0-4b97-b201-cc3329b1bdaa