# Cordel Moderno

Este projeto é uma página web simples que apresenta o poema "Cordel Moderno" de Milton Duarte. O objetivo é demonstrar a estrutura básica de um site utilizando HTML e CSS, com foco em exibir o conteúdo de forma clara e organizada.

## Estrutura do Projeto

O projeto é composto por:

- **HTML**: Estrutura principal do site.
- **CSS**: Estilo visual (deve ser criado no arquivo `style.css`).

### Arquivos

1. `index.html`: Arquivo principal contendo a estrutura HTML do site.
2. `style.css`: Arquivo de estilos que deve ser criado para estilizar a página.

## Funcionalidades

- Exibição de um poema no estilo de cordel com seções alternadas.
- Uso de links externos e internos.
- Destaque para cabeçalhos, parágrafos e rodapé.

## Estrutura HTML

A estrutura da página é dividida em:

1. **Cabeçalho (`<header>`)**: Contém o título do poema e o autor com um link externo para mais informações.
2. **Seções (`<section>`)**:
   - `class="normal"`: Contém texto normal do poema.
   - `class="imagem"`: Contém texto do poema acompanhado de estilos específicos.
3. **Rodapé (`<footer>`)**: Informações de créditos e link para o perfil da autora do site.

## Requisitos

Certifique-se de criar o arquivo `style.css` com estilos apropriados para as classes e elementos usados no HTML.

### Exemplos de Estilo CSS

Aqui estão algumas sugestões para o arquivo `style.css`:

```css
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #fdf8e4;
    color: #333;
}

header {
    text-align: center;
    background-color: #ffc107;
    color: #000;
    padding: 20px;
}

section {
    padding: 20px;
    margin: 10px auto;
    max-width: 800px;
}

section.normal {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

section.imagem {
    background-color: #ffefd5;
    border: 1px solid #ffc107;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #ffc107;
    color: #000;
}

footer a {
    color: #000;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}
```

## Como Executar

1. Clone o repositório ou copie os arquivos.
2. Abra o arquivo `index.html` em um navegador.
3. Certifique-se de que o arquivo `style.css` esteja no mesmo diretório que o `index.html` para aplicar os estilos.

## Créditos

- Poema: [Milton Duarte](https://www.recantodasletras.com.br/poesias/3186743).
- Site criado por: [Jéssica](https://github.com/jessiepsx) como parte do curso *Curso em Vídeo*.
