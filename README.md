# TaskFlow Desktop

Sistema desktop de gerenciamento de tarefas desenvolvido com Electron, React e TypeScript utilizando arquitetura limpa.

---

# Preview

## Funcionalidades

- Cadastro de tarefas
- Atualização de tarefas
- Exclusão de tarefas
- Persistência local com SQLite
- Arquitetura limpa

---

# Tecnologias

## Frontend

- React
- TypeScript
- TailwindCSS
- Zustand

## Desktop

- Electron
- Electron Vite

## Banco de Dados

- SQLite
- better-sqlite3

## Arquitetura

- Clean Architecture
- SOLID
- Modular Architecture

---

# Estrutura do Projeto

```txt
src/
├── main/
│   ├── modules/
│   ├── shared/
│   └── index.ts
│
├── preload/
│
├── renderer/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── store/
│   └── App.tsx
│
└── shared/
```

---

# Arquitetura

O projeto utiliza Clean Architecture para separar:

- regras de negócio
- infraestrutura
- comunicação IPC
- persistência
- interface gráfica

---

# Roadmap

## MVP

- [] Criar tarefas
- [] Atualizar tarefas
- [] Excluir tarefas
- [] Persistência local

---

## Próximas funcionalidades

- [ ] Categorias
- [ ] Filtros avançados
- [ ] Drag and drop
- [ ] Pomodoro
- [ ] Notificações desktop
- [ ] Exportação CSV
- [ ] Temas
- [ ] Backup automático

---

