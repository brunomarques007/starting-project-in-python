# Projeto Init python

O Projeto Init Python é um script que visa auxiliar na inicialização de um projeto de API usando Python e FAstAPI, baseado nas aulas do "rei das lives de python" [Eduardo Mendes](https://github.com/dunossauro). Seu curso gratuito pode ser acessado pelo [link do curso](https://fastapidozero.dunossauro.com/).


## Instalação

Para a instalação deste script é necessário que você tenha o python3 e o git instalados.


Após fazer o clone do repositório, altera a permissão do script para executavel.
```bash
chmod +x start.sh
```

Agora execute o script no diretório em que pretende criar o projeto.

```bash
./start.sh

ou

bash start.sh
```

## Documentação

#### Dados sobre o projeto

O projeto é baseado em **Poetry** e **FastAPI**, os testes são gerados pelo **pytest**, a documentação é gerada de forma automatizada com o **mkdos**, o lint é feito pelo **ruff** + **isort** e as tarefas do projeto são criadas com o **taskpy**. Além disso você já pode criar também o seu push inicial do projeto para o git se o mesmo for habilitado ao rodar o script.

### Bibliotecas Utilizadas

Versionamento:
 - Git
 - gh

Python:
 - Poetry
 - pipx
 - ignr

Dev:
 - ruff
 - isort
 - pytest
 - pytest-cov
 - pytest-blue
 - taskipy

Doc:
 - mkdocs
 - mkdocs-material
 - mkdocstrings
 - mkdocstrings-python
## Autor

- [@brunomarques007](https://www.github.com/brunomarques007)

