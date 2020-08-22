# bt59happy
***本方法仅供学习参考，请在下载使用完毕的24小时内删除。使用时遵守中国大陆的相关法律，禁止传播。***
安装方法（baoTa 5.9.1 开心版面板）
使用 SSH 连接工具 连接到您的 Linux服务器后，根据系统执行相应命令开始安装（大约2分钟完成面板安装）：

Centos安装脚本:
`yum install -y wget && wget --no-check-certificate -O install.sh https://raw.githubusercontent.com/0xCP/bt59happy/master/install-5.9-c.sh && sh install.sh`
>大陆境内:
`yum install -y wget && wget --no-check-certificate -O install.sh https://cdn.jsdelivr.net/gh/0xCP/bt59happy@master/install-5.9-c.sh && sh install.sh`

Ubuntu安装脚本:
`wget --no-check-certificate -O install.sh https://raw.githubusercontent.com/0xCP/bt59happy/master/install-ubuntu.sh && sudo bash install.sh`
>大陆境内:
`wget --no-check-certificate -O install.sh https://cdn.jsdelivr.net/gh/0xCP/bt59happy@master/install-ubuntu.sh && sudo bash install.sh`

Debian安装脚本：
`wget --no-check-certificate -O install.sh https://raw.githubusercontent.com/0xCP/bt59happy/master/install-ubuntu.sh && bash install.sh`
>大陆境内:
`wget --no-check-certificate -O install.sh https://cdn.jsdelivr.net/gh/0xCP/bt59happy@master/install-ubuntu.sh && bash install.sh`

如果 你是免费的 5.x BT面板 可以使用脚本 升到最新的开心版 5.9.1 面板 或者 输入：
`curl https://raw.githubusercontent.com/0xCP/bt59happy/master/update_pro.sh | bash `
>大陆境内:
`curl https://cdn.jsdelivr.net/gh/0xCP/bt59happy@master/update_pro.sh | bash `

恢复免费面板:
`wget -O update.sh http://download.bt.cn/install/update.sh && bash update.sh free`
