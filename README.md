# XML
 1.  Создать внешний репозиторий c названием XML: 
 
    На GitHub выбрать вкладку "Repositories", нажать "New", в окне "Repository name" написать "XML", поставить галочку напротив "Add a README file", нажать "Create repository"
 2.  Клонировать репозиторий XML на локальный компьютер: 
   
    git clone https://github.com/Dmbrshn/XML.git
 3.  Внутри локального XML создать файл "new.xml": 
   
    touch new.xml
 4.  Добавить файл под гит: 
    
    git add new.xml
 5.  Закоммитить файл: 
    
    git commit -m "new file"
 6.  Отправить файл на внешний GitHub репозиторий: 
    
    git push
 7.  Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML: 
    
    vim new.xml , i , набираем нужный текст, :wq  
 8.  Отправить изменения на внешний репозиторий:
    
    git add new.xml && git commit -m "Edit file" && git push
 9.  Создать файл preferences.xml:
    
    touch preferences.xml
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML:
    
    vim preferences.xml , i , набираем нужный текст, :wq 
 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML:
    
    touch skills.xml && vim skills.xml , i , набираем нужный текст, :wq 
 12. Отправить сразу 2 файла на внешний репозиторий:
    
    git add . && git commit -m "preferences and skills" && git push
 13. На веб интерфейсе создать файл bug_report.xml:
    
    В Репозитории "XML" нажать "Add file" , выбрать "Create new file" , в поле "Name" написать "bug_report.xml" 
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
    
    Нажать "Commit new file"
 15. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML:
    
    В Репозитории "XML" выбирать файл "bug_report.xml" , нажать на иконку "карандаш" , набираем текс 
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
 
    Нажать "Commit changes"
 17. Синхронизировать внешний и локальный репозиторий XML:
 
    git pull
