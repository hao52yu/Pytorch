# Pytorch环境配置

## 1、conda指令

**创建环境：** conda create -n env_name python=3.x

**激活环境：**  conda activate env_name

**退出环境： **  conda deactivate

**查看已有的环境： **  conda env list

**删除环境**：  conda remove -n env_name --all

**配置国内镜像源：**

（貌似不好用，建议直接挂梯子）

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
conda config --set show_channel_urls yes

conda clean -i

**清除配置：**

conda config --remove-key channels

## 2、pip指令

pip install -r requirements.txt 根据requirements.txt 中的内容安装包

pip install package_name 安装包

