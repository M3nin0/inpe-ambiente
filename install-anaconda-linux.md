# Instalação do Anaconda 3 | Ubuntu 18.04

Esta página apresenta os passos para a instalação do ambiente [Anaconda 3](https://docs.anaconda.com/anaconda/), uma plataforma voltada para o gerenciamento de ambientes de execução para análise de dados, suportando linguagens como Python e R.

> Os passos realizados neste documento foram feitos no Ubuntu 18.04, mas podem ser reproduzidos em outras versões Linux, para saber mais consulte a [documentação do Anaconda](https://docs.anaconda.com/anaconda/install/linux/)

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

Agora inicie o ambiente do Anaconda e vá para as páginas de configuração dos ambientes utilizados no curso. 

> Caso você tenha habilitado a inicialização do ambiente conda junto ao `shell`, basta reiniciar o terminal e o ambiente já estará ativo, do contrário, será necessário utilizar o comando `conda activate base`

Com o conda configurado e ativado, vá para as páginas de configuração dos ambientes utilizados no curso.

- [Configuração do ambiente R](config-env-r.md)
- [Configuração do ambiente Python](config-env-python.md)
