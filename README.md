# ddnsto 在 openwrt 的一键安装脚本

## 旧的安装方式如下

- 可以直接在软路由ttyd执行，复制👇👇👇
- ```sh -c "$(curl -sSL http://firmware.koolshare.cn/binary/ddnsto/openwrt/install_ddnsto.sh)"``` 
- 然后到ttyd终端下回车后进度结束。👇
- 刷新一下就出现在服务里了。如果还没明白，可以[**看视频**](https://www.bilibili.com/video/BV1mo4y197jK)如何安装就行
- 如果在过程中遇到安装失败，可以执行备用命令安装👇
- 备用命令 ```wget https://raw.githubusercontent.com/linkease/ddnsto_all_in_one_script/master/install_ddnsto.sh&& sh install_ddnsto.sh```

## 新的安装方式如下

### via curl
```
sh -c "$(curl -sSL http://firmware.koolshare.cn/binary/ddnsto/openwrt/install_ddnsto.sh)"
```
### via wget
```
sh -c "$(wget --no-check-certificate -qO- http://firmware.koolshare.cn/binary/ddnsto/openwrt/install_ddnsto.sh)"
```
#### Or
```
cd /tmp; wget --no-check-certificate http://firmware.koolshare.cn/binary/ddnsto/openwrt/install_ddnsto.sh; sh ./install_ddnsto.sh
```
# 使用方法教程
- ddnsto官方教程 ：[**👉点击链接👈]（https://www.ddnsto.com/zh/guide/quick.html#%E5%AE%89%E8%A3%85%E4%B8%89%E6%AD%A5%E8%B5%B0）
- YouTube教程:[**👉点击链接👈**](https://www.youtube.com/watch?v=nwf__oD9Z_8)
