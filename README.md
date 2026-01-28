<div align="center">
  <img src="img/logo.png" width=300px>

<br>

Машинное обучение на `Brainfuck`. Потому что можно. \
Самый бесполезный проект в истории GitHub!
</div>

Сейчас вы видите на 99.99% навайбкоденный ML фреймворк на Brainfuck, цель которого — доказать, что это по-настоящему полный по Тьюрингу язык, на котором можно сделать AGI.

## Установка
```cmd
git clone https://github.com/droyti46/bflearn.git
```

## Python API

Вдохновлён API [Scikit-learn](https://github.com/scikit-learn/scikit-learn)

```python
from bflearn import BFLinearRegressionSGD

reg = BFLinearRegressionSGD(alpha=2)

x = [1, 2, 3, 4, 5]
y = [4, 5, 6, 7, 8]

reg.fit(x, y, epochs=9)
print(reg.predict(10))
```

