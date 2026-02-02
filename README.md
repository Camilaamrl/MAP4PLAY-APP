README.md 


🏀 MAP4PLAY: Mapeamento de Quadras Acessíveis
O MAP4PLAY é uma plataforma desenvolvida para centralizar informações sobre quadras de basquete públicas na cidade de São Paulo, com um diferencial essencial: o foco na acessibilidade para pessoas com deficiência. O projeto visa facilitar o acesso ao esporte, permitindo que usuários encontrem locais adequados para a prática esportiva inclusiva.

🛠️ Tecnologias Utilizadas
O projeto foi construído utilizando práticas modernas de desenvolvimento web:

Linguagem: Python 3.12.2

Framework Web: Django 5.2


Banco de Dados: SQLite (padrão de desenvolvimento) 


Arquitetura: Baseada no padrão MVT (Model-View-Template) do Django 

🚀 Funcionalidades Principais

Listagem e Detalhes: Visualização completa das quadras cadastradas no sistema.


Gestão de Dados: Interface administrativa para cadastro de novas quadras e verificação de infraestrutura física.

Filtro de Acessibilidade: Foco em identificar estruturas adaptadas para garantir a inclusão de todos os atletas.

📂 Estrutura do Projeto
O sistema está organizado em módulos para facilitar a manutenção:


quadras/: Aplicativo principal contendo a lógica de negócio, modelos de dados e templates de interface.


sitequadras/: Configurações centrais do projeto e roteamento de URLs.

## Requisitos 

Python 3.12.2 - Conferir a versão: python --version 

Django 5.2 - Conferir a versão: django-admin –-version 

Git – Conferir a instalação: git -v 

 

## Como rodar o projeto baixado 

Baixar o projeto do GitHub:

    git clone https://github.com/Andreia-m/map4play.git .


Criar o ambiente virtual:  

    python –m venv venv 

 
Ativar o ambiente virtual: 

    venv\Scripts\activate 

 
Instalar as dependências: 

    pip install -r requirements.txt


Executar as migration para criar as tabelas no banco de dados: 

    python manage.py migrate 


Criar o super usuário: 

    python manage.py createsuperuser 
 

Rodar o projeto: 

    python manage.py runserver 

 
Acessar o padrão do Python: 

    http://127.0.0.1:8000/ 


Acessar o sistema administrativo padrão do Django:
    http://127.0.0.1:8000/admin

