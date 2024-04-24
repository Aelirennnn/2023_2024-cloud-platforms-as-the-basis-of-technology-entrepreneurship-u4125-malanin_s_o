University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FTMI](https://ftmi.itmo.ru/)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/)
Year: 2023/2024
Group: U4125
Author: Malanin Sergey Olegovich
Lab: Lab2
Date of create: 24.04.2024
Date of finished: --.--.2024

1. Я создал Cloud Run из представленного дефолтного сервиса Hello с минимальным количеством ресурсов.
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/bfb51c58-2c06-44f8-979c-a6d8f30bea98)
2. Я перешел по предоставленной ссылке Cloud Run.
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/0ae085ca-be8e-416f-8ac7-f80774af0838)
3. Я перешёл в разделы логов и метрик, проанализировал их: \
В логах я нашёл какие действие происходили с сайтом, как он запускался, отвечал на запрос GET
![Без имени](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/1d8555bb-ef12-4c71-a683-4025ec6fa407)
В метриках нашёл показатели, которые можно отслеживать: \
Количество запросов и их задержка; \
Сколько данных получено и отправлено; \
Как использовались ресурсы и т.д.
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/51a3ffba-1839-4ff4-9624-2ea612c05f23)
4. Я изменил настройки моего Cloud Run, поменяв порт на 8090. \
После смены порта на сайте отображается новая версия
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/d9bbe170-1a84-4cb7-9df0-accec23de613) \
А в метриках, можно заметить, что переключение версий показывается на графиках:
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/c9579ccc-ac08-4b8b-ba31-65e370adfe4f)
