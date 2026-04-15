# Plataforma de Gestão de Projetos Técnicos

Protótipo interativo de média fidelidade para uma plataforma de gestão de projetos técnicos, voltada para desenvolvedores e gestores.

## ✨ Destaques

- **Tutorial Interativo**: Tour de boas-vindas em 3 etapas explicando os fluxos de uso
- **2 Fluxos de Criação**: Crie tarefas pelo header ou diretamente nas colunas do Kanban
- **Totalmente Interativo**: Todos os botões, cards e links são clicáveis e funcionais
- **Estado Compartilhado**: Tarefas sincronizadas em todas as páginas
- **Feedback Visual**: Notificações, animações e estados de hover

## 🎯 Funcionalidades Principais

### 🎓 Tutorial de Boas-Vindas

Na primeira visita ao Quadro Kanban, um tutorial interativo de 3 passos explica:
1. Visão geral da plataforma
2. Como usar o Caminho A (botão no header)
3. Como usar o Caminho B (botões nas colunas)

**Reabrir o tutorial**: Clique em "Ver tutorial novamente" no topo da página do Kanban

### Fluxo de Criação de Tarefas (2 Caminhos)

#### **CAMINHO A - Botão Header (Principal)** ⭐
1. Clique no botão "+ Nova Tarefa" no header (canto superior direito)
2. Preencha o formulário no modal:
   - Título da tarefa *
   - Prioridade (Alta, Média, Baixa) *
   - Responsável *
   - Status *
3. Clique em "Criar Tarefa"
4. Receba uma notificação de sucesso
5. A tarefa aparecerá automaticamente no Quadro Kanban na coluna correta

#### **CAMINHO B - Botão por Coluna (Rápido)** ⚡
1. No Quadro Kanban, clique no botão "+" no topo de qualquer coluna
2. O modal abre com o **status pré-preenchido** conforme a coluna selecionada
3. Preencha apenas: Título, Prioridade e Responsável
4. O campo Status já está correto (economiza tempo!)
5. A tarefa é criada automaticamente na coluna correta

### 📋 Visualização de Detalhes

**Clique em qualquer card de tarefa** (em qualquer página) para ver:
- Informações completas da tarefa
- Status atual
- Responsável com avatar
- Prioridade com badge colorido
- Data de criação
- Histórico de atividades

### 🧭 Navegação

Todas as páginas estão funcionais e conectadas:

- **Dashboard**: Visão geral com estatísticas dinâmicas que atualizam em tempo real
- **Backlog**: Lista completa de tarefas em formato de tabela (clique nas linhas para ver detalhes)
- **Quadro Kanban**: Gestão visual com 4 colunas (A Fazer, Em Desenvolvimento, Revisão/Teste, Concluído)
- **Membros**: Equipe do projeto com cards interativos
- **Relatórios**: Análises e métricas visuais

### 🎨 Interatividade

✅ **Elementos Clicáveis:**
- Botão "+ Nova Tarefa" no header
- Botões "+" em cada coluna do Kanban
- Cards de tarefas → Abre modal de detalhes
- Linhas da tabela do Backlog → Abre modal de detalhes
- Links da sidebar → Navegação entre páginas
- Botão "Ver tutorial novamente" → Reabre o tour

✅ **Estados Visuais:**
- Hover em todos os botões, cards e links
- Estado ativo destacado na sidebar
- Animação de entrada nos cards de tarefas
- Transições suaves em todas as interações
- Indicador pulsante de notificações

✅ **Feedback ao Usuário:**
- Notificações toast de sucesso ao criar tarefas
- Notificações de erro se campos obrigatórios não forem preenchidos
- Mensagem de contexto quando criar tarefa por coluna específica
- Estado vazio nas colunas sem tarefas

✅ **Gestão de Estado:**
- Tarefas compartilhadas entre todas as páginas
- Estatísticas atualizadas automaticamente
- Contadores em tempo real nas colunas
- IDs técnicos sequenciais automáticos

## 🚀 Como Testar

1. Acesse o Dashboard para ver estatísticas gerais
2. Vá para o Quadro Kanban
3. Teste criar uma tarefa pelo header
4. Teste criar uma tarefa pelo botão "+" de uma coluna
5. Clique em um card para ver detalhes
6. Navegue para o Backlog e clique em uma linha
7. Explore os Membros e Relatórios

## 📋 Estrutura de Cards

Cada card de tarefa contém:
- **ID técnico** (ex: TEC-101)
- **Título** da tarefa
- **Tag de prioridade** com cor (Alta, Média, Baixa)
- **Avatar** do responsável
- **Nome** do responsável

## 🔄 Próximas Melhorias Possíveis

- Drag and drop entre colunas do Kanban
- Filtros funcionais na barra de filtros
- Edição de tarefas existentes
- Exclusão de tarefas
- Persistência de dados (Supabase)
- Autenticação de usuários
