---
description: 这是foc机场专属脚本
---

# foc对接脚本

首先要安装bbr plus

```text
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
```

之后我们就可以安装后端了

```text
wget https://syjc.ljfxz.com/foc/foc.sh && chmod +x foc.sh && bash foc.sh
```

如果遇到ssl报错下载不了 就按以下走：

```text
git  clone https://github.com/liujang/foc2.git && cd foc2 && chmod +x foc.sh && bash foc.sh
```

