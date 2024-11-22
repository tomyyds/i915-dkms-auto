# 
原仓库[i915-sriov-dkms](https://github.com/strongtz/i915-sriov-dkms) 
实现自动化部署
11代以上intel核显自动安装i915 dkms驱动，并配置sriov核显
每次升级内核后，运行该脚本就可以自动编译安装i915dkms驱动，配置核显sriov
上传.sh到root目录下
运行 ./i915-dkms-auto 如果提示没有权限，输入chmod +x ./*.sh再次运行
