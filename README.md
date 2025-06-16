# Имитационная Модель Экосистемы "Овцы и Волки"

![](https://img.shields.io/badge/python-3.11-blue)

Проект реализует симуляцию экосистемы с тремя типами сущностей:

- 🐑 Овцы (травоядные) - управляются нейронной сетью
- 🐺 Волки (хищники) - используют детерминированный алгоритм поиска
- 🌿 Трава - статичный ресурс


> **Цель**: изучение методов обучения с подкреплением на сонове динамики популяции.

## Запуск

```
curl -LsSf https://astral.sh/uv/install.sh | sh
uv venv venv --python=python3.11.11
source venv/bin/activate
python3 -m ensurepip --upgrade
pip install -r requirements.txt
pip install tensorflow[and-$device]
```

> В качестве device может быть `cpu` или `cuda`

## Содержание 

1. [Классы](docs/classes.md)
2. [Алгоритм](docs/algoritm.md)
3. [Обучение с подкреплением](docs/RL.md)
4. [Результаты](docs/results.md)
