# `Auto Layout`

Voltar ao [Glossário de Conceitos](README.md) 

## O que é?

O **Auto Layout** é meio que um superpoder que você adiciona a um Frame, com ele podendo ditar como os elementos dentro desse Frame devem se comportar, se organizar e se redimensionar automaticamente.

Para qualquer pessoa que já escreveu uma linha de CSS na vida: **:O :O :O :O o Auto Layout é literalmente o Flexbox dentro do Figma. :O :O :O :O**

*Dica: Você sabe que um Frame tem Auto Layout ativado quando o ícone dele no painel de camadas muda de um jogo da velha (#) para duas barrinhas paralelas.*

![][assets/auto_layout0.png)

## Como funciona?

Quando você ativa o Auto Layout em um Frame, você para de arrastar os elementos livremente e passa a controlá-los por regras lógicas no painel direito:

- **Direção (Direction):** Define se os itens internos vão ficar empilhados na Vertical (uma lista) ou na Horizontal (um menu lateral), ou ainda se vão quebrar a linha automaticamente (Wrap).
- **Espaçamento (Gap):** Define a distância exata em pixels entre cada item. Se você apagar um item no meio da lista, os outros sobem automaticamente para preencher o buraco.
- **Padding:** Define o espaço entre a borda do Frame e o conteúdo dentro dele.
- **Redimensionamento (Resizing):** Você pode definir se o elemento deve ter um tamanho Fixo (`Fixed`), se deve "abraçar" o conteúdo e crescer junto com o texto (`Hug contents`) ou se deve se esticar para preencher todo o espaço livre (`Fill container`).

## Por que usar?

Se você criar um botão comum e mudar o texto de "OK" para "Confirmar Transação", o texto vai vazar para fora do botão, o que convenhamos que é meio paia né. Agora, se você criar esse mesmo botão usando Auto Layout, a caixa do botão vai crescer automaticamente para acomodar o novo texto, mantendo as margens (paddings) perfeitinhas mas não complicadas,
ao contrário da música Mulher de Fases dos Raimundos

O auto layout é bem importante para criar interfaces responsivas (que funcionam tanto em monitores ultrawide quanto em telas de celular) e para entregar um design que os programadores consigam traduzir para o código sem dor de cabeça.

## Formas de criar

- **O Atalho Gigatonico:** Selecione os elementos que você quer organizar e pressione `Shift + A`. O Figma colocará todos eles dentro de um novo Frame com Auto Layout ativado.
- **Pelo Painel:** Selecione um Frame existente e, no painel direito, clique no botão `+` na seção **Auto Layout**.
- **Para remover:** Selecione o Frame e pressione `Alt + Shift + A` (ou clique no `-` no painel direito).

## Palavras chaves

`auto layout`, `flexbox`, `responsivo`, `redimensionamento`, `alinhamento`
