# Install Mini Conda Mac M1
https://docs.anaconda.com/free/miniconda/ 

Download this file : https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh 

```
mkdir -p ~/miniconda3
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh -o ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
``

After installing, initialize your newly-installed Miniconda. The following commands initialize for bash and zsh shells:

```
~/miniconda3/bin/conda init bash
~/miniconda3/bin/conda init zsh
```

Check the version

`conda -V`
