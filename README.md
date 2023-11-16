# webutvikling-eksamen-2023
Eksamens oppgave


css:  https://www.youtube.com/watch?v=2lyDv0wOQuQ    for global konfig




body * {
  font-family: 'Roboto', sans-serif;
  display: grid;
  grid-template-columns: auto auto auto;
  grid-template-rows: auto auto auto;
  grid-template-areas: 
    "header header header"
    "body body body"
    "footer footer footer";
}

header {
  grid-area: header;
}

body {
  grid-area: body;
} 

footer {
  grid-area: footer;
}

