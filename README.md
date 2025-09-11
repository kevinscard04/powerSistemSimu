# powerSistemSimu
Simulador de sistemas de potência.


# Instruções e dependências

ABRA O CMD NA PASTA ONDE QUER BAIXAR O PROJETO E EXECUTE:

    git clone https://github.com/thauanqs/powerSistemSimu.git



Usar Python 3.12.

    py -m venv .venv
    py -3.12 -m venv .venv
    .venv\Scripts\activate


Instalar as dependências usando:

    py -m pip install -r requirements.txt

# Gerando arquivo executável Windows

Para gerar um executável Windows, com o venv ativo, navegue até a pasta "src":

    cd src

e execute:

    pyinstaller --onefile --noconsole main.py

O arquivo executável será criado como maim.exe na pasta "powerSistemSimu\src\dist"

