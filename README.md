# Student Calculator App

## Сипаттамасы
Қарапайым калькулятор қосымшасы. CI/CD конвейерін көрсету үшін жасалған оқу жобасы.

## Қолданылатын технологиялар
- Python 3.11
- pytest
- GitHub Actions

## Орнату
pip3 install -r requirements.txt

## Тестілеу
pytest tests/ -v

## CI/CD
GitHub Actions арқылы әр push кезінде 5 unit-тест автоматты іске қосылады.
Pipeline: Build → Test
