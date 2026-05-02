# edgeofsight_alpha

Альфа‑версия ресурс‑пака для Minecraft Java Edition, созданная специально для мода **`edgeofsight`** и сервера **`AlphaTextureEvent``.

> Это пока что только ресурс‑пак. В будущем сюда добавлю и ссылку на мой мод. Я только начинающий в этом, так что не судите строго.

## Что это

- Изменяет базовые текстуры блоков для создания атмосферы “альфа‑мира”.  
- Не ломает функционал мода `edgeofsight` и `ResourcePackOverrides`.  
- Пак автоматически подключается через сервер, если указан в `server.properties`.

## Как использовать

### Способ 1: через сервер (рекомендуется)

1. Скопируй прямую ссылку на ZIP‑файл с GitHub Releases или `raw`.
2. В `server.properties` сервера укажи:

   ```properties
   resource-pack=https://github.com/murik1889/edgeofsight-assets/raw/main/edgeofsight_alpha.zip
   require-resource-pack=true
   ```

3. Перезапусти сервер.  
4. При подключении клиенты автоматически скачивают пак.

### Способ 2: вручную

1. Загрузи файл `edgeofsight_alpha.zip`.  
2. В Minecraft открой `Options → Resource Packs`.  
3. Нажми на `Open pack folder`,  
4. В открывшуюся папку `resourcepacks` перетащи `edgeofsight_alpha.zip` (или распакуй в папку и подключи её как обычный ресурспак).

## Версия и совместимость

- Текущая версия: **alpha**  
  (значит, это **пока черновая, экспериментальная сборка**, могут быть баги, изменения текстур и механик).  
- Для Minecraft Java Edition, под мой мод `edgeofsight` (murik1889).  
- Поддерживается через `Radmin VPN` локальный сервер.

---
