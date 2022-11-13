# Linuxのしくみ 実験と図解で学ぶOS、仮想マシン、コンテナの基礎知識

## 初期設定

sudo apt install binutils build-essential golang sysstat fonts-takao fio quemu-kvm virt-manager libvirt-clients virtinst jq docker.io containerd libvirt-daemon-system
sudo adduser `id -un` libvirt
sudo adduser `id -un` libvirt-qemu
sudo adduser `id -un` kvm

## 参考リポジトリ

https://github.com/satoru-takeuchi/linux-in-practice-2nd
