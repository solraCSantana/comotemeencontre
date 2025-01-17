# Projeto: COMO TE ME ENCONTRE 

Este projeto consiste na criação de um jogo dinâmico, divertido e envolvente com o intuito de avalaiar os conhecimentos e aprendizados no trabalho de conclusão de curso Para o curso de Imagem e Som da UFSCar. 
O "Como Te(Me) Encontrei" é um jogo de quebra-cabeça envolvente, onde o jogador, dotado da habilidade de identificar mentiras, revive momentos felizes ao lado de seu fiel companheiro, o gatinho Oliver. Porém, com o misterioso desaparecimento de Oliver, você será desafiado a enfrentar suas próprias inseguranças e a questionar a sinceridade das pessoas ao seu redor. Será que alguém mais tentará enganá-lo enquanto você luta para reencontrar o seu amigo?

## Pré-requisitos
Antes de começar, verifique se você tem as seguintes ferramentas instaladas no seu computador:
- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)
- Um editor de código como o [VS Code](https://code.visualstudio.com/).

## Configuração do Ambiente
# Configuração do Ambiente

## 1. Pré-requisitos
Certifique-se de que os seguintes itens estejam instalados no seu sistema:
- [Node.js](https://nodejs.org/) (versão mínima recomendada: 14.x ou superior)
- [Git](https://git-scm.com/)
- Editor de código como [Visual Studio Code](https://code.visualstudio.com/)

## 2. Clonando o Repositório
Para iniciar, faça o clone do repositório do projeto:
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

## 3. Estrutura do Projeto
O projeto segue a seguinte estrutura de diretórios e arquivos:

- `public/`: Contém os arquivos HTML do projeto:
  - `index.html`: Página inicial do site.
  - `about.html`: Página "Quem Somos".
  - `contactenos.html`: Página de contato.
- `src/`: Diretório principal para os recursos:
  - `css/`: Contém os estilos CSS.
    - `styles.css`: Folha de estilo principal.
    - `imagens/`: Diretório para imagens do projeto.
  - `js/`: Scripts JavaScript para funcionalidades do projeto.
    - `index.js`: Arquivo JavaScript principal.
    - `app.js`: Outros scripts auxiliares.
- `.babelrc`: Configuração para Babel, caso haja necessidade de transpilar JavaScript moderno.
- `webpack.config.js`: Configuração do Webpack para empacotar recursos.
- `.gitignore`: Lista de arquivos e diretórios ignorados pelo Git.
- `README.md`: Documentação do projeto.
- `package.json`: Gerenciador de dependências e metadados do projeto.

## 4. Instalando Dependências
Na raiz do projeto, execute o seguinte comando para instalar as dependências:
```bash
npm install
```

## 5. Executando o Projeto
Para rodar o projeto localmente, siga os passos abaixo:

1. Use uma extensão como **Live Server** no VS Code para iniciar um servidor local.
2. Execute o comando abaixo, se houver um script configurado no `package.json`:
   ```bash
   npm start
   ```
3. Acesse o projeto no navegador, geralmente disponível em `http://localhost:5500`.

## 6. Build para Produção
Se necessário empacotar os arquivos para produção, execute:
```bash
npm run build
```
Os arquivos otimizados serão gerados no diretório `dist/`.
### 1. Clonando o Repositório
Use o comando abaixo para clonar o repositório para o seu computador:
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
