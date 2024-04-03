1. Crie uma pasta e monte um ambiente virtual Python:
>>> Python -m venv producao_hospitalar

2. Ative o ambiente virtual:
>>> .\producao_hospitalar\Scripts\Activate

3. Inicializar o Repositório Git
>>> git init

4. Conectar com um Repositório Remoto
>>> git remote add origin 

5. 
>>> git remote add origin https://github.com/alexsoares4a/producao_hospitalar.git

6. Alterar o usuário e email
>> git config name "alexsoares4a"
>> git config email "alexssonline@gmail.com"

7. Fazer o push
>>> git push origin https://github.com/alexsoares4a/producao_hospitalar.git

8. Atualizar as dependências
>>> pip install -r requirements.txt --upgrade
