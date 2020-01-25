## Configuração do ambiente Python

Esta página apresenta os passos para a configuração do ambiente Python para o curso de `Introdução à análise de dados` utilizando o Anaconda.

Para começar a configuração do ambiente Python, vá para o ambiente virtual `base` do Anaconda, para isto execute o comando abaixo

```shell
conda activate base
```

Agora, faça a instalação dos pacotes `geopandas` e `descartes`.

```shell
conda install geopandas descartes
```

Ao executar o comando, o ambiente começará a carregar e será necessário aceitar que os pacotes sejam baixados.

Com o final da instalação, seu ambiente já estará pronto para a utilização.

## Dica

Caso você esteja no ambiente Python e deseja ir para o ambiente R, utilize o seguinte comando

```shell
conda activate r-env
```

> Este comando só é válido após a [configuração do ambiente R](config-env-r.md)
