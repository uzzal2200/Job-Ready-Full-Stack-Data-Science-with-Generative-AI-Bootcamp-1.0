conda create -n helmet python=3.9 -y

conda activate helmet

conda env list

conda remove --name helmet --all


conda create --prefix .\helmet python=3.9 -y

conda activate .\helmet
