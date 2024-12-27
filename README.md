# Página inicial de Produto Whey Protein NutraBio

Este repositório contém o código HTML e CSS de uma página inicial de produto para o **Whey Protein NutraBio**. A estrutura da página foi criada com base em um protótipo desenvolvido no **Figma**, visando proporcionar uma experiência de usuário fluida e visualmente atraente. O objetivo é promover o produto de forma eficaz, destacando seus benefícios e incentivando a ação de compra.

### Protótipo do Figma

![prototipo](https://github.com/user-attachments/assets/b142f930-055e-423f-b2b8-989bdd09a5a2)

---------

### Página Criada

![pagina](https://github.com/user-attachments/assets/731def3e-11d2-4d50-9704-0f6e362b1f40)



## Estrutura

A página é composta por dois arquivos principais:

- **HTML (index.html)**: A estrutura da página, com o conteúdo principal.
- **CSS (style.css)**: Estilos e animações que dão forma à página.

### HTML

O arquivo HTML define a estrutura da página, contendo os seguintes elementos:

1. **Cabeçalho (head)**:
   - Define o título da página como "Whey Protein NutraBio".
   - Inclui o arquivo de estilo CSS (`style.css`).
   - Configurações de charset e viewport para garantir compatibilidade e responsividade.

2. **Corpo da página (body)**:
   - **Container Principal** (`.container`): Organiza e centraliza o conteúdo da página.
   - **Seção de Conteúdo Principal** (`main`):
     - **Box de Promessa** (`.box-promisse`): Contém o título, uma promessa de resultado e um botão de ação "Compre Agora".
     - **Box de Imagem** (`.box-img`): Exibe a imagem do produto com uma animação de entrada.

### CSS

O arquivo CSS define o estilo visual da página, com as seguintes características:

1. **Variáveis de Cores**:
   - Utiliza cores personalizadas para dar uma identidade única ao design:
     - `--primary`: Tom de verde (#B1C548).
     - `--secundary`: Tom de verde claro (#B5D024).
     - `--background`: Cor de fundo (#EEF2D6).
     - `--black`: Cor do texto principal (#1B1E0A).
     - `--white`: Cor para elementos de fundo claros (#F6F9EB).

2. **Estilo Geral**:
   - A página é limpa e sem bordas ou margens padrões.
   - O corpo utiliza a fonte `Arial, Helvetica, sans-serif` e o fundo tem a cor definida pela variável `--background`.

3. **Layout**:
   - O layout usa **Flexbox** para organizar os elementos de forma eficiente.
   - A estrutura é adaptável, com uma distribuição em colunas para desktop e em uma coluna única para dispositivos móveis (menor ou igual a 760px de largura).

4. **Animações**:
   - A imagem do produto possui uma animação suave de deslizamento (da direita para a esquerda), utilizando `@keyframes`.

5. **Botões**:
   - O botão "Compre Agora" tem um estilo vibrante com um fundo verde (`--primary`) e borda preta.
   - Quando o usuário passa o mouse sobre o botão, ele muda para um tom de verde mais claro (`--secundary`).

### Responsividade

- **Dispositivos Móveis**: A página se adapta automaticamente para telas menores, ajustando a disposição dos elementos para uma visualização vertical.
  - A direção da flexbox é alterada para `column` em telas menores, garantindo uma experiência de leitura confortável.
  - O `padding` é ajustado para garantir que o conteúdo não fique muito apertado nas bordas da tela.
