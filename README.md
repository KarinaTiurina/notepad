# Программа "Блокнот"

Кносольное приложение на ruby 2.4.1 и базой sqlite3. Позволяет делать заметки с текстом, сохранять полезные ссылки с небольшим описанием, а также сохранять задачи, для дальнейшего выполнения.

Для записи:

    ruby new_post.rb
    
Для чтения

    ruby read.rb
    
Параметры для чтения:

    -h                           доступные параметры
    --type POST_TYPE             какой тип постов показывать (по умолчанию любой)
    --id POST_ID                 если задан id — показываем подробно  только этот пост
    --limit NUMBER               сколько последних постов показать (по умолчанию все)

   
- - - - - - - -

# Program "Notepad"

Console application on ruby 2.4.1 and database sqlite3. Allows you to take notes with text, save useful links with a small description, and also save tasks for further execution.

To write:
    
    ruby new_post.rb
    
To read.rb

    ruby read.rb
    
Available options to read:

    -h                           available options
    --type POST_TYPE             what type of posts to show (by default any)
    --id POST_ID                 if id is specified - shows in detail only this post
    --limit NUMBER               how many last posts to show (by default all)
   
    


