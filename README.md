# Soul Kitchen
Site pensado para fornecer receitas culinárias para o cotidiano, buscando facilitar a vida de quem precisa fazer marmitas semanalmente.


Instalação: 
- criar venv;
- pip install -r requirements.txt
- py manage.py collectstatic
- py manage.py runserver

Sobre os arquivos estáticos (css, js etc.): qualquer alteração deve ser feita no arquivo `setup/static`. Após serem alterados os arquivos estáticos, é necessário dar o comando `py manage.py collectstatic`