Projeto do curso Pythonando
Projeto web construído com **Django** para gerenciamento de despesas/divisão colaborativa de valores.

## 📌 Sobre

EDIV é uma aplicação desenvolvida em **Python** usando o framework **Django**.  
O projeto possui estrutura típica de um app web com:

- Backend em Django  
- Templates HTML  
- Arquivos estáticos de frontend  
- Organização em apps  

## 🧰 Tecnologias

O projeto foi desenvolvido com as seguintes tecnologias:

- 🐍 Python  
- 🌐 Django  
- 📦 Arquivos estáticos (CSS/JS)  
- HTML/Jinja para templates  
- Git/GitHub para versionamento

## 📂 Estrutura do projeto

O repositório contém:

├── apps/

│ └── ediv/

├── static/

├── templates/

├── manage.py

├── .gitignore


- **apps/ediv/** – app principal da aplicação  
- **static/** – arquivos CSS, JS, imagens  
- **templates/** – arquivos HTML  
- **manage.py** – script de gerenciamento do Django

## 🚀 Instalação

Siga estes passos para rodar o projeto localmente:

### 1. Clone o repositório

```bash
git clone https://github.com/NicolasWanderley98/EDIV.git
cd EDIV
2. Crie um ambiente virtual
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
3. Instale as dependências
pip install django
(Adicione outras dependências quando seu requirements.txt existir — ideal criar um.)

4. Rode as migrations
python manage.py migrate
5. Inicie o servidor
python manage.py runserver
Abra o navegador em http://127.0.0.1:8000.

🧪 Funcionalidades
As funcionalidades atuais incluem (preencha com o que seu APP realmente faz):

📝 Cadastro de itens/valores

💰 Divisão de despesas

📊 Exibição de resultados na interface

🔐 Possível integração com usuários autenticados (se existir)

🧩 Como contribuir
Quer contribuir com o projeto? Siga estes passos:

Faça um fork desse repositório

Crie uma branch com sua feature (git checkout -b minha-feature)

Dê commit nas suas mudanças (git commit -m "feat: descrição da feature")

Envie para o repositório (git push origin minha-feature)

Abra um Pull Request

📄 Licença
Este projeto pode ser licenciado conforme sua escolha (ex.: MIT, GPL etc.).
Adicione um arquivo LICENSE se ainda não existir.
