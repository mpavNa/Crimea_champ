# Решение для соревнования Региональный чемпионат, Крым

Планы БТИ являются строгим форматом, однако в предложенном датасете имеются планы совершенно разных форматов. Для сегментации изображений с разной семантикой, я решила использовать нейросеть SegNet которая хорошо показывает себя на малом объеме данных в медицинских задачах


**По итогам сореврнования я сделала:**

Разделила датасет на три части – разметка по стенам, окнам и дверям
Обучила простейшую модель SegNet


**Технические особенности:**

Python, Pytorch, PIL, SegNet.
