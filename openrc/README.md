```
emerge --ask \
  net-misc/curl \
  app-misc/jq \
  dev-java/openjdk:25 \
  app-accessibility/at-spi2-core \
  x11-libs/libXcomposite \
  x11-libs/libXdamage \
  x11-libs/libxkbcommon \
  x11-libs/pango \
  media-libs/libva-intel-media-driver \
  media-libs/mesa
```

```
echo "/usr/lib64/openjdk-25/lib/server" > /etc/ld.so.conf.d/openjdk-25.conf
```
