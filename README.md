# Smart Routine Agent

Sistema que organiza automaticamente a agenda semanal com base em 
horários disponíveis, tarefas e prioridades.

## Problema
Organizar rotina de estudos, projetos e compromissos manualmente é 
inconsistente e difícil de manter ao longo do tempo.

## Solução
Um agente que lê sua rotina fixa, identifica horários livres e monta 
uma agenda semanal otimizada automaticamente.

## Tecnologias
- Python 3
- Flask
- HTML / CSS
- JSON

## Funcionalidades

### ✅ MVP (em desenvolvimento)
- Leitura de horários fixos via JSON
- Identificação de horários livres
- Cadastro de tarefas com prioridade e duração
- Geração automática da agenda semanal
- Interface web para interação

### 🔜 Versão 2 — Planejamento inteligente
- Ajuste automático da agenda
- Redistribuição de tarefas não concluídas
- Controle de carga horária diária

### 🔜 Versão 3 — Integração com IA
- Comandos em linguagem natural
- Sugestões inteligentes de organização

### 🔜 Versão 4 — Sistema completo
- Integração com Google Calendar
- Banco de dados (PostgreSQL)

## Estrutura do Projeto
\```
smart_routine_agent/
├── app.py              # Servidor Flask e rotas
├── data/
│   ├── rotina_fixa.json
│   └── tarefas.json
├── logic/
│   ├── alocador.py     # Lógica de alocação de tarefas
│   └── horarios.py     # Identificação de horários livres
└── templates/
    └── index.html
\```

## Como Rodar

\```bash
# Clone o repositório
git clone https://github.com/Barcelos-Dev/smart_routine_agent.git
cd smart_routine_agent

# Instale as dependências
pip install flask

# Execute
python app.py
\```
