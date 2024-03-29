<div align="center">
  
  ![Logo](packetwrapper_logo.png)
  
  ---
  
  # Packet Wrapper
  
</div>

***
[Click for download JAR](https://www.mediafire.com/file/fex1xibblktehfs/packetwrapper.jar/file)
***
## Обратная связь
* **[Discord chat](https://discord.gg/GmT9pUy8af)**
* **[ВКонтакте](https://vk.com/itzstonlex)**

***
Данная API позволит максимально удобно управлять пакетами, не используя ни маппинг индексов, ни кучу проверок на версии, и тому подобное.

Ниже предоставлена таблица версий, которые уже адаптированы или находятся в процессе адаптации:

| Версия игры | Статус выполнения |
|------------|-------------------|
| API        | ✅                 |
| 1.15       | ✅                 |
| 1.13       | ⛔                 |
| 1.12       | ✅                 |
| 1.11       | ⛔                 |
| 1.10       | ⛔                 |
| 1.9        | ⛔                 |
| 1.8        | ⛔                 |


Пример создания, обработки и отсылания пакетов:

```java
// Создание пакета.
WrapperPlayServerAnimation serverAnimationPacket = PacketWrapper.getInstance().createPlayServerAnimation();

// Обработка и установка необходимых данных.
serverAnimationPacket.setEntityID(1);
serverAnimationPacket.setAnimation(1);

// Отправление пакета всем игрокам онлайн.
serverAnimationPacket.broadcastPacket();

// Отправление пакета определенному игроку.
serverAnimationPacket.sendPacket(player);
```

---

## SUPPORT ME

<a href="https://www.buymeacoffee.com/itzstonlex" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
