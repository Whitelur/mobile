# 📱Тестирование мобильных приложений  
Проведено тестирование мобильного приложения "shopping-list", ориентированного на создание и управление списками задач, с использованием эмулятора Android Studio  

На сонове требований была разработана тестовая документация, Ниже приведены ссылки для ознакомления с составленной документацией.👇  
💡[Чек-лист](https://docs.google.com/spreadsheets/d/1OmH8O67ZnlJNlikAi7wykgaHPSFwXaDH0XlloGPi_uY/edit?usp=sharing) в формате xlsx  
💡[Тест-кейсы](https://drive.google.com/file/d/1qvYTrS5pGJY-OzanrF549pkitExbNgh3/view?usp=sharing) *тест-кейсы составлены в QASE и экспортированы в формате PDF 
#    

  
Проведено тестирование с использованием чек-листа и тест-кейсов на основе созданной документации, результаты были зафиксированы...👇  
💡[YouTrack](https://docs.google.com/spreadsheets/d/1wNacOKetUtTDWoi4Jv3Z5eXJ1vrY9elU3uLBWE87oDM/edit?usp=sharing)     

Оформлено в YouTrack (XLSX), с привязкой багов к соответствующим тест-кейсам из QASE.  
💡[Тестовый прогон QASE](https://drive.google.com/file/d/1ds13LFQbSIKmab41ZszNTE9AfzxS9v2N/view?usp=sharing)  

💡[Отчет о ходе тестирования  ](https://docs.google.com/document/d/1U4rluJG9db82_EK10Mg7dZ1GYyDSFZvtPanMd6CWm-8/edit?usp=sharing)    

## 🗝 Перехват трафика  
В ходе тестирования мобильного приложения "shopping-list" использовался сниффер для перехвата, изменения и анализа HTTP-запросов.
В рамках тестирования были выполнены следующие задания:

1️⃣ Изменение запроса на удаление товара из корзины:  
С помощью брейкпоинта был перехвачен запрос на удаление одного товара, который был изменен таким образом, чтобы удалился другой товар.  

2️⃣ Симуляция подмены контента:   
Настроен перехват запроса к [demoshopping.ru](https://demoshopping.ru), и ответ был подменен так, чтобы вместо сайта загружалась произвольная картинка.  

3️⃣ Перехват HTTPS-запроса с мобильного устройства:  
Проведен анализ сетевого трафика приложения, и зафиксирован один из перехваченных запросов, в котором в заголовке user-agent отображается информация о моем устройстве.  

💡[Charles](https://drive.google.com/file/d/1pl4dBnzNhprWKtgu6NlTqfAO269KCDPE/view?usp=sharing)    

💡[Изменение в header с помощью перехвата ](https://drive.google.com/file/d/1a_cHaRsJIhRDhibeS9hPpcapeN8FBdjL/view?usp=sharing)
