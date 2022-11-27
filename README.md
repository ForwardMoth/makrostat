# Лабораторные работы по курсу "Макростатистический анализ и прогнозирование"

- Установка Jupyter Notebook 

```python 
pip install jupyter notebook
```

- Запуск кода

```python 
jupyter notebook
```

## 1 лабораторная "Кластерный анализ"

- 

-

-

## 2 лабораторная "Дискриминантный анализ" 

Исходные данные: стандартизированные данные о состоянии субъектов РФ. В качестве показателей были выбраны 9 различных признаков: 

1. *Х1* – Число больничных коек на 1000 человек населения 
2. *Х2* – Численность врачей всех специальностей всего человек на 1000 человек населения 
3. *Х3* – Среднедушевые денежные доходы населения (в месяц; рублей)
4. *Х4* – Численность рабочей силы, тыс. человек на 10000 человек населения 
5. *Х5* – Зарегистрировано преступлений по ч. 4, ст. 111 УК РФ - умышленное причинение тяжкого вреда здоровью, повлекшее по неосторожности смерть потерпевшего на 100000 человек населения
6. *Х6* – Предварительно расследовано преступлений, совершенных в состоянии алкогольного опьянения на 1000 человек
7. *Х7* – Общие коэффициенты смертности (число умерших на 1000 человек населения)
8. *Х8* – Выбросы загрязняющих веществ в атмосферный воздух, отходящих от стационарных источников (тысяч тонн) на 100000 человек населения
9. *Х9* – Расходы на охрану окружающей среды (млн руб) на 1000 человек

Для рассмотрения взяты *83 субъекта* из прошлой лабораторной, для исключения классов с 1 объектом. 
Задача: _классифицировать объекты к классам на основе обучающей выборки. Для основы выбрано *6 классов* и в каждом из них выбраны обучающие выборки, которые являются по принципу наиболее близкого расположения к центрам классов._

### В ходе выполнения реализовано:  

- Оценка общей ковариационной матрицы

- Оценка средних значений в классах 

- Квадрат расстояния между классами (Растояние Махаланобиса)

- Найдены коэффициенты линейных дискриминантных функций Фишера ___Имеются расхождения со Statitica___

### А также пошаговый дискриминантный анализ 

- Пошаговое включение

- Пошаговое исключение

## 3 лабораторная "Метод главных компонент" (код написан командой [Daniil Gofman](https://github.com/danielgof))

-

-

-
