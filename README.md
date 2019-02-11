# Termux-Apktool

The original file 
https://github.com/iBotPeaches/Apktool


Install 

```bash
git clone https://github.com/Lexiie/Termux-Apktool
cd Termux-Apktool
dpkg -i apktool_2.3.4_all.deb
```

Decompile

```bash
apktool d yourapk 
```

Recompile 

```bash
apktool b yourfolder/ --output out.apk
```

Sign use apksigner

```bash
pkg install apksigner
apksigner -p yourpassword keystore yourapk newapkname
```