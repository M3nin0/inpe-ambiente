## Configuração do ambiente R

Esta página apresenta os passos para a configuração do ambiente R para o curso de `Introdução à análise de dados` utilizando o Anaconda. Tal configuração é feita com a instação dos pacotes base da linguagem e as dependências utilizadas no curso.

Inicialmente faça a criação de um ambiente virtual, para alocar todos os pacotes do R separados do Python. Isto evita problemas de dependências.

```shell
conda create --name r-env
```

Com o ambiente criado faça sua ativação

```shell
conda activate r-env
```

> Veja que ao executar o comando `conda activate` o canto esquerdo de seu terminal anaconda muda de `(base)` para `(r-env)`. Sempre que você quiser utilizar R terá de executar este comando

Dentro do ambiente R, faça a instalação dos pacotes do R utilizados no curso

```shell
conda install -c r r-essentials
```

Depois de utilizar este comando, faça a instalação do pacote `sf`.

```shell
conda install -c conda-forge r-sf
```

Feito! Com os comandos executados com sucesso, seu ambiente já estará configurado.

## Dica

Caso você esteja no ambiente R e deseja voltar para o ambiente Python, utilize o seguinte comando

```shell
conda activate base
```
