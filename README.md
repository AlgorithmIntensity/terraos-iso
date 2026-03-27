# TerraOS

Минимальный Linux дистрибутив на BusyBox.

## Особенности

- Размер ISO: ~15 MB
- Ядро: Linux-TerraOS
- Оболочка: ash (BusyBox)
- Сеть: DHCP, wget, curl

## Быстрый старт

```bash
# Запуск в QEMU
qemu-system-x86_64 -cdrom terraos.iso -m 256 -nographic

# После загрузки
ifconfig eth0 up
udhcpc -i eth0
```

Скачать ISO можно [здесь](https://github.com/AlgorithmIntensity/terraos-iso/releases) или [здесь](https://github.com/AlgorithmIntensity/terraos-iso/blob/main/terraos.iso)
