## Проста обробка текстових даних засобами оболонки Unix-подібних ОС інтер команд ОС

![Рис1](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.1.1.pdf)
![Рис2](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.1.1.5.pdf)
![Рис3](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.1.1.6.pdf)

Рис.1, Рис.2, Рис.3 - Клонування гіт-репозиторію, створення гілки Laboratory-work-3 та однойменного каталогу, створення файлу README та його обробка за допомогою команди nano, через послідовність Git-команд add, commit із коментарем «Changed by Local Git» та push завантажуємо файл README на GitHub.

### 1 Навігація по файловій системі через засоби оболонки Git Bash інтерпретатору командного рядку Bash:

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.2.1.pdf)
Рис.1 - Отримання переліку файлів поточного каталогу з урахуванням видимості прихованих файлів.

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.2.2.pdf)
Рис.2 - Переходимо до прихованого каталогу .git, використовуючи команду pushd з метою швидкого повернення до попереднього каталогу у майбутньому.

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.2.3.pdf)
Рис.3 - Переглядаємо вміст файлу config, використовуючи редактор nano.

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.2.4.pdf)
Рис.4 - Отримаємо перелік файлів поточного каталогу з урахуванням умов завдання за допомогою команди ls -lahS.

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.2.5.pdf)
Рис.5 - Повертаємося до каталогу, використовуючи команду швидкого повернення popd.

### 2 Налаштування псевдонімів команд оболонки Bash:

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.3.1.pdf)
Рис.1 - Виконуємо команду alias для створення псевдоніму виклику команди touch. Перевіряємо роботу псевдоніму команди.

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.3.2.pdf)
Рис.2 - Виконуємо команду alias для створення псевдоніму виклику команди date +%d-%m-%y, яка буде надавати поточну дату лише із поточним днем, місяцем та роком. 

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.3.3.pdf)
Рис.3 - Використовуючи текстовий редактор nano, відрегадували файл .bash_profile та додали у файл два рядки зі створеними раніше псевдонімами виклику команд. Після цього виходимо з GitBash.

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.3.5.pdf)
Рис.4 - Відкриваємо GitBash та перевіряємо псевдоніми команд.

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.3.6.pdf)
Рис.5 - Копіюємо файл .bash_profile до каталогу «Laboratory-work-3» Git-репозиторію.

### 3 Робота з файлами через перенаправлення вхідних/вихідних потоків:

![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.1.pdf)


![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.2.pdf)


![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.3.pdf)


![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.4.pdf)


![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.5.pdf)


![image](https://github.com/KostyaBalaban/Laboratory-work-3/blob/main/Laboratory-work-3/imagesforREADME/2.4.6.pdf)


### 4 Проста обробка результатів виконання команд
