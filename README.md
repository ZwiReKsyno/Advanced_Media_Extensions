
## Advanced Media Extensions DTS, EAC3 и TrueHD с поддержкой 5.1: 
позволяет использовать кодеки AAC и HEVC и их лицензию в пакете AME до версии DSM 7.2. Этот патчер активирует Advanced Media Extensions 3.0 без необходимости входа в учетную запись (вам все равно потребуется действительный серийный номер. Если вам нужно подделать серийный номер, используйте Synocodectools). При установке исправления этой лицензии   необходимо удалить и переустановить его снова. Для установки   его установка не является обязательной.

(Используйте на свой страх и риск, хотя это было сделано для максимальной безопасности, могут быть ошибки. (Crack для XPEnology и Synology без лицензии AME).

*(Use at your own risk, although it has been done to be as safe as possible, there could be errors. (Crack for XPEnology and Synology without AME's license).*

## Зависимости:
- DSM 7.0-41890 (и выше)
- Видеостанция 2.4.6-1594 (и выше)
- SynoCommunity FFMPEG 6.0.2. (и выше) ( помощь )
- Advanced Media Extensions 1.0.0-50001 (и выше). (Лицензия в AME должна быть ЗАГРУЖЕНА и АКТИВИРОВАНА.)

## Поддерживаемые/неподдерживаемые сценарии:
- DTS или EAC3, TrueHD или AAC + Любой нестандартный формат видео: ✅
- нет DTS, нет EAC3, нет TrueHD, нет AAC + HEVC: ✅
- DTS или EAC3, TrueHD или AAC (5.1 или 7.1) + HEVC: ✅
- DSM 7.XX: ✅
- С устройствами DS-XXX PLAY или устройствами с низким энергопотреблением: ✅ (Я рекомендую установить Simplest  . Для Advanced требуется более мощный процессор или наличие графического процессора для двоичного файла FFmpeg для декодирования HEVC.)
- DSM 6.2:⚠️Установщик не поддерживает эту версию.
*(На устройствах с низким энергопотреблением у вас будет только ремультиплексирование звука или возможность воспроизводить его только без перекодирования.)*

## Инструкции:
- Убедитесь, что вы соответствуете необходимым зависимостям
- Установите SynoCommunity ffmpeg https://synocommunity.com/#easy-install
- Подключитесь к своему NAS с помощью SSH (требуется пользователь с правами администратора)
- Используйте команду sudo -i для переключения на пользователя root
- Используйте следующую команду (Команда установки) для выполнения патча
- Вам придется перезапускать патчер каждый раз при обновлении VideoStation, Advanced Media Extensions и DSM.

# ИСПОЛЬЗОВАНИЕ:
Команда установки: 
- `bash -c "$(curl "https://raw.githubusercontent.com/ZwiReKsyno/Advanced_Media_Extensions/main/installer.sh")"`

