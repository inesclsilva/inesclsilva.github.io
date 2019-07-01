# Inês Silva — DXD | Linguagens e tecnologias digitais 2019

Para este projeto decidi usar o que realizei no primeiro semestre e tentar o desafio de "refazê-lo" com jekyll. Melhorei o html para o dividir nos diversos includes e layouts, e fui transformando o css em scss. 

## Tecnologias usadas:

### Flexbox:
* Usei flexbox no interior dos posts, para poder ter imagens de diferentes larguras e controlar o seu alinhamento e "wrapping". Assim, não é necessário estar a controlar (ou a "simular") esse wrapping com media queries, mas continuo a ter a liberdade de alterar a width de cada elemento nos diversos breakpoints. Na homepage usei o float porque o objetivo é ter os projetos 2 a 2 e depois passar para apenas 1 por linha, e tal não justifica o uso de flexbox. 

### Animações e transições:
* Usei transitions para suavizar o hover nos projetos, de forma muito simples, e também nos dois links "⟶ Get to know me" e "⟶ Check out my projects". Para estes links, as transitions foram usadas apenas para controlar a "entrada" na página.
* Usei uma pequena animação no footer como "self-branding", presente em todas as páginas.

### SCSS:
* Usei variáveis para fonts e cores porque são os elementos que mais se repetem. Por exemplo, margens e paddings nem sempre são iguais, portanto escolhi não os incluir como varáveis.
