# Projeto: Implantação e Governança de TI — GLPI + Grafana

## Visão Geral

Projeto de estruturação completa da área de TI em empresa sem gestão formal de tecnologia.
Partindo do zero, foram implantados processos, ferramentas e indicadores que transformaram
a operação de TI em uma área mensurável, organizada e orientada a dados.

---

## Contexto e Problema

A empresa possuía **gestão de TI inexistente**: sem controle de chamados, sem visibilidade
de demandas, sem métricas de desempenho e sem processos formalizados. Solicitações eram
tratadas de forma reativa e informal, sem rastreabilidade ou histórico.

---

## Solução Implementada

### 1. Implantação do GLPI (Service Desk)
- Instalação e configuração completa da plataforma
- Cadastro de perfis de acesso por função (técnico, gestor, usuário)
- Criação de categorias de chamados por tipo de demanda
- Configuração de regras de negócio e fluxos de atendimento
- Definição de prioridades: Baixa, Média, Alta, Muito Alta, Crítica
- Mapeamento de setores (Contabilidade, RH, Fiscal e demais áreas)

### 2. Dashboard de Indicadores — Grafana
Criação de painel gerencial com visões em tempo real:

| Indicador | Descrição |
|---|---|
| Chamados Abertos | Volume atual de demandas em andamento |
| Chamados Solucionados | Atendimentos concluídos no período |
| Chamados Fechados | Encerrados com validação do usuário |
| Chamados Pendentes | Aguardando ação ou informação |
| Total Geral | Consolidado do período |
| Chamados por Status | Distribuição percentual por situação |
| Chamados por Prioridade | Mapa de criticidade das demandas |
| Chamados por Tipo | Categorização das solicitações |
| Tendência 30 dias | Evolução diária de abertura de chamados |
| Ranking de Técnicos | Performance por profissional |
| Ranking de Setores | Setores com maior volume de demandas |
| Chamados em Aberto por Técnico | Distribuição atual da fila |

---

## Resultados

- Visibilidade total das demandas de TI pela gestão
- Identificação dos setores com maior carga de suporte
- Rastreabilidade completa do histórico de atendimentos
- Base de dados para tomada de decisão sobre dimensionamento da equipe
- Fundação para implantação futura de SLAs e acordos de nível de serviço

---

## Tecnologias Utilizadas

- **GLPI** — Gestão de chamados e service desk
- **Grafana** — Visualização de dados e dashboards gerenciais
- **SQL** — Queries para extração e transformação dos dados
- **MySQL/MariaDB** — Banco de dados do GLPI

---

##Próximos Passos

- [ ] Indicador de Tempo Médio de Resolução (TMR) por técnico e categoria
- [ ] Painel de SLA cumprido x violado
- [ ] Análise de chamados recorrentes por categoria (identificação de gargalos)
- [ ] Automação de relatórios periódicos via Python
- [ ] Implantação de base de conhecimento (FAQ interno)

---

## Sobre

Projeto desenvolvido por profissional com mais de 20 anos de experiência em gestão de TI,
incluindo atuação como Diretor de TI e Gerente LATAM. MBA em Gestão de Projetos.
Especialização em governança, infraestrutura e implantação de processos de TI.

---

*Projeto em andamento — atualizado continuamente conforme evolução da implantação.*
