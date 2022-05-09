# SHEBANG

Na computação, o shebang é uma sequência de caracteres que indica ao interpretador que o arquivo é um script de comando. Nele mostramos o caminho do interpretador que será usado para executar o script.

No Python, o shebang é definido como:
```python
#!/usr/bin/env python
```
Com o auxílio do shebang, o interpretador do Python será determinado automaticamente, tornando desnecessário que o usuário chame explicitamente o interpretador.

# delta-git

Extensão que ajudar melhor visualizar o histórico de commits.

# Virtual Environments

O python permite a criação de ambientes virtuais, onde você pode criar um ambiente de trabalho para executar scripts Python sem se preocupar em poluir a sua instalação global de python com pacotes que possam vir a dar conflito em algum momento.

1. Criando um ambiente virtual

```python
python3 -m venv .venv
```
A pasta `.venv` será criada na mesma pasta do script, o nome `.venv` é opcional e vc pode por qualquer nome, sendo ou não oculto, por convenção cria-se a pasta com o nome `.venv`.

2. Ativando o ambiente virtual

```python
source .venv/bin/activate
```

A ativação do ambiente virtual é necessária, assim o interpretador Python será configurado para executar o script Python dentro do ambiente virtual, e não na instalação global.

