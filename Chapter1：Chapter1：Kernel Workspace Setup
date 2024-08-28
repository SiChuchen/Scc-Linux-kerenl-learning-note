项目源码地址：

```c
https://github.com/PacktPublishing/Linux-Kernel-Programming
```

参考书籍《linux kernel programming comprehensive guide》

安装Ubuntu18，选择 VirtualBox 或者 VMWare workstation 进行安装（记住打开CPU的虚拟化开关，VMware需要从设置里打开CPU虚拟化开关）

确保其有足够的性能：CPU：双核，内存：4GB，硬盘：50GB（至少）

在Ubuntu虚拟机中（以下简称主机）安装相关的包

```bash
sudo apt update

sudo apt-get install git fakeroot build-essential tar ncurses-dev xz-utils libssl-dev bc stress python3-distutils libelf-dev linux-headers-$(uname -r) bison flex libncurses5-dev util-linux net-tools linux-tools-$(uname -r) exuberant-ctags cscope sysfsutils gnome-system-monitor curl perf-tools-unstable gnuplot rt-tests indent tree psmisc libnuma-dev numactl hwloc bpfcc-tools sparse flawfinder cppcheck bsdmainutils trace-cmd virt-what

sudo apt-get install lttng-tools
```

## 查找和使用Linux内核文档

- 社区经过多年的努力，已经将 Linux 内核文档发展和改进到一个良好的状态。最新版本的内核文档以一种美观且现代的“网页”风格呈现，我们可以随时在线访问：[Linux Kernel Documentation](https://www.kernel.org/doc/html/latest/)。
- 我们也可以直接从内核源码树中生成完整的 Linux 内核文档，并且可以生成多种流行格式（包括 PDF、HTML、LaTeX、EPUB 或 XML），类似于 Javadoc 或 Doxygen 的风格。内核内部使用的现代文档系统称为 Sphinx。在内核源码树中运行 `make help` 会显示多个文档目标，其中包括 `htmldocs`、`pdfdocs` 等。因此，我们可以例如 `cd` 到内核源码树，然后运行 `make pdfdocs`，将完整的 Linux 内核文档构建为 PDF 文档（PDF 文件以及其他一些元文档会被放置在 `Documentation/output/latex` 目录中）（第一次运行需要安装一些包，激活虚拟环境，请按照提示进行）。
