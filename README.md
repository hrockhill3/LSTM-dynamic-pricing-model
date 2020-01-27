# LSTM_Project

Написанный мной проект для дисертации по модели динамического ценообразования для Максидома на примере одного товара.
A project I wrote for a dissertation on a dynamic pricing model for Maksidom on the example of a single product.

LSTM модель обучалась на недельных данных по продажам за последние три года. 
Подробнее о используемых факторах можно посмотреть в эксель файле с генерирвоанными данными. Поскольку данные о продажах являются коммерческой тайной, на основе модели обученной на реальных данных я нагенерировал данные, которые включают в себя зависитмости с реальных данных, но не отражают их напрямую.
The LSTM model was trained on weekly sales data over the past three years.
More details about the factors used can be found in the excel file with the generated data. Since sales data are a trade secret, based on a model trained on real data, I generated data that includes dependencies with real data, but do not directly reflect them.

В Питоновском файле написана симуляция/демонстрация системы, которая предлагает  попробовать свои силы в обходе модели в задаче максимизации прибыли с помощью ценообразования.
Поскольку цены влияют на продажи напрямую, в скрипт встроен генератор продаж на следующий шаг на основе заданной цены человеком/моделью и проводится сравнение заработанных денег за последуюущю неделю.
In the Python file, a simulation / demonstration of a system is written that offers to try your hand at bypassing the model in the task of maximizing profits using pricing.
Since prices directly affect sales, the script generates the next-generation sales generator based on a given price by a person / model and compares the money earned over the next week.

LSTM модель была опробована на практике и цены выставлялись на основе рекомендации модели на протяжении 4 недель.
По результатам эксперимента был получен значительный прирост выручки и прибыли (+100% и +200%) по сравнению с аналогичным периодом года t-1 и t-2, что продемонстрировало применимость такой системы для формирования системы ценообразования для оффлай магазина.
The LSTM model was tested in practice and prices were set based on the model recommendation for 4 weeks.
According to the results of the experiment, a significant increase in revenue and profit (+ 100% and + 200%) was obtained compared to the same period of the year t-1 and t-2, which demonstrated the applicability of such a system for the formation of a pricing system for an offline store.

