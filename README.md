![](https://img.shields.io/github/license/wh1isper/camonline)
![](https://img.shields.io/github/v/release/wh1isper/camonline)
![](https://img.shields.io/pypi/dm/camonline)
![](https://img.shields.io/github/last-commit/wh1isper/camonline)
![](https://img.shields.io/pypi/pyversions/camonline)

# camonline

## Install

`pip install camonline`

## Usage

Set timezone(e.g. `Aisa/Shanghai UTC+8`)

```bash
docker run -it \
-v /dev/video4:/dev/video0 \
-e TZ=Asia/Shanghai \
wh1isper/camonline:latest
```

## Develop

Install pre-commit before commit

```
pip install pre-commit
pre-commit install
```

Install package locally

```
pip install -e .[test]
```

Run unit-test before PR, **ensure that new features are covered by unit tests**

```
pytest -v
```
