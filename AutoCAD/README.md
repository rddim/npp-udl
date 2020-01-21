 <details><summary>Български :bulgaria:</summary>
 
## Съдържание
 * [Синтаксис за открояване в Notepad++](#синтаксис-за-открояване-в-notepad-)
 * [Автоматично завършване на команди в Notepad++](#автоматично-завършване-на-команди-в-notepad-)
 * [Използване](#използване-)
 * [Екранни снимки](#екранни-снимки-)
 * [Сваляне](../../../releases/latest) на последната версия

### Синтаксис за открояване в Notepad++ <sup>[↑](#съдържание)</sup>

* **AutoCAD-LPSS.udl.xml** – синтаксис за открояване на описващите елементи във файловете с типове `линии` (_*.lin_), типовете `щриховки` (_*.pat_), команди в `скрипт` (_*.scr_) и елементи в `shape` (_*.shp_) за AutoCAD

### Автоматично завършване на команди в Notepad++ <sup>[↑](#съдържание)</sup>

* **AutoCAD-LPSS.xml** – автоматично завършване на наличните команди в `AutoCAD-LPSS.udl.xml`<sup><sup><b>[1]</b></sup></sup> при създаване на файлове с прости и сложни типове `линии` (_*.lin_) и `скрипт` (_*.scr_) файлове  за AutoCAD.

> _За да работи, автоматичното завършване трябва да e разрешено в `Настройки > Предпочитания... > Авто-завършване > Завършване на функции и думи`_
>
> <sup><sup><b>[1]</b></sup></sup> _**AutoCAD-LPSS.udl.xml** синтаксисът трябва да e наличен в Notepad++_

### Използване <sup>[↑](#съдържание)</sup>

* Файлът от папка _`userDefineLangs`_ се поставят в папка _`\userDefineLangs`_<sup><sup><b>[1][2]</b></sup></sup> чрез меню `Синтаксис > Потребителски синтаксиси > Отваряне на папката със синтаксиси...` или се внася чрез меню `Синтаксис > Потребителски синтаксиси > Дефиниране на синтаксис > Внасяне...`<sup><sup><b>[3]</b></sup></sup> (за коя да е версия)
* Файлът от папка _`autoCompletion`_ се поставя в папка _`\autoCompletion`_<sup><sup><b>[4]</b></sup></sup> (за версия >=7.6.2) или в _`\plugins\APIs`_<sup><sup><b>[5]</b></sup></sup> (за версия =< 7.6.1)

> <sup><sup><b>[1]</b></sup></sup> _При стандартна инсталация папката се намира в `%AppData%\Notepad++\userDefineLangs`_
>
> <sup><sup><b>[2]</b></sup></sup> _за версия >= 7.6.4_
>
> <sup><sup><b>[3]</b></sup></sup> _При обновяване на наличният такъв, трябва предварително да се премахне, тъй като се получава дублиране_
>
> <sup><sup><b>[4]</b></sup></sup> _При стандартна инсталация, папкaтa се намира в `C:\Program Files\Notepad++\autoCompletion` или `C:\Program Files (x86)\Notepad++\autoCompletion`_
>
> <sup><sup><b>[5]</b></sup></sup> _При стандартна инсталация, папката се намира в `C:\Program Files\Notepad++\plugins\APIs` или `C:\Program Files (x86)\Notepad++\plugins\APIs`_
>
> _Пълният списък с команди се извежда, чрез натискане на клавиши `Ctrl+Space`_

**_След извършване на горните промени, е препоръчително Notepad++ да се рестартира_**

### Екранни снимки <sup>[↑](#съдържание)</sup>

<details><summary>Щракнете за показване</summary>

* Типове линии (linetype)

![Linetype](/AutoCAD/img/acad-linetype.png?raw=true)

* Щриховки (pattern/hatch)

![Hatch](/AutoCAD/img/acad-hatch.png?raw=tue)

* Скрипт файл (script)

![Script](/AutoCAD/img/acad-script.png?raw=true)

* Форма файл (shape)

![Shape](/AutoCAD/img/acad-shape.png?raw=true)

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

* **AutoCAD-LPSS.udl.xml** – syntax highlight for `linetypes` (_*.lin_), `hatch pattern` (_*.pat_), `script` (_*.scr_), and `shape` (_*.shp_) files for AutoCAD

### Auto-Completion Functions in Notepad++ <sup>[↑](#table-of-contents)</sup>

* **AutoCAD-LPSS.xml** – auto-completion commands for `AutoCAD-LPSS.udl.xml`<sup><sup><b>[1]</b></sup></sup> when creating `linetypes` (_*.lin_) and `script` (_*.scr_) files for AutoCAD

> _The `Auto-Completion` option should be enabled in Notepad++ from `Setting > Preferences > Auto-Completion > Function and word completion`_
>
> <sup><sup><b>[1]</b></sup></sup> _The **AutoCAD-LPSS.udl.xml** language should be available in Notepad++_

### Usage <sup>[↑](#table-of-contents)</sup>

* The file from _`userDefineLangs`_ folder should be placed in _`\userDefineLangs`_<sup><sup><b>[1]</b></sup></sup><sup><sup><b>[2]</b></sup></sup> folder by `Language > User Defined Language > Open User Defined Language folder...` or should be imported by `Language > User Defined Language > Define your language... > Import...`<sup><sup><b>[3]</b></sup></sup> menu (for any version)
* The file from _`autoCompletion`_ folder should be placed in _`\autoCompletion`_<sup><sup><b>[4]</b></sup></sup> folder (for version >=7.6.2) or in _`\plugins\APIs`_<sup><sup><b>[5]</b></sup></sup> (for version =< 7.6.1)

> <sup><sup><b>[1]</b></sup></sup> _By regular installation the folder is in `%AppData%\Notepad++\userDefineLangs`_
>
> <sup><sup><b>[2]</b></sup></sup> _(for version >=7.6.4)_
>
> <sup><sup><b>[3]</b></sup></sup> _If you update the existing UDL it should be removed firstly because of duplication_
>
> <sup><sup><b>[4]</b></sup></sup> _By regular installation the folder is in `C:\Program Files\Notepad++\autoCompletion` or `C:\Program Files (x86)\Notepad++\autoCompletion`_
>
> <sup><sup><b>[5]</b></sup></sup> _By regular instalation the folder is in `C:\Program Files\Notepad++\plugins\APIs` or `C:\Program Files (x86)\Notepad++\plugins\APIs`_
>
> _The full list of commands can be displayed by pressing `Ctrl+Space`_

**_It is recommended to restart Notepad++ after the changes_**

### Screenshots <sup>[↑](#table-of-contents)</sup>
 <details h2><summary>Click to expand</summary>

* Linetype

![Linetype](/AutoCAD/img/acad-linetype.png?raw=true)

* Hatch Pattern

![Hatch](/AutoCAD/img/acad-hatch.png?raw=tue)

* Script

![Script](/AutoCAD/img/acad-script.png?raw=true)
 
* Shape

![Shape](/AutoCAD/img/acad-shape.png?raw=true)

</details>

---
</details>
