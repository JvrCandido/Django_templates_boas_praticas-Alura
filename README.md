# 🛰️ Alura Space

Projeto desenvolvido durante as aulas da **Alura** — um site em **Django** para exibir uma galeria de imagens do espaço, com páginas dinâmicas e estrutura organizada em apps.

---

## 📂 Estrutura do Projeto

```
alura_space/
├── manage.py
├── requirements.txt
├── galeria/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   ├── views.py
│   └── migrations/
├── setup/
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── static/
│       └── assets/
│           ├── imagens/
│           ├── logo/
│           ├── favicon/
│           └── ícones/
└── .gitignore
```

---

## ⚙️ Instalação

1. **Clone ou extraia o projeto**
   ```bash
   git clone <https://github.com/JvrCandido/Django_templates_boas_praticas-Alura>
   cd Django_templates_boas_praticas-Alura
   ```

2. **Crie e ative o ambiente virtual**
   ```bash
   python -m venv venv
   source venv/bin/activate     # macOS / Linux
   venv\Scripts\activate      # Windows
   ```

3. **Instale as dependências**
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute as migrações**
   ```bash
   python manage.py migrate
   ```

5. **Rode o servidor local**
   ```bash
   python manage.py runserver
   ```

6. **Acesse no navegador:**
   ```
   http://127.0.0.1:8000/
   ```

---

## 🧠 Tecnologias utilizadas
- Python 3
- Django
- HTML / CSS
- SQLite (banco de dados padrão)

---

## 🧑‍💻 Autor
Projeto criado com base nas aulas da [Alura](https://www.alura.com.br/).
Adaptado e executado por **João Victor Rocha Cândido**.
