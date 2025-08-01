# teamwork
we are family!



Install Conda in HPC

```
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
sh Miniconda3-latest-Linux-x86_64.sh
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


