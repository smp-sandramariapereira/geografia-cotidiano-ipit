# 🌍 Geografia no Cotidiano + IPIT — 3 aulas de 50 minutos

Sequência didática completa para o **Ensino Médio**, com **150 minutos** em três encontros, roteiros detalhados, oito etapas IPIT, formulários digitais editáveis e rubrica formativa.

## Abrir o curso
- [Aplicação web — index.html](index.html) (página estática pronta para abrir no navegador)
- [Plano de desenvolvimento](docs/plano-de-desenvolvimento.md)
- [Cronograma minuto a minuto](docs/cronograma.md)
- [Rubrica formativa](docs/rubrica-avaliacao.md)
- [Projeto integrador](atividades/projeto-integrador.md)

> **GitHub Pages:** o endereço público só deve ser considerado ativo após verificação. Para configurar, abra **Settings → Pages → Build and deployment → Deploy from a branch**, selecione **main** e **/(root)** e salve. Não há confirmação de publicação neste momento.

## Cronograma
| Aula | Etapas IPIT | Duração | Entrega |
|---|---|---:|---|
| 1 — Investigar o território | Descoberta 30 min + Ideação 20 min | 50 min | Croqui, problema, evidências e alternativas |
| 2 — Projetar a solução | Solução 10 + Tecnologia 10 + MVP 10 + Arquitetura 20 | 50 min | Esboço, ferramenta, escopo e plano |
| 3 — Desenvolver e apresentar | Desenvolvimento 25 + Pitch 25 | 50 min | Protótipo testado, pitch e retrospectiva |
| **Total** | **8 etapas** | **150 min** | |

**Questão orientadora:** Como utilizar a Geografia para reconhecer um problema do lugar onde vivemos e propor uma melhoria para a comunidade?

**Produto integrador:** croqui diagnóstico e protótipo de intervenção territorial, com evidências e teste de compreensão por colegas. Papel ou ferramentas digitais opcionais.

## Interface docente
A página possui navegação por aulas e etapas, conteúdo-modelo explicitamente fictício, campos para evidências reais, checklists, progresso, rubrica, registros de equipe, diário, IA e retrospectiva, salvamento automático no **localStorage**, exportações **JSON** e **Markdown**, importação JSON com checagem de esquema, impressão/PDF e confirmação de exclusão.

**Importante:** dados ficam no navegador atual. Não há sincronização, contas, envio remoto ou proteção por autenticação. Faça backup por JSON; não registre informações pessoais de estudantes em dispositivos compartilhados.

## Arquivos
- `index.html` — interface sem dependências remotas
- `design-system.css`, `visual-extras.css` — estilos responsivos
- `professor-preenchido.js` — planejamento docente e fichas com exemplos
- `visual-extras.js` — navegação e armazenamento/exportações
- `assets/diagramas/` — dois esquemas SVG originais
- `docs/` — plano, cronograma, padrão de design, rubrica
- `fichas/` — oito fichas IPIT, acordo, diário, IA, retrospectiva, checklist
- `atividades/` — desafios, exercícios com respostas-modelo e projeto integrador

## Fontes e atribuição
**Fonte documental:** BRASIL. Ministério da Educação. *PNLD 2018: Geografia — Guia de livros didáticos, Ensino Médio*. Brasília, 2017. Resenha da coleção *Geografia no Cotidiano*, **pp. 50–54**.

**Obra resenhada:** MARTINS, Dadá; BIGOTTO, Francisco; VITIELLO, Márcio. *Geografia no Cotidiano*. Base Editorial, 2016.

**Metodologia IPIT:** Sandra Maria Pereira — [IPIT_origin](https://github.com/smp-sandramariapereira/IPIT_origin). **Referência de interface:** [projeto-powerbi-ipit](https://github.com/smp-sandramariapereira/projeto-powerbi-ipit).

A fonte PNLD é uma **resenha da coleção**, e não o conteúdo integral de um capítulo. Todas as situações e propostas didáticas deste projeto foram elaboradas como adaptações pedagógicas e não devem ser atribuídas literalmente ao livro.

## Limites
A interface e os arquivos foram criados no repositório. Testes instrumentados de ponta a ponta da página e confirmação de GitHub Pages ativo **ainda não foram realizados**. A duração dos pitches depende do número de equipes; ajustar formato por estações se necessário.
