# teamwork
we are family!



# Install Conda in HPC

```
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
sh Miniconda3-latest-Linux-x86_64.sh
```

## activate

```
source miniconda3/etc/profile.d/conda.sh

```
## create conda enviroment
```
conda create -n r_env r-base=4.3.2 -c conda-forge
```
```

# 安装jupyterlab
conda install -c conda-forge jupyterlab
#打开R
R

#在R中安装jupyter kernel
install.packages('IRkernel')
IRkernel::installspec(name = "r_env",displayname = "R(r_env)")

#退出R
q()

# 启动Jupyterlab
jupyter lab
# 会被问，敲y就好
#Proceed ([y]/n)? 
y

```

# ATAC
Clone the SupportingCRE git project
```
git clone https://github.com/IStevant/SupportingCRE.git
```
Install the Conda SupportingCRE environment
```
cd SupportingCRE
source ~/miniconda3/etc/profile.d/conda.sh
conda env create -f conda_env/SupportingCRE_env.yml
```


