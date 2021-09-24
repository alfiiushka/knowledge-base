## Code Review

Code Review не решит проблему ошибок в коде и не сделает код идеальным. Имеет смысл для новичков на проекте, для случаев сомнений в выбранной реализации, для предложений каких-либо нововведений

* **Отправлять код на Code Review только тогда, когда это требуется**

  Доверие к членам команды(разрешать вливать в мастер задачи, если уверен в своей реализации, если нет, делать MR/PR)
  
* **Экономим время других членов команды**

  - Первое code review производится самостоятельно(анализаторы кода/ форматирование/ общая логика)
  - Работа только с небольшими по объему MR/PR(разбиваем на коммиты с ясными пояснениями)
  
* **Процесс Code Review**

  - Комментарии оставляются не автору, а коду(не персонализуются)
  - Придирки, необязательные к исправлению можно помечать как nitpick
  - Если код приходится объяснять - его лучше переделать

Ссылки:
- https://habr.com/ru/post/473308/
- https://tproger.ru/translations/kak-vljubit-v-sebja-revjuera/
- https://martinfowler.com/articles/branching-patterns.html#reviewed-commits