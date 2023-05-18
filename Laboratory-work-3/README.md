## Проста обробка текстових даних засобами оболонки Unix-подібних ОС інтерпретора команд ОС

![Рис1](
![Рис2](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.1.1.5.png)
![Рис3](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.1.1.6.png)

Рис.1, Рис.2, Рис.3 - Клонування гіт-репозиторію, створення гілки Laboratory-work-3 та однойменного каталогу, створення файлу README та його обробка за допомогою команди nano, через послідовність Git-команд add, commit із коментарем «Changed by Local Git» та push завантажуємо файл README на GitHub.

### 1 Навігація по файловій системі через засоби оболонки Git Bash інтерпретатору командного рядку Bash:

![Рис1](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.2.1.png)
Рис.1 - Отримання переліку файлів поточного каталогу з урахуванням видимості прихованих файлів.

![Рис2](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.2.2.png)
Рис.2 - Переходимо до прихованого каталогу .git, використовуючи команду pushd з метою швидкого повернення до попереднього каталогу у майбутньому.

![Рис3](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.2.3.png)
Рис.3 - Переглядаємо вміст файлу config, використовуючи редактор nano.

![Рис4](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.2.4.png)
Рис.4 - Отримаємо перелік файлів поточного каталогу з урахуванням умов завдання за допомогою команди ls -lahS.

![Рис5](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.2.5.png)
Рис.5 - Повертаємося до каталогу, використовуючи команду швидкого повернення popd.

### 2 Налаштування псевдонімів команд оболонки Bash:

![Рис1](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.3.1.png)
Рис.1 - Виконуємо команду alias для створення псевдоніму виклику команди touch. Перевіряємо роботу псевдоніму команди.

![Рис2](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.3.2.png)
Рис.2 - Виконуємо команду alias для створення псевдоніму виклику команди date +%d-%m-%y, яка буде надавати поточну дату лише із поточним днем, місяцем та роком. 

![Рис3](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.3.3.png)
Рис.3 - Використовуючи текстовий редактор nano, відрегадували файл .bash_profile та додали у файл два рядки зі створеними раніше псевдонімами виклику команд. Після цього виходимо з GitBash.

![Рис4](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.3.5.png)
Рис.4 - Відкриваємо GitBash та перевіряємо псевдоніми команд.

![Рис5](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.3.6.png)
Рис.5 - Копіюємо файл .bash_profile до каталогу «Laboratory-work-3» Git-репозиторію.

### 3 Робота з файлами через перенаправлення вхідних/вихідних потоків:

![Рис1](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.1.png)
Рис.1 - Створюємо файл balaban_1, використовуючи команду cat з перенаправленням stdin-потоку на stdout-потік так, що файл містить один рядок з моїм прізвищем та ім’ям.

![Рис2](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.2.png)
Рис.2 - Додаємо до створеного файлу через перенаправлення stdout-потоку ще один рядок з номером моєї групи.

![Рис3](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.3.png)
Рис.3 - Створюємо файл balaban_2, який містить два рядки, створені через перенаправлення stdout-потоку двох наступних команд:
- команда визначення назви поточного каталогу, в якому ви знаходитеся, формує
перший рядок;
- команда визначення імені поточного користувача ОС, формує другий рядок;

![Рис4](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.4.png)
Рис.4 - Об`єднуємо два раніше створені файли в один файл командою cat зі створенням нового файлу, назва якого – balaban.cat.txt;

![Рис5](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.5.png)
Рис.5 - Повторюємо об`єднання файлів, але вже командою paste зі створенням нового файлу, де назва файлу – balaban.paste.txt;

![Рис6](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.6.png)
Рис.6 - Виконуємо Git-команди add та commit із коментарем «Changed by Local Git» для створення нового Git-знімку.

### 4 Проста обробка результатів виконання команд:

![Рис1](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.5.1.png)
Рис.1 - Отримємо перелік каталогів для швидкого пошуку файлів, які можуть виконуватися в командному рядку без вказування повного шляху до файлу.

![Рис2](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.5.2.png)
Рис.2 - Змінюємо рішення попереднього завдання так, щоб всі назви каталогів були в окремих рядках.

![Рис3](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.5.3.png)
Рис.3 - Змінюємо рішення попереднього завдання, впорядкувавши значення назв каталогів за зростанням та видаливши всі дублікати цих назв.

![Рис4](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.5.4.png)
Рис.4 - Змінюємо рішення попереднього завдання, визначивши лише перші 5 назв каталогів.

![Рис5](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.5.5.png)
Рис.5 - Проводимо статистичний аналіз результату завдання 2.5.3, отримавши кількість каталогів та розмір найбільшої назви каталогу.
