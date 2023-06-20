# Условия
Разработать (однопользовательский) ВК-бот для поиска людей:

- Бот должен получать информацию из профиля пользователя(Возраст, пол, город, семейное положение, если информации недостаточно нужно дополнительно спросить её у пользователя). Входные данные: Имя пользователя или его id в ВК, для которого мы ищем пару.
- Бот должен выполнять поиск анкет на основе полученных данных
- Бот должен выдавать пользователю по очереди найденные анкеты (ссылка на профиль, топ-3 популярных фотографии, Популярность определяется по количеству лайков и комментариев.)

Требования к сервису:
1. Код программы удовлетворяет PEP8.
2. Получать токен от пользователя с нужными правами.
3. Программа декомпозирована на функции/классы/модули/пакеты.
4. Результат программы записывать в БД.
5. Люди не должны повторяться при повторном поиске.
6. Не запрещается использовать внешние библиотеки для vk.
