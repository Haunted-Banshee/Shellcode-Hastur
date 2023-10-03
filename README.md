# Shellcode-Hastur
Shellcode Reductio Entropy Tools

## 一、使用说明

直接下载使用即可

```
Shellcode-Hastur.exe -h
usage: Shellcode-Hastur.exe [-h] [-file] [-uuid] [-mac] [-ipv4] [-ipv6] [-english] shellcode

Shellcode Reductio Entropy Tools

positional arguments:
  shellcode   Shellcode to Convert

optional arguments:
  -h, --help  show this help message and exit
  -file       Please Enter the File name
  -uuid       Shellcode Convert to UUID String
  -mac        Shellcode Convert to MAC address
  -ipv4       Shellcode Convert to IPv4 address
  -ipv6       Shellcode Convert to IPv6 address
  -english    Shellcode Convert to English Words
```

## 二、示例

查询文件熵，以notepad为例

![1](https://github.com/Haunted-Banshee/Shellcode-Hastur/blob/main/img/1.png)

转换shellcode 为 UUID、IPv4、IPv6、MAC、English Words





## 三、Currently supported features

- [x] Query File Entropy
- [x] Convert to UUID String
- [x] Convert to MAC address
- [x] Convert to IPv4 address
- [x] Convert to IPv6 address
- [x] Convert to English Words

## 四、Future Features I'm aiming to support

- [ ] Random English Words
- [ ] 更多的自实现降熵方法
- [ ] More Shellcode Template
