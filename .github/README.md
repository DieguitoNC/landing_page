# Introducao ao HTML
https://efficient-sloth-d85.notion.site/Principais-elementos-HTML-da8b750fee5b49f2923fdc35b1c921fc?pvs=25#7ad91c5061194a4989b1d6c4c1f0f853


# Estruturando o projeto
## H1....h6
Sao os cabecalhos das paginas
## Div
Serve para criar blocos
## img
Serve para colocar imagem



# Posicao dos elementos da tela
## a 
- Serve para criar link
- mas ele tem display inline

# Apresentação e posição dos elementos na tela
## strong
- Vai deixar em negrito
## span - Container generico
- Cria um container generico que podemos estilizar com CSS

# Aplicando fontes customizadas e iniciando o CSS
- Colar o link do html na pagina html e dps utilzar a fonte
# Cores e fontes
- Basicamente temos a fonte normal e a bold

# Alinhando textos e elementos - CSS
## Alinhar textos 
- Vai usar text-align: center
## Alinhar bloco
- Vai colocar margin: auto
## Chamar pelo ID
- Vai colocar # nome (junto)
# Trabalhando com espacamentos
- Aqui eu usei margin para definir o espacamento, conforme algum ponto de referencial, margin
## Concatenacao para chamar elementos adjunts anteriores
```
#footer a + a {

  margin-left: 28px;

}
```

# Bordas e classificacoes de elementos
## Class
- A gente usa quando vao ter alguns elementos repetidos com o mesmo nome e chamamos com . na frente do nome
```
.line {

  border: 1px solid #ECEFF2;

  width: 568px;

  margin: auto;

}
```

# Posicionando Elementos
## Position Fixed
- Vai criar uma camada que fica superior aos outros
```
#balls {

  position: fixed;

  right: 0px;

  bottom: 0px;

}
```