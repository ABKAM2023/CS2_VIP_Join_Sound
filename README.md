**[VIP] Join Sound** - добавляет возможность проигрывания звука для всех игроков при подключении VIP-игрока.

В `groups.ini` добавьте следующее:

```ini
  // Путь к звуковому файлу, который будет воспроизводиться при подключении VIP-игрока
  // Формат: "JoinSound" "путь_к_файлу"
  "JoinSound" "sounds/music/vip_join.vsnd_c"
```
В файл `vip.phrases.txt` добавьте следующее:
```ini
    "JoinSound"
    {
        "en"    "Join Sound"
        "ru"    "Звук при подключении"
    }
```
Требования: [VIP CORE](https://csdevs.net/resources/vip-core.511/)
