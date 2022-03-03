# settings_themes

## 链接

在Unix系统中, 可以对软件创建**硬链接**和**软连接**.

### 硬链接

硬链接是一个目录条目，它指具有同一个i-node（硬盘上的物理位置）的另一个文件，事实上只存在一个文件.

```bash
ln ~/Github/xiaorui77 ~/Library/Application Support/abnerworks.Typora/themes
```

### 软连接

软链接类似快捷方式,是一个独立的文件, 其中包含了指向一个位置的指针

```bash
ln -s [原文件] [软连接文件]
ln -s ~/Github/xiaorui77 ~/Library/Application Support/abnerworks.Typora/themes
```
