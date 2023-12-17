## Init env

```bash
$ pipenv shell
```

## Install package

```bash
$ pipenv install package_name
```

## Install package from requirements.txt file

```bash
$ pipenv install -r ./requirements.txt
```

## Install package from requirements.txt file localy

```bash
$ pip3 install -r requirements.txt -t ./
```

## Install package from requirements.txt file localy in directory

In restore.bat  
```bash
call pip3 install -r requirements.txt -t ./packages --no-user
call cd packages
call type NUL > __init__.py
call cd..
```

## List packages

```bash
$ pipenv shell
$ pip list
```

## Checking installed package safety

```bash
$ pipenv check
```

## Show packages dependencies

```bash
$ pipenv graph
```

## run pytest

```bash
$ python -m pytest -v
```
