# Zingen - Karaokê

Landing page estática para o aplicativo Zingen, criada com HTML e CSS. O projeto apresenta uma página promocional com seções sobre recursos, planos, download e apresentação do app.

## Descrição

Este projeto é um site de apresentação focado em um produto de karaokê chamado **Zingen**. Ele inclui:

- Seção de hero com CTA
- Área de recursos e vantagens do app
- Planos e preços
- Seção de download com botões para stores
- Layout responsivo para desktop e mobile

## Tecnologias

- HTML5
- CSS3
- Design responsivo

## Como usar

1. Abra o arquivo `index.html` no navegador.
2. Alternativamente, execute um servidor local a partir da pasta do projeto e acesse `http://localhost:PORT`.

Exemplo com Python 3:

```bash
cd "c:\Users\cesar\OneDrive\Área de Trabalho\zingen"
python -m http.server 8000
```

## Estrutura do projeto

- `index.html` - página principal do site.
- `assets/` - imagens, ícones e outros recursos estáticos.
- `styles/` - arquivos CSS organizados por componente e utilitários.

### `styles/`

- `global.css` - reset e variáveis globais.
- `utility.css` - utilitários de espaçamento, grid e flex.
- `buttons.css` - estilos de botões.
- `hero.css` - estilos da seção hero.
- `about.css` - estilos da seção sobre o app.
- `features.css` - estilos da seção de funcionalidades.
- `pricing.css` - estilos da seção de planos.
- `download.css` - estilos da seção de download.
- `sections.css` - estilos gerais de seções.
- `social.css` - estilos de elementos sociais.
- `cards.css` - estilos dos cartões de recurso.

## Principais seções

- `#hero` - chamar a atenção do visitante e direcionar para ação.
- `#about` - explicar a proposta do aplicativo.
- `#features` - mostrar vantagens e funcionalidades.
- `#pricing` - apresentar planos de assinatura.
- `#download` - incentivar o download do app.

## Personalização

- Para ajustar cores e tipografia, edite variáveis em `styles/global.css`.
- Para alterar o layout de botões, revise `styles/utility.css` e `styles/buttons.css`.
- Para modificar o conteúdo das seções, atualize `index.html`.

## Observações

- O projeto é uma página estática, sem backend.
- O CSS é carregado a partir de `styles/index.css`, que importa os arquivos do diretório `styles/`.

## Licença

Sem licença definida. Use e modifique de acordo com suas necessidades.
