University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FTMI](https://ftmi.itmo.ru/)  
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/)  
Year: 2023/2024  
Group: U4125  
Author: Malanin Sergey Olegovich  
Lab: Lab4  
Date of create: 30.04.2024  
Date of finished: --.--.2024  

![Prototype](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/f6563281-ad98-4837-95f9-af7347035f1a)  

**Начальное состояние (15-45 человек):**  
VM: e2-micro 0.25-2 vCPU 1 GB memory — 7.11$  
SQL Cloud: PostgreSQL 1 vCPU 0.6 GB memory — +- 9.5$  
_Итог — 16.61$_  
Выбор данной конфигурации обусловлен небольшим количеством пользователей и низкими нагрузками на приложение на начальном этапе. Этот тип обеспечивает достаточные ресурсы для запуска и тестирования приложения, не превышая бюджет.  
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/41d46d92-5602-4d44-9f41-d9fe362d668d)  
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/cdee695f-4b57-4be8-af34-6b204ac975cd)  

**Тестирование партнёрами (100 - 150 человек):**  
VM: e2-small 0.5-2 vCPU 2 GB memory — 13.23$  
SQL Cloud: PostgreSQL 1 vCPU 1.7 GB memory — +- 28.98$  
_Итог — 42.21$_  
Увеличение объема ресурсов, связано с увеличением числа пользователей и, соответственно, с увеличением нагрузки на приложение. Увеличение ресурсов базы данных также обусловлено увеличением нагрузки и объема данных, генерируемых и обрабатываемых приложением при тестировании продукта.  
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/1bafd689-39e4-40f5-8a8d-f4d93eba9be8)  
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/c44b8611-bcec-4ddc-b885-c75c8c0b5348)  
 
**Продовое решение:**  
VM: e2-medium 1-2 vCPU 4 GB memory — 25.46$  
SQL Cloud: PostgreSQL 1 vCPU 3.75 GB memory — +- 66.5$  
_Итог — 96.91$_  
Для продового решения необходимы более мощные ресурсы, из-за обработки более высокой нагрузки и увеличения объема данных, с которыми приходится работать на этапе продуктивной эксплуатации.
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/68620082-596d-406e-ae47-bff570bcb2f7)  
![image](https://github.com/Aelirennnn/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-malanin_s_o/assets/125411403/75e2caab-8961-4801-a09b-64c625a0bd47)  

**Таким образом**, на начальном этапе были выбраны VM: e2-micro 0.25-2 vCPU 1 GB memory и SQL Cloud: PostgreSQL 1 vCPU 0.6 GB memory, так как они обеспечивают достаточные ресурсы для начального числа пользователей при минимальных затратах.   
На этапе тестирования с партнерами были выбраны более мощные VM: e2-small 0.5-2 vCPU 2 GB memory и SQL Cloud: PostgreSQL 1 vCPU 1.7 GB memory, чтобы обеспечить дополнительные ресурсы при повышенной нагрузке из-за тестирования активного.   
На этапе продуктового решения выбраны еще более мощные VM: e2-medium 1-2 vCPU 4 GB memory и SQL Cloud: PostgreSQL 1 vCPU 3.75 GB memory для обеспечения стабильной работы приложения в реальных условиях с большим количеством пользователей.  

Я бы использовал решения, которые предполагают плату только за фактическое использование ресурсов, чтобы снизить издержки во время простоя платформы
