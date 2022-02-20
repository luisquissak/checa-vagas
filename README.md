# checa-vagas

Projeto Python para usar técnicas de ML na busca por vagas pre selecionadas adequadas a um currículo

## Instalar Python e Clonar e Setar o projeto

Baixar e instalar [Python 3.10](https://www.python.org/downloads/release/python-3100/).

```bash
C:\Users\A450373\appdata\local\Programs\Python\Python310\python --version
```

Clonar o projeto [checa-vagas](https://github.com/luisquissak/checa-vagas).

```bash
git clone git@github.com:luisquissak/checa-vagas.git
```

Criar [ambiente virtual](https://code.visualstudio.com/docs/python/environments):

```bash
cd checa-vagas
C:\Users\A450373\appdata\local\Programs\Python\Python310\python -m venv .venv
```

Ativar venv:

```bash
.venv\Scripts\activate
```

Atualizar pip:

```bash
python -m pip install --upgrade pip
```

Instalar libs:

```bash
pip install -r requirements.txt
```

## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
