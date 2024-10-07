### **Ficha Prática I: Introdução à linguagem CSS**  
**Nome:** Gonçalo Garrido  
**Número de Aluno:** A038702  

#### 1. Criar novo documento HTML

Cria um novo documento chamado **css1.html** usando o seguinte código base:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Documento CSS1</title>
  <link rel="stylesheet" type="text/css" href="estilos1.css">
</head>
<body>
  <h1>Título H1</h1>
  <h2>Título H2</h2>
  <h3>Título H3</h3>
  <h4>Título H4</h4>
  <h5>Título H5</h6>
  <h6>Título H6</h6>
  <p>Parágrafo muito curto.</p>
  <p>Outro parágrafo curto.</p>
</body>
</html>
```

#### 2. Associar CSS ao documento HTML

Cria um novo ficheiro **estilos1.css** e define o tipo de letra de todo o documento como Verdana:

```css
body {
  font-family: Verdana;
}
```

Para associar este ficheiro ao HTML, utiliza o seguinte código no cabeçalho do **css1.html**:

```html
<link rel="stylesheet" type="text/css" href="estilos1.css">
```

#### 3. Formatação de texto com CSS

No ficheiro **estilos1.css**, adiciona as seguintes regras:

- Alterar tipos de letra:
```css
h1 { font-family: Arial; }
h2 { font-family: Courier; }
h3 { font-family: Georgia; }
h4 { font-family: 'Times New Roman'; }
h5 { font-family: Trebuchet MS; }
h6 { font-family: Garamond; }
```

- Modificar tamanhos de letra:
```css
h1 { font-size: 10px; }
h2 { font-size: 12px; }
h3 { font-size: 14px; }
h4 { font-size: 18px; }
h5 { font-size: 20px; }
h6 { font-size: 24px; }
```

- Parágrafos com negrito:
```css
p {
  font-size: small;
  font-weight: bold;
}
```

#### 4. Apresentação de texto

- Alinhar títulos:
```css
h2 { text-align: right; font-style: italic; }
h3 { text-align: center; font-style: italic; }
```

- Espaçamento e cores:
```css
h1 { letter-spacing: 0.7em; color: red; background-color: gray; }
h6 { word-spacing: 1.2em; color: lightblue; }
```

Este é o resultado final esperado para a Ficha 1【】.
