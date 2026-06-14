# hello-world

간단한 Python 유틸리티 모음입니다.

## 설치

Python 3.8 이상이 필요합니다.

```bash
pip install pytest
```

## 사용법

```python
from calculator import add, divide

print(add(2, 3))      # 5
print(divide(10, 2))  # 5.0
```

## 테스트 실행

```bash
pytest test_calculator.py -v
```

## 기능

- 덧셈 (`add`)
- 뺄셈 (`subtract`)
- 곱셈 (`multiply`)
- 나눗셈 (`divide`) — 0 나누기 시 `ValueError` 발생
