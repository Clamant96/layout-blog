# CONFIGURANDO MEU PROJETO CSS

## IMPORTANDO FONTS (GOOGLE FONTS)
* Aessar o link: https://fonts.google.com/
* Escolha uma font: https://fonts.google.com/specimen/Vollkorn?preview.text_type=custom
* Selecione as forças dessa fonte
* Clique em "import" que fica no lado inferior direito
* Copie a URL: @import url('https://fonts.googleapis.com/css2?family=Vollkorn:wght@400;500;600;700;800;900&display=swap');
```css
@import url('https://fonts.googleapis.com/css2?family=Amaranth:wght@400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Titillium+Web:wght@200;300;400;600;700;900&display=swap');
```

## CONFIGURANDO VALORES PADROES PARA SEU PROJETO
* Dentro de seu arquivo .css, faça os seguintes comandos

```css
/* DEIXANDO A MARGIN E PADDING DE SEU WINDOW ZERADO */
* {
    padding: 0;
    margin: 0;
}

/* APLICANDO CONFIGURACOES GLOBAIS PARA SEU PROJETO */
html, body {
    height: 100%;

    font-family: 'Titillium Web', sans-serif;
    font-size: 17px;
}

/* APLICANDO CONFIGURACOES GLOBAIS PARA O H1 */
h1 {
    font-family: 'Amaranth', sans-serif;
    font-size: 44px;

    color: var(--text-title);
}

/* APLICANDO CONFIGURACOES GLOBAIS PARA O H2 */
h2 {
    font-family: 'Amaranth', sans-serif;
    font-size: 28px;

    color: var(--text-title);
}

/* APLICANDO CONFIGURACOES GLOBAIS PARA O H3 */
h3 {
    font-size: 14px;
    font-weight: 400;

    color: var(--text-author);
}

/* APLICANDO CONFIGURACOES GLOBAIS PARA O P */
p {
    color: var(--text-default);
}

/* APLICANDO CONFIGURACOES GLOBAIS PARA O HR */
hr {
    width: 85%;
    height: auto;

    margin-left: 5%;
    
    border-top: 0px solid var(--border-style-search);
    border-left: 0px solid var(--border-style-search);
    border-right: 0px solid var(--border-style-search);
    border-bottom: 1px solid var(--border-style-search);
}

/* CRIANDO MACROS/VARIAVEIS PARA REUTILIZACAO DE CORES */
:root {
    --text-default: #262626;
    --text-title: #303030;
    --text-author: #00000080;
    --text-white: #f1f1f1;

    --border-style-search: #e8e8e8;

    --background-color-button: #3bc;
}
```