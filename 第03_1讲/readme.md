
### 切换盘符的目录到D盘
```bash
cd /d D:\Paddle_tutorial
```
### 进入anaconda环境
```bash
conda activate
```

### 创建一个名为paddle_tutorial的环境，指定Python版本是3.7
```bash
conda create --name paddle_tutorial python=3.7
```
**注意** 这个虚拟环境在C盘./conda文件夹里

### 进入刚才创建的paddle_tutorial的环境
```bash
conda activate paddle_tutorial
```

### conda列出虚拟环境
```bash
conda env list
```

### conda退出虚拟环境
```bash
conda deactivate
```
### 查看虚拟环境中安装的所有库文件
```bash
conda list
```

### 更新所有库文件
```bash
conda update --all
```

### 安装库文件
```bash
conda install package
```

### conda更新库文件
```bash
conda update package
```

### conda删除虚拟环境
```bash
conda remove -n your_env_name --all
```
