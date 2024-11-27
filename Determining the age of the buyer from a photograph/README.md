# Determining the age of_the buyer from a photograph

[ipynb](https://github.com/allenbext/Portfolio/blob/main/Determining%20the%20age%20of%20the%20buyer%20from%20a%20photograph/Determining_the_age_of_the_buyer_from_a_photograph.ipynb)

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
