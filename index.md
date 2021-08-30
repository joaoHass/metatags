# Meta tags & formatação do < head >

##  Informações

**Metatags**. Elas **formatam o snippet** que aparece quando você cola o link **em lugares que suportam o protocólo [OpenGraph](https://ogp.me/)** (whatsapp, messenger, slack, etc.).

**Exemplo:**
![exemplo](https://ahrefs.com/blog/wp-content/uploads/2020/01/og-tags-1.png)

### ~ Favicon

- Dimensões de **16 x 16 pixels**

#### ~ Título (_og:title_)

- Focar em **precisão**, **valor** e **clicabilidade**
- Mantenha **curto**. Entre **40 e 60 caracteres**
- **Não inclua** o nome do site

#### ~ Descrição (_og:description_ , _twitter:description_):

- Usar para **complementar** o título
- Manter **curto**. O facebook recomenda de **2 a 4 sentenças**

#### ~ Imagem (_og:image_, _twitter:image_)


- **De preferência**, com razão de **1.91:1**
- **No mínimo**, com dimensões **1200x630**

---

## Implementando no < head >

 **Obrigatório**

```html
<!-- = METATAGS = -->

<!-- favicon -->
<link rel="shortcut icon" href="./favicon.ico" type="image/x-icon" />

<!-- url -->
<link rel="canonical" href="http://..." />
<meta property="og:url" content="http://..." />
<meta name="twitter:url" content="http://..." />

<!-- title -->
<meta property="og:title" content="Title" />

<!-- description -->
<meta name="description" content="..." />
<meta property="og:description" content="..." />
<meta name="twitter:description" content="..." />

<!-- image -->
<meta property="og:image" content="http://..." />
<meta name="twitter:image" content="http://..." />

<!-- misc -->
<meta property="og:locale" content="pt_BR" />
<meta name="theme-color" content="#a52a2a" />
```

**Opcional**

```html
<!-- robots -->
<meta name="robots" content="index, follow" />
```
