# v2ray-agent (Русская документация)

- [Спасибо JetBrains за лицензию на открытое ПО](https://www.jetbrains.com/?from=v2ray-agent)

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Telegram Канал](https://img.shields.io/badge/Telegram-Channel-blue)](https://t.me/v2rayAgentChannel)
[![Telegram Группа](https://img.shields.io/badge/Telegram-Group-blue)](https://t.me/technologyshare)
[![Официальный сайт](https://img.shields.io/badge/Website-v2ray--agent.com-blue)](https://www.v2ray-agent.com/)
[![Оригинальный репозиторий](https://img.shields.io/badge/Original-Repository-blue)](https://github.com/mack-a/v2ray-agent)

**Быстрая установка Xray-core/sing-box одной командой**

## 🎯 Функциональность

*   **🔧 Поддержка нескольких ядер:** Xray-core и sing-box
*   **📡 Поддержка многих протоколов:** VLESS, VMess, Trojan, Hysteria2, Tuic, NaiveProxy и другие
*   **🔒 Автоматический TLS:** Автоматическое получение и обновление SSL сертификатов
*   **⚙️ Простое управление:** Удобное меню для управления пользователями, портами и конфигурациями
*   **📋 Поддержка подписок:** Создание и управление ссылками подписок
*   **🌐 Управление трафиком:** WireGuard, IPv6, Socks5, DNS, VMess(ws), SNI обратный прокси
*   **🚫 Управление доменами:** Черный список доменов для запрета доступа к сайтам
*   **📥 Управление BT:** Запрет на загрузку P2P контента
*   **📖 Подробнее:** [Официальный сайт](https://www.v2ray-agent.com/), [X/Twitter](https://x.com/v2rayagent)

## 🚀 Быстрый старт

### 📥 Установка (стандартная версия)

```bash
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/fsuhvx2-cmyk/v2ray-agent/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```

**После установки используйте команду:**
```bash
vasma
```

### 🐳 Установка Docker версии

```bash
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/fsuhvx2-cmyk/v2ray-agent/master/shell/docker_reality.sh" && chmod 700 /root/docker_reality.sh && /root/docker_reality.sh
```

**После установки используйте команду:**
```bash
vasmad
```

Подробнее: [Docker Reality инструкция](https://www.v2ray-agent.com/archives/019e1b57-92b3-70ab-8919-cdf8c0bb4fe9)

## 📚 Документация и Руководства

*   [Полное руководство 8-в-1 скрипта](https://www.v2ray-agent.com/archives/1710141233) - от новичка до мастера
*   [Быстрое руководство по настройке](https://www.v2ray-agent.com/archives/1682491479771)
*   [Важные замечания по использованию](https://www.v2ray-agent.com/archives/1679931532764)
*   [Обработка ошибок в скрипте](https://www.v2ray-agent.com/archives/1684115970026)
*   [Руководство по выбору VPS](https://www.v2ray-agent.com/archives/1679975663984)
*   [Hysteria2 для слабых VPS - быстрая установка](https://www.v2ray-agent.com/archives/1697162969693)

## 💬 Сообщество и поддержка

*   **Telegram:** [📢 Канал обновлений](https://t.me/v2rayAgentChannel) | [👥 Группа поддержки](https://t.me/technologyshare)
*   **Сайт:** [🌐 Официальный](https://www.v2ray-agent.com/) | [🔄 Резервный](https://www.592083.xyz/)
*   **Обратная связь:** [🐛 Создать issue](https://github.com/fsuhvx2-cmyk/v2ray-agent/issues)
*   **X/Twitter:** [🐦 @v2rayagent](https://x.com/v2rayagent)

## 💝 Пожертвование

Спасибо за интерес к проекту!

*   [🛒 Покупка VPS как пожертвование](https://www.v2ray-agent.com/categories/vps)
*   [💰 Пожертвование в криптовалюте](https://www.v2ray-agent.com/1679123834836)

## 📄 Лицензия

Проект лицензирован под [AGPL-3.0](LICENSE)

---

## ℹ️ Информация

Это форк оригинального репозитория [mack-a/v2ray-agent](https://github.com/mack-a/v2ray-agent) с добавленной русской документацией.

**Автор оригинального проекта:** [mack-a](https://github.com/mack-a)

**Документация на других языках:**
- [中文 (Китайский)](https://github.com/mack-a/v2ray-agent)
- [English (Английский)](documents/en/README_EN.md)
- [Русский](README.md) ← вы здесь

---

⚠️ **Важно перед началом:**

✅ Убедитесь, что ваш VPS поддерживает необходимые протоколы  
✅ Откройте порты 80 и 443 для получения SSL сертификата  
✅ Подготовьте доменное имя для привязки к VPS  
✅ Используйте Linux ОС (Ubuntu 18.04+, Debian 10+, CentOS 8+)

