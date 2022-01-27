Projeot Imersao React - Alura 24012022

Preparando Ambiente

Instalando yarn com npm

npm install --global yarn

Verificando a versao do yarn
yarn --version

Inicializando o yarn no repositorio
1- yarn init -y

Instalando o Next, React, React-Dom
2- yarn add next react react-dom

Importando biblioteca de componetes
2-1 yarn add @skynexui/components

Importando  biblioteca na Page
2-2 import { Box, Button, Text, TextField, Image } from '@skynexui/components';

Ignorar pasta node para o github
3- npx gitignore node

criando pacote de dados criados
4- git add .

salvar pacote de dados alterados na maquina de desenvolvimento
5- git commit -m "escrevaseucomentarioaqui"

adcionar link da pasta criada no github
6- git remote add origin link_da_pasta_github

enviando todas modificacoes para o github
7- git push -u origin master
