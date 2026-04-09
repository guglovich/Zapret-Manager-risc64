# Zapret Manager for riscv64

Форк [Zapret Manager by StressOzz](https://github.com/StressOzz/Zapret-Manager) с поддержкой **riscv64** архитектуры (OpenWRT SNAPSHOT).

## Установка

```bash
sh <(wget -O - https://raw.githubusercontent.com/guglovich/Zapret-Manager-risc64/refs/heads/main/Zapret-Manager.sh)
```

После установки запуск через:
```bash
zms
```

## Изменения

- Добавлена поддержка архитектуры **riscv64**
- TG WS Proxy Go использует репозиторий `guglovich/-tg-ws-proxy-Manager-go-risc64`
- TG WS Proxy Rust использует репозиторий `guglovich/tg-ws-proxy-rs-risc64`

## Поддерживаемые архитектуры

| Архитектура | TG WS Proxy Go | TG WS Proxy Rust |
|-------------|----------------|-------------------|
| aarch64 | ✅ | ✅ |
| armv7 | ✅ | ✅ |
| x86_64 | ✅ | ✅ |
| mipsel_24kc | ✅ | ✅ |
| mips_24kc | ✅ | ❌ |
| riscv64 | ✅ | ✅ |

## Оригинал

Оригинальный проект: [StressOzz/Zapret-Manager](https://github.com/StressOzz/Zapret-Manager)
