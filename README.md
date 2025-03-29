<div align="center">
    <h1>ModHash</h1>
    <p>ModHash это ядро для кастомных подключаемых модулей, написан на `pyrogram`.</p>
    <img alt="code size" src="https://img.shields.io/github/languages/code-size/xnobanonlyzxc/ModHash?style=for-the-badge">
    <img alt="repo stars" src="https://img.shields.io/github/stars/xnobanonlyzxc/ModHash?style=for-the-badge">
    <img alt="repo stars" src="https://img.shields.io/github/commit-activity/w/xnobanonlyzxc/ModHash?style=for-the-badge">
</div>

# Установка
1. [Скачать](https://github.com/xNoBanOnlyZXC/ModHash/releases/latest) архив `ModHash` и `Python` (при первой установке)
2. Установить `Python 3.11.7` (есть в разделе релизов), обязательно галочку на `PATH`
3. Распаковать `ModHash` в любое место
4. Запустить `install_reqs.bat`
5. Запустить `start.bat`

# Функционал
Базовый функционал обеспечивают встроенные модули.

# Модули
Вы можете сами писать свои модули и встраивать в юзербот, для этого есть папка `modules`
Для начала можно использовать `Template.py`:

```python
from pyrogram import Client, filters
from pyrogram.types import Message
from utils.misc import prefix
from utils.scripts import modules_help, requirements
from pyrogram.handlers import MessageHandler

module_name = ''

# Code

async def name(client: Client, message: Message):
    i = 0

# End of code

# MessageHandler(,filters.command('',prefix) & filters.me)
handlers = [

]

# "":"",
modules_help[module_name] = {

}

requirements[module_name] = {
    
}
```
