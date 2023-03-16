# Executando o Sass para compilar o Bootstrap em tempo real
=========================================================

Este é um guia passo a passo para executar o Sass e compilar o Bootstrap em tempo real em seu projeto. O comando que vamos utilizar é o seguinte:

bashCopy code

`sass --watch scss/custom.scss:css/bootstrap.css`

Este comando irá monitorar o arquivo `custom.scss` em `scss/` e compilar as alterações em tempo real em `css/bootstrap.css`.

## Pré-requisitos
--------------

Antes de executar o comando, você precisa ter os seguintes pré-requisitos instalados em seu sistema:

-   Sass: verifique se você tem o Sass instalado em seu sistema. Se não tiver, instale-o executando o seguinte comando no terminal:

Copy code

`npm install -g sass`

## Passo a Passo
-------------

1.  Abra o terminal e navegue até o diretório raiz do seu projeto.
2.  Execute o seguinte comando no terminal:

bashCopy code

`sass --watch scss/custom.scss:css/bootstrap.css`

Este comando irá monitorar o arquivo `custom.scss` em `scss/` e compilar as alterações em tempo real em `css/bootstrap.css`.

1.  Mantenha o terminal aberto enquanto faz alterações em `custom.scss`. O Sass detectará as alterações e recompilará o arquivo automaticamente.

2.  O Sass exibirá informações no terminal a cada vez que compilar o arquivo, incluindo o tempo que levou para compilar e se houve algum erro. Verifique se não houve erros na saída do terminal.

3.  O arquivo `css/bootstrap.css` foi gerado e pode ser referenciado em seu HTML para incluir o Bootstrap em seu projeto.

## Conclusão
---------

Este guia deve ajudá-lo a compilar o Bootstrap em tempo real usando o Sass em seu projeto. Lembre-se de manter o terminal aberto enquanto o comando `sass` estiver em execução e fazer alterações somente em `custom.scss`.
