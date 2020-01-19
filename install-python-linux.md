# Instalação do Python no Linux (Ubuntu 18.04)

Esta página apresenta os passos para a instalação do Python 3.7 (Anaconda)

> Os passos foram testados no Ubuntu 18.04, porém versões superiores também serão compativeis.

Para iniciar, faça a instalação da ferramenta que auxilia no *download* dos pacotes

```shell
sudo apt-get update -y && sudo apt-get install wget -y
```

Feito a instalação, baixe o pacote de instalação do Anaconda.

```shell
wget https://repo.anaconda.com/archive/Anaconda3-2019.10-Linux-x86_64.sh
```

Com a conclusão do *download*, permita a execução do arquivo baixado e inicie a instalação.

```shell
chmod +x Anaconda3-2019.10-Linux-x86_64.sh
./Anaconda3-2019.10-Linux-x86_64.sh
```

No final da instalação será exibido uma opção para iniciar o ambiente Python junto ao seu `shell`, é recomendado que esta opção seja habilitada.

Com o ambiente instalado, faça a instalação dos pacotes `GeoPandas` e `descartes`.

```shell
conda install -c conda-forge geopandas descartes
```

> Caso você não tenha habilitado a inicialização do ambiente conda junto ao shell, a execução do comando acima deverá ser feita com: conda activate base && conda install -c conda-forge geopandas descartes
