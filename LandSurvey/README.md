## Съдържание
 * [Синтаксис за открояване на геодезически измервания в Notepad++](#синтаксис-за-открояване-на-геодезически-измервания-в-notepad-)
 * [Използване](#използване-)
 * [Поддържани файлове](#поддържани-файлове-)
 * [Открояване на записи](#открояване-на-записи-)
 * [Екранни снимки](#екранни-снимки-)
 * [Сваляне](../../../releases/latest) на последната версия

### Синтаксис за открояване на геодезически измервания в Notepad++ <sup>[↑](#съдържание)</sup>

  * **LandSurveyPlusPlus.npp.udl.xml** – разширен синтаксис за открояване на записи във файлове от геодезически измервания с тотална станция или нивелир

### Използване <sup>[↑](#съдържание)</sup>

Файлът от папка _`userDefineLangs`_ се поставя в папка _`\userDefineLangs`_<sup><sup><b>[1][2]</b></sup></sup> чрез меню `Синтаксис > Потребителски синтаксиси > Отваряне на папката със синтаксиси...` или се внася чрез меню `Синтаксис > Потребителски синтаксиси > Дефиниране на синтаксис > Внасяне...`<sup><sup><b>[3]</b></sup></sup> (за коя да е версия)

> <sup><sup><b>[1]</b></sup></sup> _При стандартна инсталация папката се намира в `%AppData%\Notepad++\userDefineLangs`_
>
> <sup><sup><b>[2]</b></sup></sup> _за версия >= 7.6.4_
>
> <sup><sup><b>[3]</b></sup></sup> _При обновяване на наличният такъв, трябва предварително да се премахне, тъй като се получава дублиране_

### Поддържани файлове <sup>[↑](#съдържание)</sup>

`asc` `csv` `dat` `dek` `dpi` `gsi` `gt7` `htf` `kor` `kpt` `lis` `raw` `sdr` `tnv` `zss`

### Открояване на записи <sup>[↑](#съдържание)</sup>

Открояване на редове, съдържащи записи за:
  * начало на станция – всички изброени файлове <sup><sup><b>[1]</b></sup></sup>
  * буквени кодове `тт/tt/TT` `пт/pt/PT` `рт/rt/RT` `от/ot/OT` `лт/lt/LT` `нр/nr/NR` – всички изброени файлове
  * цифрови кодове `10` `11` `12` `13` `20` – `dek` `gsi`
  * нулево `31..00+00000000` разстояние – `dek` `gsi`
  * име на `Обект:` – `dpi` `kor` `kpt`
  * параметри – `dpi` `kor`
  * нулево `S 0.000` разстояние – `dpi`
  * липса на код след `kod␣` `cd␣` – `dpi`
  * указващ низ за метри и градуси `UNITS M,D` – `gt7`
  * указващ низ за футове и градуси `UNITS F,D` – `gt7`
  * начало `Start-Line`, продължение `Cont-Line` и край `End-Line` на линия – `dat` файлове от *DiNi* нивелир
  * повторени измервания `#####` – `dat` файлове от *DiNi* нивелир
  * коментирани `;` редове – всички изброени файлове <sup><sup><b>[2]</b></sup></sup>

> <sup><sup><b>[1]</b></sup></sup> _без `raw` `tnv` – поради липса на достатъчно файлове за тестване_
>
> <sup><sup><b>[2]</b></sup></sup> _при внасяне в ТПлан тези редове се пропускат автоматично, изключение правят в `dat` файловете от нивелация_
>
> * _кирилицата във файловете от ТПлан за DOS е с MIK кодировка, която по подразбиране не се поддържа от Notepad++. За добавянето ѝ може да прочетете [тук](https://github.com/rddim/npp-shtirlitz-mik)._
>
> * _при някои файлове се наблюдава неправилно открояване на част от съдържанието_

 <details><summary>Благодарности</summary>
 
 * [УАСГ](https://www.uacg.bg/) – гр.София
   * Ръководството на университета
   * инж.Тамара Илиева-Цветкова
 * инж.Атанас Петков
 * колеги
 </details>

### Екранни снимки <sup>[↑](#съдържание)</sup>

<details><summary>Щракнете за показване</summary>

* `asc`

![asc](/LandSurvey/img/file_format_asc.png?raw=tue)

* `csv`

![csv](/LandSurvey/img/file_format_csv.png?raw=true)

* `dat`

![csv](/LandSurvey/img/file_format_dat_dini.png?raw=true)

* `dat`

![csv](/LandSurvey/img/file_format_dat_dini_rpt.png?raw=true)

* `dek`

![csv](/LandSurvey/img/file_format_dek.png?raw=true)

* `dpi`

![csv](/LandSurvey/img/file_format_dpi_cmnt.png?raw=true)

* `dpi`

![csv](/LandSurvey/img/file_format_dpi_kod.png?raw=true)

* `dpi`

![csv](/LandSurvey/img/file_format_dpi_v1.png?raw=true)

* `dpi`

![csv](/LandSurvey/img/file_format_dpi_v2.png?raw=true)

* `gsi`

![csv](/LandSurvey/img/file_format_gsi.png?raw=true)

* `gt7`

![csv](/LandSurvey/img/file_format_gt7.png?raw=true)

* `htf`

![csv](/LandSurvey/img/file_format_htf.png?raw=true)

* `kor`

![csv](/LandSurvey/img/file_format_kor.png?raw=true)

* `kpt`

![csv](/LandSurvey/img/file_format_kpt.png?raw=true)

* `lis`

![csv](/LandSurvey/img/file_format_lis.png?raw=true)

* `raw`

![csv](/LandSurvey/img/file_format_raw.png?raw=true)

* `sdr`

![csv](/LandSurvey/img/file_format_sdr.png?raw=true)

* `tnv`

![csv](/LandSurvey/img/file_format_tnv.png?raw=true)

* `zss`

![csv](/LandSurvey/img/file_format_zss.png?raw=true)
</details>
