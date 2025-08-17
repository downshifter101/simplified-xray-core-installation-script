# Modification of simple-xray-core
  -no ui panel  
  -no need for tsl-sertificate or domain  
  -with TCP BBR congestion control  
  -debian server version  


## Installation process:

```sh
wget -qO- https://github.com/downshifter101/simplified-xray-core-installation-script/blob/main/xray-install | bash
```

## Usage

**Print client list:**

```sh
userlist
```

**Print qr-code to connect:**

```sh
mainuser
```

**Add user:**

```sh
newuser
```

**Delete user:**

```sh
rmuser
```

**Print connection link:**

```sh
sharelink
```

# Print Usage

```sh
cat ~/help
```

## See also
- [simple-xray-core](https://github.com/ServerTechnologies/simple-xray-core)
- [X-ray Core](https://github.com/XTLS/Xray-core)
- [Doc](https://xtls.github.io/ru/)

## Clients
**Windows**

- [v2rayN](https://github.com/2dust/v2rayN)  
- [Furious](https://github.com/LorenEteval/Furious)  
- [Invisible Man - Xray](https://github.com/InvisibleManVPN/InvisibleMan-XRayClient)  

**Android**

- [v2rayNG](https://github.com/2dust/v2rayNG)  
- [X-flutter](https://github.com/XTLS/X-flutter)  
- [SaeedDev94/Xray](https://github.com/SaeedDev94/Xray)  

**iOS & macOS arm64**

- [Streisand](https://apps.apple.com/app/streisand/id6450534064)  
- [Happ](https://apps.apple.com/app/happ-proxy-utility/id6504287215)  
- [OneXray](https://github.com/OneXray/OneXray)  

**macOS arm64 & x64**

- [V2rayU](https://github.com/yanue/V2rayU)  
- [V2RayXS](https://github.com/tzmax/V2RayXS)  
- [Furious](https://github.com/LorenEteval/Furious)  
- [OneXray](https://github.com/OneXray/OneXray)  

**Linux**

- [Nekoray](https://github.com/MatsuriDayo/nekoray)  
- [v2rayA](https://github.com/v2rayA/v2rayA)  
- [Furious](https://github.com/LorenEteval/Furious)  

## Delete:
```sh
bash -c "$(curl -L https://github.com/XTLS/Xray-install/raw/main/install-release.sh)" @ remove
rm /usr/local/etc/xray/config.json
rm /usr/local/etc/xray/.keys
rm /usr/local/bin/userlist
rm /usr/local/bin/mainuser
rm /usr/local/bin/newuser
rm /usr/local/bin/rmuser
rm /usr/local/bin/sharelink
```
