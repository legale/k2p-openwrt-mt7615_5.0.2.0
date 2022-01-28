# k2p-openwrt-mt7615_5.0.2.0
For openwrt 18.06
Put directory mtk into ./package

```Make menuconfig```

Chinese version compilation options: https://www.right.com.cn/forum/thread-572784-1-1.html For stability, use lean source code, remove the default selected bandwidth monitoring and open source mt7615 driver. Don't choose any QOS NFTABLES

The errors encountered during compilation refer to the patch of hanwckf https://github.com/hanwckf/openwrt-mt7615
