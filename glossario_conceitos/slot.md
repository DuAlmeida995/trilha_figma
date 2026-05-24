# `Slot` 

Voltar ao [Glossário de Conceitos](README.md) 

## O que é?

Um **Slot** é um espaço reservado vazio dentro de um Componente.
É como uma caixinha onde no futuro podemos injetar qualquer outro componente que desejamos.

## Como funciona?

A técnica do Slot geralmente envolve os seguintes passos:

- **O Componente Placeholder:** Primeiro, você cria um componente genérico e o chama de algo como `Slot` ou `Placeholder`. Pode ser apenas um quadrado tracejado com Auto Layout.
- **Inclusão no Mestre:** Você pega uma Instância desse `Slot` e coloca dentro do seu Componente Mestre de verdade (por exemplo, dentro de um componente de `Modal` ou `Card`).
- **Instance Swap (Troca de Instância):** Nas configurações do seu componente Mestre, você cria uma propriedade do tipo *Instance Swap* apontando para esse Slot.
- **Injeção de Conteúdo:** Quando você for usar a Instância do Modal na sua tela final, o painel direito do Figma vai permitir que você clique no `Slot` e troque aquele quadrado tracejado por **qualquer outro componente** da sua biblioteca (um formulário, uma imagem, uma lista de botões).

## Por que usar?

O Slot evita a Não-Muito-Legal-Mas-Bem-Conhecida **"Explosão de Variantes"**. 

Imagine que você tem um Modal (aquela janelinha de pop-up). O cabeçalho e o rodapé do Modal são sempre iguais, mas o conteúdo do meio muda muito. Sem slots, você teria que criar uma variante `Modal / Com Formulário`, outra `Modal / Com Imagem`, outra `Modal / Com Aviso`. 

Com a técnica de Slot, você cria apenas **um** componente de Modal. O conteúdo do meio é um Slot livre para a equipe injetar o que precisar na hora de desenhar a tela, mantendo o arquivo limpo e leve.

## Palavras chaves

`slot`, `placeholder`
