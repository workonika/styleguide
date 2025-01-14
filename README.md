# Руководство Google по стилям

Каждый крупный open-source проект имеет собственное руководство по стилям: набор соглашений 
(иногда произвольный) о том, как писать код для этого проекта. Гораздо легче понять большую кодовую базу, 
когда весь код в ней написан в едином стиле. 

“Стиль” охватывает множество моментов, от “использовать camelCase для имен переменных” к
“никогда не использовать глобальные переменные” и до “никогда не использовать исключения.” 
Этот проект (ссылка на оригинал статьи прим.переводчика)
([google/styleguide](https://github.com/google/styleguide)) ведет к руководящим принципам по стилям,
которые используются для кода в компании Гугл. Если вы модифицируете проект, который инициирован в Гугл,
возможно вам укажут на данную страницу, чтобы ознакомиться с руководством по стилю, который применяется
в данном проекте.

Данный проект содержит следующие руководства по стилям:

*   [AngularJS Style Guide][angular]
*   [Common Lisp Style Guide][cl]
*   [C++ Style Guide][cpp]
*   [C# Style Guide][csharp]
*   [Go Style Guide][go]
*   [HTML/CSS Style Guide][htmlcss]
*   [JavaScript Style Guide][js]
*   [Java Style Guide][java]
*   [Objective-C Style Guide][objc]
*   [Python Style Guide][py]
*   [R Style Guide][r]
*   [Shell Style Guide][sh]
*   [Swift Style Guide][swift]
*   [TypeScript Style Guide][ts]
*   [Vimscript Style Guide][vim]

Этот проект также включает [cpplint][cpplint] - инструмент, чтобы помочь с руководством по стлию, 
и [google-c-style.el][emacs], файл настроек Emacs для стилей Гугл.

Если ваш проект требует, чтобы вы создавали XML, вам может быть полезен
[XML Document Format Style Guide][xml]. В дополнеие к действующим правилам стилей он также включает советы по разработке своих собственных, в противоположность подгонке под существующий формат XML.

Гид по стилям в этом проекте лицензирован под лицензией CC-By 3.0 License, которая
призывает вас делиться этими документами. Смотрите
[https://creativecommons.org/licenses/by/3.0/][ccl] для больших деталей.

Следующий Google гид по стилям существует отдельно от этого проекта:
[Effective Dart][dart].

## Сотрудничество и вклад

За небольшими исключениями, эти гиды по стилям являются копиями внутренних 
гидов по стилям Google, которые помогают разработчикам работать над собственными open source проектами Гугл.
Изменения вначале делаются во внутренних гидах по стилям и со временем копируются сюда.
**Внешние изменения не принимаются**
Пул-реквесты регулярно закрываются без комментариев. Вопросы, 
Changes to the style guides are made to the internal style guides
first and eventually copied into the versions found here. **External
contributions are not accepted.** Pull requests are regularly closed without
comment. Issues that raise questions, justify changes on technical merits, or
point out obvious mistakes may get some engagement and could in theory lead to
changes, but we are primarily optimizing for Google's internal needs.

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>

[cpp]: https://google.github.io/styleguide/cppguide.html
[csharp]: https://google.github.io/styleguide/csharp-style.html
[swift]: https://google.github.io/swift/
[objc]: objcguide.md
[go]: go/
[java]: https://google.github.io/styleguide/javaguide.html
[py]: https://google.github.io/styleguide/pyguide.html
[r]: https://google.github.io/styleguide/Rguide.html
[sh]: https://google.github.io/styleguide/shellguide.html
[htmlcss]: https://google.github.io/styleguide/htmlcssguide.html
[js]: https://google.github.io/styleguide/jsguide.html
[ts]: https://google.github.io/styleguide/tsguide.html
[angular]: https://google.github.io/styleguide/angularjs-google-style.html
[cl]: https://google.github.io/styleguide/lispguide.xml
[vim]: https://google.github.io/styleguide/vimscriptguide.xml
[cpplint]: https://github.com/google/styleguide/tree/gh-pages/cpplint
[emacs]: https://raw.githubusercontent.com/google/styleguide/gh-pages/google-c-style.el
[xml]: https://google.github.io/styleguide/xmlstyle.html
[dart]: https://www.dartlang.org/guides/language/effective-dart
[ccl]: https://creativecommons.org/licenses/by/3.0/
