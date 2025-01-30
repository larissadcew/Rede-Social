# 🌐 Social Network Platform
![image](docs/networkfoto.png)

Este é um projeto de plataforma de rede social desenvolvido com Django. Ele permite que os usuários criem e compartilhem posts, sigam outros usuários, curtam posts e gerenciem seus perfis.

## ✨ Funcionalidades

- 🔐 **Autenticação de Usuário**: Registro, login e logout de usuários.
- 📝 **Posts**: Criação, edição e visualização de posts.
- 👍 **Curtidas**: Usuários podem curtir ou descurtir posts.
- 👥 **Seguir Usuários**: Siga ou deixe de seguir outros usuários.
- 📄 **Perfis de Usuário**: Visualize e gerencie perfis de usuário.

## 🗂️ Estrutura do Projeto

- **.github/workflows**: Configurações para integração contínua e automação.
- **docs**: Documentação do projeto.
- **network**: Aplicativo principal contendo views, models e templates.
- **project4**: Diretório do projeto Django.
- **Pipfile & Pipfile.lock**: Gerenciamento de dependências com Pipenv.
- **db.sqlite3**: Banco de dados SQLite usado para desenvolvimento.
- **dumydata.py**: Script para gerar dados de teste.
- **manage.py**: Script de gerenciamento do Django.
- **requirements.txt**: Lista de dependências do projeto.



## 🛠️ Instalação

1. **Clone o repositório**:
```bash
   git clone https://github.com/larissadcew/Network-django
   cd Network-django
```

2.Instale as dependências:
```bash
pip install -r requirements.txt
```

3.Realize as migrações do banco de dados:
```bash
python manage.py runserver
```

Acesse a aplicação:
Abra o navegador e vá para http://127.0.0.1:8000/


🚀 Uso
📝 Criar Post: Após o login, crie um novo post.
👍 Curtir Posts: Veja os posts e curta ou descurta conforme desejar.
👥 Seguir Usuários: Siga ou deixe de seguir outros usuários para ver seus posts.
📄 Gerenciar Perfil: Visualize e edite seu perfil de usuário.


