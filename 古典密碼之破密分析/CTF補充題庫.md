#
```

```

## 補充題1
```
picoCTF-2019/13
Cryptography can be easy, do you know what ROT13 is? 
cvpbPGS{abg_gbb_onq_bs_n_ceboyrz}
```
```
https://cryptii.com/pipes/rot13-decoder
```
## 補充題2
```
連豬圈裏的豬都會的密碼
```
![cipher](./pic/cipher.png)

## 補充題3
```
希伯來 Atbash 之謎

uozt{S H W 2021}
```


## 補充題4
```
AngstromCTF 2019/Classy Cipher

Every CTF starts off with a Caesar cipher, but we're more classy.

Author: defund

from secret import flag, shift

def encrypt(d, s):
	e = ''
	for c in d:
		e += chr((ord(c)+s) % 0xff)
	return e

assert encrypt(flag, shift) == ':<M?TLH8<A:KFBG@V'
```
```
def decrypt(e, s):
    d = ''
    for c in e:
        d += chr((ord(c)-s) % 0xff)
    return d

for i in range(1, 300):
    f = decrypt(':<M?TLH8<A:KFBG@V', i)
    if 'actf' in f:
        print(f)
        exit()
```
```
https://jsur.in/post/2019-04-23-angstromctf-2019-writeups
```


