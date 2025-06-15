# AdGuard-Home-with-Docker
AdGuard Homeをdocker composeで簡単に構築

# 構築時の注意点
基本的にUbuntu等ではデフォルトのローカルリゾルバが動いてるため、停止する必要があります
```bash
sudo systemctl disable --now systemd-resolved
```