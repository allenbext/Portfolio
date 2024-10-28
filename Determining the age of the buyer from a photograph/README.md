# Определение возраста покупателей по фотографии

[ipynb](https://github.com/allenbext/Portfolio/blob/main/Defining%20Comment%20Toxicity/Defining_Comment_Toxicity.ipynb)

## Описание проекта

Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Требуется построить модель, которая по фотографии определит приблизительный возраст человека. 

## Навыки и инструменты

- **python**
- **pandas** 
- **numpy**
- **matplotlib**
- **seaborn**
- tensorflow.keras.preprocessing.image.**ImageDataGenerator**
- tensorflow.keras.applications.resnet.**ResNet50**
- tensorflow.keras.models.**Sequential**
- tensorflow.keras.layers.**GlobalAveragePooling2D**
- tensorflow.keras.layers.**Dense**
- tensorflow.keras.optimizers.**Adam**
- tensorflow.**keras**

## Общий вывод

Обученная модель достигла требуемой заданием метрики MAE. Переобучение отсутсвует. Полученная модель рекомендована к использованию для рекомендаций товара для определенной возрастной группы.
