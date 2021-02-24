### Hi there 👋

<!--
**zig-i2p/zig-i2p** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |




| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

=====================================================================

Incognito, [09.01.21 20:00]
#лайфхак 

   (https://telegra.ph/file/f4a54c63a4b9d82762ef0.jpg)
   # Чекаем слитые пароли от Wi-Fi

### vulpw - утилита для проверки паролей от Wi-Fi на утечку в базу данных.

#### Установка:


```sh
apt update
apt install git -y
apt install python -y
git clone https://github.com/codekushi/vulpw.git
cd vulpw
pip install -r requirements.txt
```
Запуск:
`python checker.py`

После чего нам предлагают сделать выбор среди четырёх пунктов.

• 1 - проверка пароля от Wi-Fi на утечку данных
• 2 - проверка имени точки доступа на утечку данных
• 3 - проверка Wi-Fi на утечку данных
• 4 - проверка паролей среди других файлов

Если у вас появляется строка:

`If the Checker doesn't spot any weakness then your Password is safe (or) its yet to get updated in our wordlist`, то всё заебись. Утилите не удалось найти пароль среди базы данных.

А если у вас появляется строка:
`Your Password ваш пароль is Vulnerble`, то пиздец. Пароль попал в базу.


https://sourcegraph.com/github.com/Aniket965/Hello-world@647bad9da901a52d455f05ecc37c6823c22dc77e/-/blob/Python/webscraper.py?subtree=true&utm_source=share#L2:8
