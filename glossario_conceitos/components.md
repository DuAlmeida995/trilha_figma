# `Component` (Componente)

Voltar ao [Glossário de Conceitos](README.md) 

## O que é?

Um **Componente** é um elemento de interface (como um botão, um ícone ou um card de personagem tipo sla aqueles de The Sims ou algo assim) que pode ser reutilizado em vários lugares do seu design. Ele é o pilar central para manter projetos grandes organizados e fáceis de dar manutenção.

Para meus programadores de padrão e fãs do Professor Coutinho, um compomente mestre funciona como uma Classe da computação orientada a objetos. Dá pra reconhecer esses carinhas no painel de camadas pelo ícone de quatro losangos roxos (❖).

Exemplo:

Temos o componente linha_celula, e abaixo dele, instâncias do mesmo

![](assets/components1.png)

## Como funciona?

O poder do componente está na replicação e na herança:

- **Componente Mestre (Main Component):** É o original. Qualquer alteração de cor, tamanho ou estrutura que você fizer nele será propagada automaticamente para todas as suas cópias.
- **Instâncias (Instances):** São as cópias geradas a partir do Mestre (como os "Objetos" instanciados de uma "Classe"). Se você mudar a cor do Mestre, todas as Instâncias mudam de cor.
- **Overrides (Sobrescritas):** Apesar de herdarem as características do Mestre, você pode alterar propriedades específicas de uma Instância (como mudar apenas o texto de "Jogar" para "Sair") sem afetar o Mestre e nem as outras Instâncias.

## Por que usar?

Imagine que o seu jogo tem 30 bilhões e 3 unidades de telas diferentes, todas usando o mesmo botão de "Voltar". Se um dia a equipe decidir que o botão de "Voltar" precisa ser maior e vermelho, você não precisará editar as 30 bilhões e 3 unidades de telas! Olha que coisa boa :D. Basta alterar o Componente Mestre uma única vez, e o projeto inteiro se atualiza num piscar de olhos.
Ai você vai poder pegar o tempo que você economizou para fazer qualquer outra coisa que não seja estudar para a prova que você vai ter quando a greve da USP se encerrar, legal né?

*OBS:* Para as pessoas do futuro (vulgo Those Who Come After), tô escrevendo isso enquanto rola uma greve na USP e em outras estaduais de SP, já vai fazer quase 1 mês que não temos aula, em teoria isso parece legal mas ficar sem ver os eachamigos é meio deprimente,
valorize os seus eachamigos pessoa que estiver lendo!

## Formas de criar

- **Atalho principal:** Selecione o Frame ou Grupo que deseja transformar e pressione `Ctrl + Alt + K` (ou `Cmd + Option + K`).
- **Menu superior:** Clique no ícone de quatro losangos (❖) na barra de ferramentas superior do Figma.
- **Menu de contexto:** Clique com o botão direito na seleção e escolha **Create component**.

## Palavras chaves

`componente`, `reutilização`, `classe`, `mestre`, `instância`, 
