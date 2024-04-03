1. Crie uma pasta e monte um ambiente virtual Python:
>>> Python -m venv producao_hospitalar

2. Ative o ambiente virtual:
>>> .\producao_hospitalar\Scripts\Activate

3. Inicializar o Repositório Git
>>> git init

4. Conectar com um Repositório Remoto
>>> git remote add origin https://github.com/alexsoares4a/producao_hospitalar.git

5. Configuração do usuário e email para uso do git
>> git config name "alexsoares4a"
>> git config email "alexssonline@gmail.com"

6. Obter os arquivos atualizados de um repositório remoto
>>> git push origin https://github.com/alexsoares4a/producao_hospitalar.git

7. Atualizar as dependências
>>> pip install -r requirements.txt --upgrade
