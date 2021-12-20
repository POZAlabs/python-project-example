# python-project-example

파이썬 프로젝트 예시 (poetry, pre-commit)

리눅스/Mac OS 환경을 가정하고 있습니다.

## 프로젝트 세팅

### 1. `poetry` 설치 (글로벌 파이썬)

```shell
pip install poetry
```

### 2. 가상환경 구성 및 활성화

가상환경 구성

```shell
python3 -m venv .venv
```

가상환경 활성화

```shell
source .venv/bin/activate
```

### 3. 프로젝트 생성

```shell
poetry init
```

### 4. `pre-commit` 설치 및 구성

`pre-commit` 설치
```shell
poetry add pre-commit --dev
```

`pre-commit` 구성
```shell
pre-commit install
```
