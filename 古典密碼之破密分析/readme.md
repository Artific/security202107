# agenda
```
1_密碼學 ==>加密與解密

2_密碼學類型

3_古典密碼
  ROT13（rotate by 13 places|ROT-13)
  凱撒密碼(Caesar cipher)
  維吉尼亞密碼(Vigenère cipher)
  古希臘斯巴達的密碼棒
  
4_破密分析與攻擊
  brute force attack 暴力破解
  Frequency analysis 頻率分析
  
5_工具與技術
```
### 上課時程 : 1-2小時

# 1_密碼學 ==>加密與解密
```
https://en.wikipedia.org/wiki/Cryptography

明文(Plaintext)與密文(ciphertext)
金鑰(key)
加密(encryption)與解密(decryption)
```
```
範例 ==> Vigenère square
https://en.wikipedia.org/wiki/Classical_cipher


明文(Plaintext)  ==>	ATTACKATDAWN
金鑰(key)        ==>	LEMONLEMONLE
密文(ciphertext) ==>	LXFOPVEFRNHR

加密(encryption) ==> 明文(Plaintext)變密文(ciphertext)
解密(decryption) ==> 密文(ciphertext)變明文(Plaintext)
```
# 2_密碼學類型
```
https://en.wikipedia.org/wiki/Cryptography

Classic cryptography(古典密碼|經典密碼)

Modern cryptography(現代密碼)
   安全性基礎 ==＞ computational hardness assumptions
　　　　　RSA ==＞ integer factorization algorithms
          
Quantum cryptography(量子密碼)
　　安全性基礎 ==＞量子力學基本原理
    利用量子力學的特性來加密的科學
    https://en.wikipedia.org/wiki/Quantum_cryptography

POST-Quantum cryptography(後量子密碼)
    cryptographic algorithms (usually public-key algorithms) that are thought to be secure 
    against a cryptanalytic attack by a quantum computer
    https://en.wikipedia.org/wiki/Post-quantum_cryptography
```
# 3_Classic cryptography(古典密碼)
```
經典密碼大致上分為替換式密碼和移項式密碼
Classical ciphers are often divided into 
transposition ciphers(移項式密碼) and substitution ciphers(替換式密碼).

[1] Substitution ciphers替換式密碼

     字母（或是字母群）作有系統的代換，直到訊息被替換成其它難以解讀的字
     In a substitution cipher, letters (or groups of letters) are systematically replaced 
     throughout the message for other letters (or groups of letters)
    
    單字母替代式密碼(monoalphabetic substitution ciphers) == > Caesar cipher | Affine cipher
   
    多字母替代式密碼(polyalphabetic substitution ciphers) == > Vigenère cipher
    
[2]transposition ciphers(移項式密碼)   
    scytale 古希臘斯巴達的密碼棒
    Rail fence cipher
```
## [1] Substitution ciphers替換式密碼
### ROT13（rotate by 13 places|ROT-13)
```
https://zh.wikipedia.org/wiki/ROT13
```
### 凱撒密碼(Caesar cipher)
```
https://en.wikipedia.org/wiki/Caesar_cipher
```
```
https://www.dcode.fr/caesar-cipher
```
### Affine cipher
```
https://en.wikipedia.org/wiki/Affine_cipher
```

### 維吉尼亞密碼(Vigenère cipher)
```
https://en.wikipedia.org/wiki/Vigen%C3%A8re_cipher
```
## [2]transposition ciphers(移項式密碼) 
### 古希臘 斯巴達的密碼棒
```
https://en.wikipedia.org/wiki/Scytale
```
### Rail fence cipher
```
https://en.wikipedia.org/wiki/Rail_fence_cipher
```
# 4_破密分析與攻擊(Cryptanalysis of classical ciphers)
```
brute force attack 暴力破解 == > 金鑰個數有限
Frequency analysis 頻率分析 == > 金鑰個數比較多
```
## brute force attack 暴力破解
```
https://en.wikipedia.org/wiki/Brute-force_attack

蠻力攻擊（英語：Brute-force attack），又稱為窮舉攻擊（英語：Exhaustive attack）或暴力破解，是一種密碼分析的方法
將密碼進行逐個推算直到找出真正的密碼為止

例如：一個已知是四位數並且全部由阿拉伯數字組成的密碼，其可能共有10000種組合，因此最多嘗試9999次就能找到正確的密碼
```
## Frequency analysis 頻率分析
```
Frequency analysis
https://en.wikipedia.org/wiki/Frequency_analysis

頻率分析是指研究字母或者字母組合在文本中出現的頻率。應用頻率分析可以破解古典密碼。

頻率分析基於如下原理：在任何一種書面語言中，不同的字母或字母組合出現的頻率各不相同。
而且，對於以這種語言書寫的任意一段文本，都具有大致相同的特徵字母分布。
比如，在英語中，字母E出現的頻率很高，而X則出現得較少。類似地，ST、NG、TH，以及QU等雙字母組合出現的頻率非常高，NZ、QJ組合則極少。
英語中出現頻率最高的12個字母可以簡記為「ETAOIN SHRDLU」
```
# 5_工具與技術
```
基礎篇 == >使用線上工具
中級篇 == >使用指令
高級篇 == >Python 程式解題
```
# 後續課程
```

```
