# EduPlay — HackTudo 2026

> Time **ALTF4**
> *(nome do app é uma sugestão — troquem à vontade, o README acompanha)*

## O Desafio

> Como criar soluções que permitam o uso pedagógico de dispositivos digitais pessoais, reduzindo distrações e fortalecendo o foco, a autonomia dos estudantes e a mediação dos educadores, sem ampliar a vigilância, a desigualdade ou a sobrecarga das escolas?

O celular hoje é tratado pelas escolas quase sempre como um problema a ser contido — bloqueado, confiscado, proibido. O **EduPlay** parte de outra premissa: o celular já é o dispositivo pessoal mais acessível dos estudantes, e em vez de brigar contra ele, a escola pode ocupá-lo com algo que compita de verdade pela atenção — conteúdo da própria matéria, em formato de jogo.

## A Solução

O **EduPlay** é uma plataforma digital escolar em formato de aplicativo mobile, organizada por matéria, onde o aprendizado acontece através de **jogos e quizzes dinâmicos**, gamificação saudável e interação entre colegas de turma — acessível a qualquer momento, dentro ou fora da escola.

Em vez de restringir o uso do celular, o app dá aos alunos um motivo próprio para usá-lo a favor dos estudos, e aos professores uma ferramenta de incentivo e acompanhamento pedagógico — sem depender de monitoramento ou controle do dispositivo do aluno.

### Funcionalidades principais

- **Trilhas por matéria** — conteúdo, jogos e quizzes organizados de acordo com a disciplina e o que está sendo trabalhado em sala, permitindo que o professor direcione o uso para o que realmente importa naquele momento.
- **Jogos e quizzes dinâmicos** — mecânicas variadas de perguntas e desafios, criados/curados pelos professores, que transformam revisão e fixação de conteúdo em algo ativo em vez de passivo.
- **Ranking especial (gamificação)** — aba dedicada a um ranking dos alunos que mais completam quizzes e jogos, incentivando competitividade saudável e engajamento contínuo com os estudos.
- **Chat interativo da turma** — espaço de conversa entre os alunos de uma mesma turma, para tirar dúvidas, discutir os desafios e criar senso de comunidade em torno do aprendizado.
- **Acesso a qualquer momento** — o app funciona dentro e fora da escola, permitindo que o estudo continue por iniciativa do próprio aluno, no seu tempo e ritmo.
- **Painel do professor** — visão de progresso e engajamento da turma nos quizzes/jogos, servindo como incentivo pedagógico e apoio à mediação, sem expor dados de uso do dispositivo pessoal do aluno.

## Como isso responde ao desafio

| Critério do desafio | Como o EduPlay endereça |
|---|---|
| **Reduzir distrações / fortalecer o foco** | O conteúdo pedagógico compete diretamente pela atenção que hoje vai para redes sociais e jogos genéricos, usando os mesmos gatilhos de engajamento (progresso, ranking, desafio) a favor do estudo. |
| **Autonomia dos estudantes** | Acesso livre a qualquer hora, sem depender de supervisão constante — o aluno escolhe quando e quanto praticar. |
| **Mediação dos educadores** | Professores curam o conteúdo por matéria e acompanham o progresso da turma, sem precisar policiar o uso do celular em sala. |
| **Sem ampliar vigilância** | O app não monitora o dispositivo, localização ou outros aplicativos do aluno — só registra o uso dentro da própria plataforma pedagógica. |
| **Sem ampliar desigualdade** | Funciona em app mobile leve, compatível com aparelhos de entrada, e não exige hardware ou infraestrutura adicional da escola além de internet básica. |
| **Sem sobrecarregar a escola** | Professores reaproveitam conteúdo já planejado em formato de quiz/jogo, sem precisar de novos processos administrativos ou equipe técnica dedicada. |

## Público-alvo

- **Estudantes** do ensino fundamental/médio, como usuários principais do app.
- **Professores**, que criam/curam trilhas de conteúdo por matéria e acompanham o engajamento da turma.
- **Escola**, como ambiente que adota a plataforma como incentivo institucional ao estudo, sem custo de infraestrutura relevante.

## Stack Técnica (proposta)

```
Mobile:        React Native (iOS + Android, um único código-base)
Backend:       API leve (Node.js/Express ou FastAPI) + banco de dados relacional
Autenticação:  Login por escola/turma (professor cria turma, aluno entra com código)
Realtime:      WebSocket para chat da turma
Gamificação:   Serviço de pontuação/ranking desacoplado da lógica de conteúdo
```

> Stack sujeita a ajuste conforme o tempo disponível no hackathon — prioridade é ter um fluxo funcional de ponta a ponta (login → trilha da matéria → quiz → ranking → chat).

## Escopo do MVP (hackathon)

- [ ] Login simples de aluno e professor (por turma/código)
- [ ] Uma matéria com trilha de conteúdo + 1 quiz jogável
- [ ] Ranking da turma atualizado em tempo real
- [ ] Chat básico da turma (texto)
- [ ] Painel simples do professor com progresso dos alunos

## Time

**ALTF4**

---

*Projeto desenvolvido para o HackTudo 2026.*
