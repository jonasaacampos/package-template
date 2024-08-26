# Template para Criação de Pacotes Python 🐍

Este repositório fornece um template básico para a criação de pacotes Python. Ele é projetado para facilitar o desenvolvimento e a distribuição de seus pacotes.

## 🚀 Descrição
Siga estas instruções para configurar e usar o template.

### 📦 Instalação
Para instalar o pacote, execute o seguinte comando:

`pip install nome-do-pacote`

### 📋 Pré-requisitos

    - Python 3.6 ou superior
    - pip

### 🔧 Estrutura do Projeto

A estrutura básica do projeto é a seguinte:

```
text
package-template/
│
├── package_name/
│   ├── __init__.py
│   └── module.py
│
├── tests/
│   └── test_module.py
│
├── README.md
└── setup.py
```

## 🛠️ Como Usar

1. Clone o repositório: `git clone https://github.com/jonasaacampos/package-template.git`
2. Navegue até o diretório do projeto: `cd package-template`
3. Instale as dependências: `pip install -r requirements.txt`
4. Execute os testes: `pytest`

## Gerar os binários e publicar

### Para gerar os binários

```
python -m pip install --upgrade pip
python -m pip install twine
python -m pip install setuptools
python -m pip install wheel

# criar uma source distribution e uma distribuição binária
python setup.py sdist bdist_wheel
```

## CheckList para publicação
 
 - [ ] Criar conta no [Test Pypi](https://test.pypi.org/account/register/)
 - [ ] Publicar no Test Pypi
 - [ ] Instalar pacote usando Test Pypi
 - [ ] Testar pacote
 - [ ] Criar conta no [Pypi](https://pypi.org/account/register/)
 - [ ] Publicar no Pypi
 - [ ] Instalar pacote usando Pypi

## 🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um issue ou um pull request.

## 📄 Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENCE](LICENCE.md) para mais detalhes.

 ## About Me:
 Uma breve descrição sobre o autor...
 Meu link do github.

