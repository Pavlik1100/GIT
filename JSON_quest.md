JSON
 1. Создать внешний репозиторий c названием JSON. ----- + -> new repository -> заполнить поле "Repository name" -> чек бокс "Add a README file" -> кликнуть кнопку "create repository"
 2. Клонировать репозиторий JSON на локальный компьютер. ----- git clone https://github.com/Pavlik1100/GIT.git
 3. Внутри локального JSON создать файл “new.json”. ----- > new.json
 4. Добавить файл под гит. ----- git add new.json
 5. Закоммитить файл. ----- git commit -m "create new.json"
 6. Отправить файл на внешний GitHub репозиторий. ----- git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON. -----  
  
vim new.json  
  
-----  
  
 {  
    "FIO": "SimonovPavelSergeevich",  
    "age": 28,  
    "count_of_pets": 0,  
    "salary": 1000  
 }  

 8. Отправить изменения на внешний репозиторий. -----  
  
git add new.json  
git commit -m "update new.json"  
git push  

 9. Создать файл preferences.json ----- > preferences.json  
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON. -----  
  
vim preferences.json  
  
-----  
  
 {  
    "favourite_film": "Blade_runner",  
    "favourite_serial": "LOST",  
    "favourite_food": "fried_chiken",  
    "favourite_time_of_the_year": "summer",
    "next_visit_country": "USA"  
 }  


 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON -----  

> skills.json  
vim sklls.json  
  
-----  
  
 {  
    "skill_1": "why_QA",  
    "skill_2": "when_QA",  
    "skill_3": "where_QA"  
 }  


 12. Отправить сразу 2 файла на внешний репозиторий. -----  
  
git add preferences.json skills.json  
git commit -m "added 2 files preferences.json skills.json"  
git push  
  
 13. На веб интерфейсе создать файл bug_report.json. ----- add new file -> заполнить поле названия файла   
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе. ----- добавить commit в поле "commit changes" -> отметить чекбокс "commit directory to the main branch" -> нажать кнопку "commit changes"
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. ----- выбрать в дериктории файл для редактирования, кликнуть чтобы открыть -> нажать кнопку с карандашом "Edit this file" -> ввести данные в формате JSON  

{  
  "ID": 1,  
  "Title": "Button_'Home'_dont_click",  
  "Steps": "Open_web_and_click_button_'Home'",  
  "Facual_result": "When_button_click_nothing_is_happening",  
  "Expected_result": "When_button_click_we_back_home_page",  
  "Severity": "Medium"  
}  
       
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе. ----- добавить commit в поле "commit changes" -> отметить чекбокс "commit directory to the main branch" -> нажать кнопку "commit changes"
 17. Синхронизировать внешний и локальный репозиторий JSON ----- git pull
