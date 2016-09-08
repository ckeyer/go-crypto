# gocrypto
Golang 密码学编程

# Golang 环境

```
~ $ go version
go version go1.7 darwin/amd64
```

## Golang [crypto](https://golang.org/pkg/crypto/)标准库

Go语言标准库包含了大量的

### 包结构

- crypto
  - aes ：实现了AES加密
  - cipher ： 实现了标准块密码模式，用于分组加密的实现
  - des ：实现了DES加密
  - dsa ：实现了数字签名算法
  - ecdsa ：实现了椭圆曲线数字签名算法
  - elliptic ：实现了几个标准椭圆曲线
  - hmac ：实现了基于哈希的消息验证码
  - md5 ：实现了MD5算法
  - rand ：实现了密码安全的伪随机数生成器
  - rc4 ：实现了RC4加密,Bruce Schneier应用密码学中定义
  - rsa ：实现了RSA加密
  - sha1 ：实现了SHA1算法
  - sha256 ：实现了SHA256算法
  - sha512 ：实现了SHA512算法
  - subtle  ：实现了常用的密码学函数，但需要仔细考虑使用的正确性
  - tls ：部分实现了TLS 1.2
  - x509 ：解析x509协议与证书
     * pkix 

# golang官方库[golang.org/x/crypto](https://godoc.org/golang.org/x/crypto)

### 包结构

  - acme
     * internal
        - internal/acme
  - bcrypt
  - blowfish
  - bn256
  - cast5
  - curve25519
  - ed25519
     * internal
        - edwards25519
  - hkdf
  - md4
  - nacl
     * box
     * secretbox
  - ocsp
  - openpgp
     * armor
     * clearsign
     * elgamal
     * errors
     * packet
     * s2k
  - otr
  - pbkdf2
  - pkcs12
     * internal
        - rc2
  - poly1305
  - ripemd160
  - salsa20
     * salsa
  - scrypt
  - sha3
  - ssh
     * agent
     * terminal
  - tea
  - twofish
  - xtea
  - xts
 
### 其它相关包

math/big
encoding/base64

 
## 哈希

#### MD4
#### MD5
#### SHA1
#### SHA224
#### SHA256
#### SHA384
#### SHA512
#### MD5SHA1
#### RIPEMD160
#### SHA3_224
#### SHA3_256
#### SHA3_384
#### SHA3_512
#### SHA512_224
#### SHA512_256

## 对称加密

#### DES 
#### IDEA
#### RC2
#### RC4
#### SKIPJACK
#### RC5
#### AES

## 非对称加密

### 公私钥
### 签名
### 证书

### RSA
### DSA
### ECC
### Diffie-Hellman

