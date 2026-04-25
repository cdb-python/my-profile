# [tech.md](http://tech.md)

## Хардуер

КомпонентДетайлCPUAMD Ryzen 9 5900X (12 ядра / 24 нишки)Дънна платкаASUS TUF GAMING X570-PLUS (WI-FI)RAM64 GB DDR4 (2 стика — Patriot, 2933 MHz, XMP не е активиран)GPU2x AMD Radeon RX 6800 XT (16GB GDDR6)PSU850WSSD 1Samsung 970 EVO 250GB (C:)SSD 2ADATA SX8100NP 954GB — 2 партиции: D: (\~754GB) и E: (\~200GB)HDD2x WD 14TB (X:, Y:) — Storage Space 13TB (Z:)МишкаLogitech G502КлавиатураVANTAR MXОСWindows 11 Pro 25H2 (Build 26200.7171)Node.jsv24.13.0МониторLG OLED48C34LA — 48", 4K, 120HzАудиоLogitech Z906 5.1

## Рутер

ПараметърДетайлМоделTP-Link Archer AX53 (AX3000 WiFi 6)FirmwareАвгуст 2025WiFi5GHz only, WPA2-PSK\[AES\]2.4GHzИзключенRemote ManagementDisabledPort ForwardingПразно — нищо не е expose-натоUPnPВключен — pending изключванеAdmin панелHTTP + HTTPS (192.168.0.1)

## Claude Setup

- **План:** Pro ($20/мес) — активиран 20 Април 2026
- **Sonnet:** ежедневна работа, MCP операции, разговори
- **Opus:** финансов анализ, сложни стратегии, дълбоки анализи

## Активни MCP сървъри

- Filesystem — достъп до D:\\Cloud
- Desktop Commander — терминал, файлове
- PDF Viewer
## Активен Софтуер

ПрограмаДетайлBitcoin Core v30.0.0Pruned node, data dir E:\\Bitcoin Core, prune=153600SyncthingФайлова синхронизация PC↔Android, стартира при логинTailscaleVPN mesh — ryzen9-5900x (100.75.141.9), cdb-s22 (100.114.168.55), i3-8350k (100.124.20.42)Chrome Remote DesktopОтдалечен достъп — Running/Automatic, умишлено запазенIIS / cdb-webdavСтар WebDAV на порт 80, настроен с Copilot — pending cleanup след Macrium backup

## Профил файлове

- `D:\Cloud\profile\` — активна структура (пише Claude)
- `D:\Cloud\my_profile.md` — стар монолитен файл (архив, не се ползва)
- GitHub repo raw URL: `https://raw.githubusercontent.com/cdb-python/my-profile/main/my_profile.md`
- `D:\Cloud\sync_repo.ps1` — push към GitHub (Task Scheduler на 3ч)

## Software Roadmap

ИнструментЗащоСтатусПрофил 2.0Разделен на D:\\Cloud\\profile\\ структура✅ ГотовоGitHub repo privateprivate + Android fallback без raw URL🔜 ПланираноGmail MCPПише/чете мейли с Claude🔜 СледващоSQLite MCPБаза данни за клиенти от залата🔜 При SkillsObsidianВизуализация на D:\\Cloud🔜 Когато искашn8nАвтоматизации🔜 По-късноClaude CodeCLI среда, slash команди, hooks🔜 Когато е моментIIS cleanupМахане на cdb-webdav след Macrium backup🔜 PendingRouter UPnPИзключване от admin панела🔜 Pending

## Skills Roadmap

- Тренировъчна програма по клиентски параметри
- Хранителен режим по метода на Chris
- Клиентски профил и анализ
- Добавъчен протокол (Атия/Синклеър/Лайън стандарти)
