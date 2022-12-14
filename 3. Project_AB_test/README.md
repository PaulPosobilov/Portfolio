*ПРИМЕЧАНИЕ:   
В данном проекте, для визуализации полученных результатов, используется интерактивный график из библиотеки plotly.   
Для того, чтобы увидеть проект с корректно отображающимся графиком перейдите по ссылке:*   https://nbviewer.org/github/PaulPosobilov/Portfolio/blob/main/3.%20Project_AB_test/Project_3_AB_test.ipynb

# Анализ результатов A/B-теста  
## Описание проекта:  

Наши основные задачи:  

* Провести оценку результатов A/B-теста;    
* оценить корректность проведения теста;  
* проанализировать результаты теста;  
* оценить изменения, связанные с внедрением улучшенной рекомендательной системы.  

**Проект состоит из следующих этапов:**  
1. Загрузка и изучение данных.  
2. Предобработка данных.  
3. Исследовательский анализ данных.  
4. Оценка результатов A/B тестирования. 
5. Выводы.  

**Результаты:**  
- Нельзя принимать результаты A/B теста, т.к. есть значимые ошибки при его проведении;  
- количество пользователей в контрольной группе 2604 пользователей, в тестовой группе 877, разница почти в три раза;  
- минимальное количество пользователей, установленное в ТЗ, было набрано и составило более 6000 человек, однако, какое-либо действие в ходе теста сделали лишь 3481 человек, что существенно ниже условию из ТЗ;  
- в таблице с действиями пользователей не хватило данных за 5 дней, с 31 декабря 2020 года по 4 января 2021 года;  
- параллельно с нашим тестом проводился конкурирующий тест и были пользователи, которые участвовали в двух тестах одновременно. Хотя мы и выяснили, что доля пользователей из конкурирующего теста в группе B одновременно участвовала в равных долях в первом тесте в группах A и B, нельзя считать, что это не могло повлиять на результаты теста - это серьезное допущение;  
- было установлено, что в период проведение теста проводилась одна маркетинговая компания, и хотя активность пользователей группы A и B одновременно снизилась в этот период, знать точное влияния компании не представляется возможным.  

**Основные инструменты и библиотеки используемые в проекте:**  
`python`, `pandas`, `seaborn`, `matplotlib`, `plotly`, `math`, `scipy`, `numpy` 

**Статус проекта:** Закончен.
