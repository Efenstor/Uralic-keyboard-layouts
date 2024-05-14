# Kamassian-keyboard-layout

Linux shell script that installs the Kamassian keyboard layout (Cyrillic characters).

Does install, uninstall and test install. Requires *xmlstarlet*. Hopefully Bourne Shell-compatible.

The CLI is in Russian but everything else, including internal comments, is in English, so it is easily translatable and may be used as a template for those who wish to make their own custom keyboard layout installer.

---

**install_kamassian.sh** - это шелл-скрипт для Линукс, который устанавливает раскладку клавиатуры для камасинского языка (кириллическая транскрипция).

Способен установить, удалить раскладку или проверить наличие уже установленной. Из внешних утилит требуется только *xmlstarlet*. Теоретически совместим с Bourne Shell.

Скрипт можно использовать как заготовку для изготовления установщиков собственных раскладок подобного типа.

Раскладка полностью соответствует обычной русской и может быть использована вместо неё, т.к. все дополнительные знаки получаются при удержании правой клавиши Alt (для заглавных букв, соответственно, правый Alt + Shift).

* *1-й ряд (E)*: **`** ударение, **-** макрон, **+** диерезис
* *2-й ряд (D)*: **у** - ұ, **н** - ӈ, **г** - ғ, **х** - ˣ, **ъ** - ɂ
* *3-й ряд (C)*: **о** - ө, **д** - ԃ, **э** - ә
* *4-й ряд (B)*: **ч** - ӌ, **c** - ҫ, **т** - ԏ

![screenshot](https://github.com/Efenstor/Kamassian-keyboard-layout/assets/11175574/6e712cea-5ce2-4bbd-a4d1-2c0342f54dc7)
