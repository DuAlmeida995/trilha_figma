# `Group`

Voltar ao [Glossário de Conceitos](README.md) 

## O que é?

O **Group** (ou adivinhem, no português, um Grupo!! Quem diria não é mesmokkkk?) é a forma mais simples de organizar elementos no Figma. Ao contrário do Frame, um grupo não tem propriedades próprias (como cor de fundo ou bordas); ele serve apenas para manter vários objetos juntos, facilitando a movimentação e a organização da lista de camadas.

## Como funciona?

O Grupo é "preguiçoso" e depende inteiramente do que está dentro dele:

- **Tamanho Adaptável:** O tamanho do grupo é sempre exatamente o tamanho da soma dos seus elementos. Se você mover um objeto para longe dentro do grupo, o limite do grupo aumenta automaticamente.
- **Seleção em Bloco:** Ao clicar em qualquer item de um grupo, o Figma seleciona o grupo inteiro. Isso é ótimo para mover logotipos complexos ou ilustrações feitas de várias formas pequenas.
- **Sem Propriedades:** Se você tentar colocar uma cor de fundo em um Grupo, o Figma aplicará essa cor em **todos** os objetos dentro dele individualmente, e não no fundo do "contêiner".

Exemplo bobinho:

Grupo composto por dois retângulos. Ao selecionamos um retângulo, automaticamente selecionamos o outro, assim se mexermos um, mexermos o outro, e vice-versa. (agora que eu vi os retângulos ficaram com a numeração 67, esse número me persegue eu vou ficar louco)

![](assets/group.md)

## Quando usar?

Use Grupos apenas para organização básica. Se você precisar de controle de layout, grids, ou quiser que o fundo tenha uma cor específica, **use sempre um Frame**.

## Formas de criar

- **Atalho principal:** Selecione os objetos e pressione `Ctrl + G` 
- **Desfazer grupo:** Para "quebrar" um grupo e soltar os elementos, pressione `Ctrl + Shift + G`.
- **Menu:** Clique com o botão direito nos elementos selecionados e escolha **Group Selection**.

## Palavras chaves

- `agrupar`, `organização`, `seleção rápida`, `camadas`
