#  To-Do List Moderno

Uma aplicação web simples e elegante para gerenciar suas tarefas diárias, construída com Flask e SQLite.

##  Funcionalidades

-  Adicionar novas tarefas
-  Marcar tarefas como concluídas
- 🗑 Excluir tarefas
-  Armazenamento persistente com SQLite
-  Design responsivo e moderno

##  Como executar

1. **Clone o repositório**
   ```bash
   git clone <url-do-repositorio>
   cd todo-list
   ```

2. **Crie um ambiente virtual**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # ou
   venv\Scripts\activate     # Windows
   ```

3. **Instale as dependências**
   ```bash
   pip install flask
   ```

4. **Execute a aplicação**
   ```bash
   python app.py
   ```

5. **Abra no navegador**
   ```
   http://localhost:5000
   ```

##  Estrutura do Projeto

```
todo-list/
├── app.py              # Aplicação principal Flask
├── requirements.txt    # Dependências
├── database/
│   └── todo.db        # Banco de dados SQLite (criado automaticamente)
├── static/
│   └── style.css      # Estilos CSS
└── templates/
    └── index.html     # Template HTML
```

##  Tecnologias

- **Backend**: Flask (Python)
- **Banco de dados**: SQLite
- **Frontend**: HTML, CSS, JavaScript
- **Ícones**: Font Awesome

##  Preview

Interface moderna com design glassmorphism, gradientes e animações suaves.

---

Feito usando Flask 👍
