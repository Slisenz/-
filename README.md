В рамках обучения в Яндексе, у нас было несколько проектов. Тут будет описан один из самых больших, где задействовано довольно большое количество инструментов для проведения полномасштабного тестирования.

## 📌 **О проекте**  
Яндекс.Самокат — сервис аренды электросамокатов, включающий:  
- **Веб-приложение** для клиентов (оформление/отслеживание заказов)  
- **Мобильное приложение** для курьеров (выполнение заказов)  
- **Бэкенд-API** для взаимодействия между системами

 Перед тестированием сервиса, была разработана [MindMap](https://miro.com/app/board/uXjVI1lwBdg=/?share_link_id=565720288200) 
## Направления тестирования
### 🔹 Тестирование веб-приложения  
- **Валидация данных:**  
  - Проверка корректности работы полей формы заказа  
  - Тестирование граничных значений и обработки ошибок  
- **Функциональность заказов:**  
  - Проверка отображения статуса заказа  
  - Тестирование переходов между экранами  
- **UI-тестирование:**  
  - Сверка с макетами  
  - Проверка адаптивности  

Пример разработанного чек-листа   
<img src="https://github.com/Slisenz/Yandex/blob/main/image3.png?raw=true" width="800">

### 🔹 Тестирование мобильного приложения (курьерская часть)  
- **Критичные сценарии:**  
  - Работа приложения без интернет-соединения  
  - Корректность получения и отображения уведомлений  
- **Основной функционал:**  
  - Прием и выполнение заказов  
  - Навигация по карте    

Составленый тест-кейс  
<img src="https://github.com/Slisenz/Yandex/blob/main/img19.png?raw=true" width="1200">

### 🔹 Тестирование API  
- **Валидация запросов:**  
  - Проверка структуры ответов  
  - Тестирование ошибок и статус-кодов  
- **Критичные endpoints:**  
  - Создание/отмена заказа  
  - Обновление статуса заказа  

 Чек-лист для API  
<img src="https://github.com/Slisenz/Yandex/blob/main/image4.png?raw=true" width="800">

 ### Во время тестирования были задействованы следующие инструменты
 <img src="https://cdn.iconscout.com/icon/free/png-256/free-postman-logo-icon-download-in-svg-png-gif-file-formats--technology-social-media-company-brand-vol-5-pack-logos-icons-2945092.png?f=webp&w=256" width="16" height="16"> Postman | <img src="https://static-00.iconduck.com/assets.00/swagger-icon-2048x2048-563qbzey.png" width="16" height="16"> Swagger |
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Android_Studio_icon_%282023%29.svg/768px-Android_Studio_icon_%282023%29.svg.png" width="16" height="16"> Android Studio | <img src="https://images.icon-icons.com/3053/PNG/512/charles_proxy_macos_bigsur_icon_190302.png" width="16" height="16"> Charles |
<img src="https://static-00.iconduck.com/assets.00/chrome-devtools-icon-1024x1024-bgoqb03p.png" width="16" height="16"> DevTools |
 <img src="https://cdn-icons-png.flaticon.com/512/2772/2772128.png" width="16" height="16"> SQL | <img src="https://cdn-icons-png.flaticon.com/512/5968/5968705.png" width="16" height="16"> Figma |
 <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/Cygwin_logo.svg/2048px-Cygwin_logo.svg.png" width="16" height="16"> Cygwin |


## 📊 Результаты тестирования
В общей сумме было разработано и протестировано более 250 различных проверок. Всего было обнаружено 61 баг, из которых 16 удалось обнаружить путем исследовательского тестирования.  
Пример составленных баг-репортов
<img src="https://github.com/Slisenz/Yandex/blob/main/image9.png?raw=true" width="1200">  
- Чек-листы, тест-кейсы и баг-репорты можно посмотреть [тут](https://docs.google.com/spreadsheets/d/1bTEnWMD2GtPbUm7DSoHToSowaGisFel8zIL-lNpwcSc/edit?usp=sharing)  
