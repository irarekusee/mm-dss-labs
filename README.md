# Индикаторы технического анализа
**Лабораторная работа №2**


**Тема:** выработка рекомендации поведения трейдера на основе паттернов и индикаторов.


**Цель работы:** научиться предлагать поведенческую стратегию с помощью комплексного индикатора.


**Задачи:**


- выбрать комплексный индикатор;
- выбрать временной ряд для анализа;
- реализовать выбранный индикатор в соответствии с правилами его построения;
- осуществить оценочный прогноз за определенный период;
- предложить решение: не входить в торговлю, покупать или торговать акциями.


**Описание**: в качестве индикатора был выбран MACD. Так, алгоритм определяет, что время торговать, когда Signal line "пробивает" Main line, наоборот - время закупать акции. Прогноз цены за следующие 5 торговых дней строится с помощью модели ARIMA. Таким образом, трейдер может принять решение стоит ли выходить на рынок и оценить возможную прибыль.


**Рефлективное заключение:** в ходе выполнения лабораторной работы был получен навык построения поведенческой стратегии трейдера на основе индикатора технического анализа MACD. Интеративный график, отражающий стратегию в каждый из торговых дней, а также прогноз цены на следующие 5 торговых дней, позволяет быстро оценить ситуацию на рынке и принять решение.
