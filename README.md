# Teste Técnico

Olá! Este é o desafio técnico da UpCities.

Não existe resposta certa aqui. Existe um problema real, dados do jeito que a prefeitura entrega, e a expectativa de que você tome decisões e saiba defendê-las.

## Cenário

A prefeitura de Serra Nova (município fictício) mantém a lista de espera por vaga em creche numa planilha que a Secretaria Municipal de Educação atualiza na mão.

A ordem dessa fila segue critérios previstos em decreto municipal — deficiência, renda familiar, irmão já matriculado, distância da unidade. Na prática, cada servidor aplica do seu jeito.

Quando a mãe liga perguntando em que posição a criança está, ninguém consegue responder com segurança. A prefeitura já foi acionada judicialmente duas vezes por causa disso e, nas duas, não conseguiu demonstrar como a fila tinha sido ordenada.

A secretaria entregou o que tinha: a planilha atual, o texto do decreto e o cadastro das unidades.

## O problema

**Faça com que a secretaria consiga manter essa fila e responder ao cidadão.**

Duas coisas precisam ser possíveis:

1. A secretaria colocar uma criança na fila e ver a fila ordenada.
2. O cidadão saber sua posição — e a secretaria saber explicar por que ele está ali.

O resto é com você.

## O que está neste repositório

| Arquivo | O que é |
| --- | --- |
| `dados/inscricoes.xlsx` | A planilha da secretaria, ~810 inscrições |
| `dados/unidades.csv` | Cadastro das unidades: bairro, coordenadas e vagas |
| `docs/decreto-municipal.md` | Decreto nº 4.187/2026, com os critérios |

Os dados são fictícios, mas foram construídos a partir de como esse tipo de base costuma chegar até nós.

## Entregável

Um repositório com o que você construiu rodando, e um README.

Stack e arquitetura são inteiramente sua escolha. O formato pode ser API, interface web, agente/chatbot, entre outros. O que fizer mais sentido pra você. Pode inclusive ser mais de um.

> Só uma restrição: **não vale entregar só CLI.** A secretaria e o cidadão não usam terminal.

### O que escrever no README

Queremos entender:

- o que você construiu
- por que construiu assim
- o que decidiu deixar de fora, e por quê
- onde a sua solução falha
- o que você faria com mais tempo

### Como entregar

Repositório no GitHub. Se a solução também estiver acessível de algum jeito, seja um endereço na web, um bot num mensageiro ou um app, deixe o acesso no README. Assim a gente consegue usar sem montar nada.

Se a entrega for só o repositório, **descreva no README como rodar**: dependências, variáveis de ambiente, comandos. A gente precisa conseguir subir na nossa máquina pra avaliar o que você fez.

## Como avaliamos

Três critérios, com peso equivalente:

| Critério | O que olhamos |
| --- | --- |
| **Capacidade de implementação** | O que você entregou funciona, é legível, e outra pessoa consegue continuar de onde você parou. |
| **Capacidade de integração** | Como as partes conversam entre si e com o que veio de fora — inclusive com o dado do jeito que a prefeitura mandou. |
| **Capacidade de resolução de problema** | Capacidade de analisar o problema, identificar sua causa e tomar decisões práticas para solucioná-lo de forma eficiente. |

Não avaliamos por checklist de funcionalidades. Avaliamos as decisões que você tomou.

## Dúvidas

Qualquer dúvida, é só chamar.

Boa sorte.
