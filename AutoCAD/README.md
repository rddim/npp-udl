 <details><summary>Български :bulgaria:</summary>
 
## Съдържание
 * [Синтаксис за открояване в Notepad++](#синтаксис-за-открояване-в-notepad-)
 * [Автоматично завършване на команди в Notepad++](#автоматично-завършване-на-команди-в-notepad-)
 * [Използване](#използване-)
 * [Екранни снимки](#екранни-снимки-)
 * [Сваляне](../../../releases/latest) на последната версия

### Синтаксис за открояване в Notepad++ <sup>[↑](#съдържание)</sup>

* **AutoCAD-Linetype.npp.udl.xml** - синтаксис за открояване на описващите елементи във файловете с типове `линии` (_*.lin_) за AutoCAD
* **AutoCAD-Script.npp.udl.xml** - синтаксис за открояване на определени команди в `скрипт` файловете (_*.scr_) за AutoCAD
* **AutoCAD-Shape-Hatch.npp.udl.xml** - синтаксис за открояване на описващите елементи в `shape` файловете (_*.shp_) и типовете `щриховки` (_*.pat_) за AutoCAD

### Автоматично завършване на команди в Notepad++ <sup>[↑](#съдържание)</sup>

* **AutoCAD-Linetype.xml** - автоматично завършване на наличните команди в `AutoCAD-Linetype.npp.udl.xml`<sup><sup><b>[1]</b></sup></sup> при създаване на файлове с прости и сложни типове `линии` (_*.lin_) за AutoCAD
* **AutoCAD-Script.xml** - автоматично завършване на наличните команди в `AutoCAD-Script.npp.udl.xml`<sup><sup><b>[1]</b></sup></sup> при създаване на `скрипт` файлове (_*.scr_) за AutoCAD.

> _За да работи, автоматичното завършване трябва да e разрешено в `Настройки > Предпочитания... > Авто-завършване > Завършване на функции и думи`_
>
> <sup><sup><b>[1]</b></sup></sup> _Синтаксисът за открояване на команди трябва да e наличен в Notepad++_

### Използване <sup>[↑](#съдържание)</sup>

* Файловете от папка _`userDefineLangs`_ се поставят в папка _`\userDefineLangs`_<sup><sup><b>[1]</b></sup></sup> (за версия >= 7.6.4) или се внасят чрез меню `Синтаксис > Дефиниране на синтаксис > Внасяне...`<sup><sup><b>[2]</b></sup></sup> (за коя да е версия)
* Файловете от папка _`autoCompletion`_ се поставят в папка _`\autoCompletion`_<sup><sup><b>[3]</b></sup></sup> (за версия >=7.6.2) или в _`\plugins\APIs`_<sup><sup><b>[4]</b></sup></sup> (за версия =< 7.6.1)

> <sup><sup><b>[1]</b></sup></sup> _При стандартна инсталация папката се намира в `%AppData%\Notepad++\userDefineLangs`_
>
> <sup><sup><b>[2]</b></sup></sup> _При обновяване на наличните такива, те трябва предварително да се премахнат, тъй като се получава дублиране_
>
> <sup><sup><b>[3]</b></sup></sup> _При стандартна инсталация, папкaтa се намира в `C:\Program Files\Notepad++\autoCompletion` или `C:\Program Files (x86)\Notepad++\autoCompletion`_
>
> <sup><sup><b>[4]</b></sup></sup> _При стандартна инсталация, папката се намира в `C:\Program Files\Notepad++\plugins\APIs` или `C:\Program Files (x86)\Notepad++\plugins\APIs`_
>
> _Пълният списък с команди се извежда, чрез натискане на клавиши `Ctrl+Space`_

**_След извършване на горните промени, е препоръчително Notepad++ да се рестартира_**

### Екранни снимки <sup>[↑](#съдържание)</sup>

<details><summary>Щракнете за показване</summary>

* Типове линии (linetype)

![Linetype](/AutoCAD/img/acad-linetype.png?raw=true)

* Скрипт файл (script)

![Script](/AutoCAD/img/acad-script.png?raw=true)

* Форма файл (shape)

![Shape](/AutoCAD/img/acad-shape.png?raw=true)

* Щриховки (hatch)

![Hatch](/AutoCAD/img/acad-hatch.png?raw=tue)
</details>

---
</details>

<details><summary>English :uk:</summary>

## Table of Contents
 * [UDL for AutoCAD in Notepad++](#udl-for-autocad-in-notepad-)
 * [Auto-Completion Functions in Notepad++](#auto-completion-functions-in-notepad-)
 * [Usage](#usage-)
 * [Screenshots](#screenshots-)
 * [Download](../../../releases/latest) the latest release

### UDL for AutoCAD in Notepad++ <sup>[↑](#table-of-contents)</sup>

* **AutoCAD-Linetype.npp.udl.xml** - syntax highlight for `linetypes` files (_*.lin_) for AutoCAD
* **AutoCAD-Script.npp.udl.xml** - syntax highlight for `script` files (_*.scr_) for AutoCAD
* **AutoCAD-Shape-Hatch.npp.udl.xml** - syntax highlight for `shape` files (_*.shp_) and `hatch` types files (_*.pat_) for AutoCAD

### Auto-Completion Functions in Notepad++ <sup>[↑](#table-of-contents)</sup>

* **AutoCAD-Linetype.xml** - auto-completion commands for `AutoCAD-Linetype.npp.udl.xml`<sup><sup><b>[1]</b></sup></sup> when creating `linetypes` (_*.lin_) for AutoCAD
* **AutoCAD-Script.xml** - auto-completion commands for `AutoCAD-Script.npp.udl.xml`<sup><sup><b>[1]</b></sup></sup> when creating `script` files (_*.scr_) for AutoCAD

> _You should enable `Auto-Completion` option in Notepad++ from `Setting > Preferences > Auto-Completion > Function and word completion`_
>
> _The proper syntax highlight should be available in Notepad++_

### Usage <sup>[↑](#table-of-contents)</sup>

* The files from _`userDefineLang`_ folder should be placed in _`\userDefineLang`_<sup><sup><b>[1]</b></sup></sup> folder (for version >=7.6.4) or should be imported by `Language > Define your language... > Import...`<sup><sup><b>[2]</b></sup></sup> menu (for any version)
* The files from _`autoCompletion`_ folder should be placed in _`\autoCompletion`_<sup><sup><b>[3]</b></sup></sup> folder (for version >=7.6.2) or in _`\plugins\APIs`_<sup><sup><b>[4]</b></sup></sup> (for version =< 7.6.1)

> <sup><sup><b>[1]</b></sup></sup> _By regular installation the folder is in `%AppData%\Notepad++\userDefineLangs`_
>
> <sup><sup><b>[2]</b></sup></sup> _If you update the existing UDLs they should be removed firstly because of duplication_
>
> <sup><sup><b>[3]</b></sup></sup> _By regular installation the folder is in `C:\Program Files\Notepad++\autoCompletion` or `C:\Program Files (x86)\Notepad++\autoCompletion`_
>
> <sup><sup><b>[4]</b></sup></sup> _By regular instalation the folder is in `C:\Program Files\Notepad++\plugins\APIs` or `C:\Program Files (x86)\Notepad++\plugins\APIs`_
>
> _The full list of commands can be displayed by pressing `Ctrl+Space`_

**_It is recommended to restart Notepad++ after the changes_**

### Screenshots <sup>[↑](#table-of-contents)</sup>
 <details h2><summary>Click to expand</summary>

* Linetype

![Linetype](/AutoCAD/img/acad-linetype.png?raw=true)

* Script

![Script](/AutoCAD/img/acad-script.png?raw=true)
 
* Shape

![Shape](/AutoCAD/img/acad-shape.png?raw=true)

* Hatch

![Hatch](/AutoCAD/img/acad-hatch.png?raw=tue)

</details>

---
</details>
