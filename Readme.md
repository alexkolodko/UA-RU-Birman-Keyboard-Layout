# Українсько-російська типографська клавіатурна розкладка
У стандартній маківській українській розкладці є фішка: якщо натиснути альт+і, то введеться буква и. Це дає змогу залишити одну розкладку замість двох.

Я звик ще з часів PC користуватися [типографською розкладкою Іллі Бірмана](https://ilyabirman.ru/projects/typography-layout/), вона зручніша за маківську. Але постійно дратувало тримати три розкладки і перемикатися між ними.

[Завантажити](https://github.com/alexkolodko/UA-RU-Typography-Keyboard-Layout/raw/dcce2c981fe350ab344343f7cea940d3403ff51b/Layouts/1.3.2/Install%20UA-RU-Typo%20Layout%201.3.2.zip)

# Як працює розкладка
Щоб не перемикати розкладки, вирішив об'єднати типографську розкладку і властивості маківської розкладки.

* українсько-російська: за замовчуванням розкладка українська, але під час натискання `альт+і` → `ы`, `альт+є` → `э`, `альт+ї` → `ъ`.
* із затиснутим шифтом виводяться великі літери.

# Встановити на Mac OS X
Потрібно розархівувати і запустити app-файл, слідувати інструкції і включити в налаштуваннях потрібну розкладку.

Якщо не вийшло, завантажити файл `UA-RU Typography.bundle` і скопіювати його в `~/Library/Keyboard Layouts` (у Finder натиснути ⇧⌘G і ввести адресу), розлогінитися, увійти заново. Тепер у налаштуваннях розкладок будуть доступні дві нові, вибирайте собі будь-яку або обидві.

# Встановлення на Windows
* Встановіть [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134). 
* Візьміть `UA–RU–Typography.klc`, що я приклав, відкрийте у програмі та експортуйте як DLL (Project → Build DLL and Setup Package)
* Встановіть розкладку.

# Як зробити свою розкладку
Ви можете за бажання зробити свою власну розкладку:
* на Mac OS X за допомогою програми [Ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele "Ukelele"), це досить просто. Іконки для розкладки треба робити у форматі ICNS і зберігати поруч із файлом із розкладкою ([як зробити іконку ICNS](https://blog.alexkolodko.com/all/icns-icons-mac-os/ "як зробити ICNS-іконку"));
* на Windows [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134)

# Зміни
## 1.3.2
* Прибрав взагалі RU-UA.
* Повернув на клавішу тільди символ `.
* Додав інструкція для Windows.