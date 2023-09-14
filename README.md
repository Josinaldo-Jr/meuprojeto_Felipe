
# # Meu Progeto Inicial Flask

Uma breve descrição sobre o que esse projeto faz e para quem ele é


## Instalação

Crie uma pasta para o seu projeto

```bash
  mkdir meuprojeto
  cd meuprojeto
```
segundo passo: crie uma maquina virtual

```bash
  py -3 -m venv venv
```    
terceiro passo: ative a maquina virtual no windows

```bash
  nomedamaquinavirtual\Scripts\activate
```
quarto passo: instale o flask

```bash
  pip install flask
```
```bash
pip freeze > requiriments.txt    
pip install -r requiriments.txt
```

No terminal, na pasta do seu projeto, execute o seguinte comando para criar uma pasta para as migrações:
```bash
flask db init
```
Isso criará uma pasta chamada migrations onde as migrações serão armazenadas.
Agora você pode usar o seguinte comando para gerar uma migração baseada nos modelos que você definiu:
```bash
flask db migrate -m "Nome da Migração"
```
Resumindo:

```bash
 flask db init 
 ``` 
- Uma vez para inicializar o sistema de migração.
```bash
 flask db migrate
 ```
- Sempre que você fizer alterações em seus modelos.
```bash
 flask db upgrade 
 ```
- Sempre que você quiser aplicar as migrações pendentes ao banco de dados.

## Autores

- [@Riukos](https://www.github.com/riukos)


## Licença

[MIT](https://choosealicense.com/licenses/mit/)

