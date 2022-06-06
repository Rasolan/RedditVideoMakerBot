# Reddit Video Maker Bot RU 🎥

https://user-images.githubusercontent.com/6053155/170525726-2db23ae0-97b8-4bd1-8c95-00da60ce099f.mp4

All done WITHOUT video editing or asset compiling. Just pure ✨programming magic✨.

Created by Lewis Menelaws & [TMRRW](https://tmrrwinc.ca)

[<picture>

  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/6053155/170528535-e274dc0b-7972-4b27-af22-637f8c370133.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/6053155/170528582-cb6671e7-5a2f-4bd4-a048-0e6cfa54f0f7.png">
  <img src="https://user-images.githubusercontent.com/6053155/170528582-cb6671e7-5a2f-4bd4-a048-0e6cfa54f0f7.png" width="350">
</picture>](https://tmrrwinc.ca)

## Motivation 🤔

These videos on TikTok, YouTube and Instagram get MILLIONS of views across all platforms and require very little effort. The only original thing being done is the editing and gathering of all materials...

... but what if we can automate that process? 🤔

## Disclaimers 🚨

- Это чисто для развлекательных целей.
- **В настоящий момент** этот репозиторий не будет пытаться загрузить этот контент через этого бота. Это даст вам файл, который вам нужно будет загрузить вручную. Это делается для того, чтобы избежать каких-либо проблем с правилами сообщества.

## Requirements

-   Python 3.6+
-   Playwright (это должно установиться автоматически во время установки)

## Installation 👩‍💻

1. Clone this repository

2. Run `pip3 install -r requirements.txt`
3. Run `playwright install` and `playwright install-deps`.
4. 
	4a **Автоматическая установка**: запустите `python3 main.py` и введите 'yes', чтобы активировать помощника по установке.

4b **Ручная установка**: переименуйте `.env.template` в `.env` и замените все значения соответствующими полями. Чтобы получить ключи Reddit (**обязательно**), посетите [страницу приложений Reddit.](https://www.reddit.com/prefs/apps) TL; DR настройте приложение, которое является «скриптом». Скопируйте свои ключи в файл `.env` вместе с тем, использует ли ваша учетная запись двухфакторную аутентификацию.

5. Запустите `python3 main.py` (если вы не выбрали автоматическую установку, установщик автоматически запустит main.py)
7. Наслаждайтесь 😎


Если вы хотите увидеть более подробное руководство, обратитесь к официальной [документации] (https://luka-hietala.gitbook.io/documentation-for-the-reddit-bot/).
\*Документация все еще разрабатывается и дорабатывается, пожалуйста, будьте терпеливы, пока мы меняем/добавляем новые знания!

## Участие и способы улучшения 📈

В своем текущем состоянии этот бот делает именно то, что ему нужно. Тем не менее, можно сделать много улучшений.

Я попытался упростить код, чтобы любой мог прочитать его и внести свой вклад с любым уровнем навыков. Не стесняйтесь :) внесите свой вклад!

- [x] Разрешение пользователям выбирать ветку Reddit вместо рандомизации.
- [ ] Разрешение пользователям выбирать фон вместо фона Minecraft.
- [x] Разрешение пользователям выбирать между любым субреддитом.
- [ ] Разрешение пользователям изменять голос.
- [ ] Создание лучшей документации и добавление интерфейса командной строки.

Пожалуйста, ознакомьтесь с нашими [правилами участия](CONTRIBUTING.md) для получения более подробной информации.
