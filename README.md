# Badge "Magic" Tool

## Download font

http://littlelimit.net/k8x12.htm

```sh
wget https://littlelimit.net/arc/k8x12/k8x12_ttf_2021-05-05.zip
unzip k8x12_ttf_2021-05-05.zip
```

## Build

```sh
go build .
```

## Download prebuilt version

```sh
curl -O badgemagic-tool https://github.com/orangecms/fossasia-badge/releases/download/v0.0.10/badgemagic-tool
chmod +x badgemagic-tool # set executable permissions
```

## Run it

```sh
sudo ./badgemagic-tool -mode anim -font k8x12.ttf "CyReVolt 段"
```

NOTE: If you set up udev rules, you will not need `sudo`.
