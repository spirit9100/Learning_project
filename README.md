# Учебные проекты по курсу ML-engineer
### [Учебный проект по созданию нейроассистента.](https://github.com/spirit9100/Learning_project/blob/main/RAG-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0%20%D1%81%20%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20saiga_mistral_7b.ipynb)

Для реализации проекта используем фреймфорк LlamaIndex. LLM выберем на основе [Leaderboard](https://russiansuperglue.com/leaderboard/2), для русскоязычных моделей. Для выбора определим критерии: модель должна понимать инструкции,  должна помещаться в память GPU в блокноте и занимать как можно выше позицию в списке.

Модель подходящая под наши праметры является [saiga_mistral_7b_lora](https://huggingface.co/IlyaGusev/saiga_mistral_7b_lora/tree/main)

В качестве источника знаний возьмем книгу "ХАКИНГ Искусство эксплойта" Второе издание автор Джон Эриксон.

Для улучшения нашей системы будем использовать [Arize Phoenix](https://phoenix.arize.com/), которая позволит произвести трассировку запросов к модели.

Защиту нашей системы попробуем написать сами 🚲 😀.

### [Пример реализации распознования шахматных на изображении.](https://github.com/spirit9100/Learning_project/blob/main/41_YOLO_%D0%BE%D0%B1%D0%BD%D0%B0%D1%80%D1%83%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5_%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BE%D0%B2.ipynb)
Пример содержит построение модели на основе архитектуры YOLO v3. 

###[Обучение с подкреплением Reinforcement learning](https://github.com/spirit9100/Learning_project/blob/main/42_%D0%9E%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_%D1%81_%D0%BF%D0%BE%D0%B4%D0%BA%D1%80%D0%B5%D0%BF%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D0%BD%D0%B0_%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5_%D0%B8%D0%B3%D1%80_gymnasium_%D0%B8_%D0%B8%D0%B3%D1%80_Atari.ipynb)  
В реализации используется игра Atari Space Invaders
