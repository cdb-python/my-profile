# [archive.md](http://archive.md) — История на разговорите

## 20 Април 2026

- Настрои MCP (Filesystem + Desktop Commander), D:\\Cloud
- Изгради пълен личен профил
- Научи за Skills, Prompt Engineering, Routines
- Изгради Software Roadmap
- Активира Pro план ($20/мес)
- Настрои автоматичен sync към GitHub repo (Task Scheduler, 3ч)

## 20 Април 2026 (сигурност)

- Разговор за сигурност и prompt injection риска при MCP
- Препоръки: BitLocker на D/Z дискове, Data Controls в [Claude.ai](http://Claude.ai)

## 20 Април 2026 (bootstrap fix)

- Chris хвана грешка: правилото "Desktop Commander първо" трябва да е в userPreferences
- userPreferences обновени с 1→2 приоритетно правило

## 21 Април 2026 (Android sync)

- Нов GitHub repo `cdb-python/my-profile` (публичен)
- sync_repo.ps1 + Task Scheduler (ClaudeProfileSync)
- Потвърдено от Android ✅

## 21 Април 2026 (портфолио)

- Revolut портфолио документирано с реални данни
- Решение за реинвестиране на XAU ($623.60) в съществуващи позиции

## 21 Април 2026 (стратегия + профил 2.0)

- Добавена секция Поведение и личност
- Портфолио стратегия с Lyn Alden Three Pillar логика
- CLS отхвърлен (overvalued)

## 22 Април 2026 (хранене и добавки)

- Хранителен протокол финализиран с тайминг
- D3 удвоен → кръвен тест 22 юли 2026
- Омега-3 механизъм изяснен
- EAA vs BCAA анализ

## 22 Април 2026 (финансова стратегия)

- GEV blowout Q1 earnings (+13% интрадей, +75% YTD)
- Философия на фолиото финализирана — compounding vehicle
- Финализирано фолио: MU, CCJ, GEV, VRT, VST, FIX, HUT, TSM, NVDA, IESC
- Файл: `D:\Cloud\folio_plan_final_22042026.txt`

## 23 Април 2026 (The Ensemble)

- Концептът документиран
- MVP стратегия: залата е доказателство, не таван

## 23 Април 2026 (сигурност + технически fix)

- Файловете преименувани на ASCII
- Google 2FA напълно настроен
- Gist премахнат изцяло, GitHub raw URL единствен fallback
- Профил 2.0 план дискутиран

## 23 Април 2026 (хранителен метод)

- Пълна система за хранителни режими документирана
- intake_form.html създаден
- ЯМР/ЕМГ анализ — механизъм на омега-3 непоносимостта изяснен

## 24 Април 2026 (здраве — нерви, студ, добавки)

- B витамини финализирани (methylcobalamin отделно, B1/ALA пропуснати)
- NIR лампа концепт добавен
- Студ/нерви механизъм документиран

## 24 Април 2026 (профил реструктуризация — Профил 2.0 ✅)

- my_profile.md (\~50KB монолит) разделен на D:\\Cloud\\profile\\ структура
- Файлове: [personality.md](http://personality.md), [health.md](http://health.md), [nutrition.md](http://nutrition.md), [training.md](http://training.md), [finances.md](http://finances.md), [tech.md](http://tech.md), [business.md](http://business.md), [archive.md](http://archive.md)
- [personality.md](http://personality.md) (\~7.6KB) — зарежда се при всеки разговор вместо целия профил
- Правила за запис добавени в [personality.md](http://personality.md) (кое в кой файл)
- userPreferences обновени да сочат към D:\\Cloud\\profile\\personality.md

## 24 Април 2026 (сън данни — корекция)

- Открита грешка в [health.md](http://health.md): средният сън 4.8ч беше изчислен от сегменти, не от нощи
- Анализ на суровите данни от Z:\\Syncthing-s22\\Download\\Samsung Health (com.samsung.shealth.sleep CSV)
- Реални стойности: avg 7.12ч (Oct24-Apr26) | 6.94ч (последни 12мо) — съвпадат с часовника (6h43m)
- Feb26 дъно: 6.49ч (не 3.5ч) | Тренд: Nov25(7.43ч) → Apr26(6.05ч)
- Преоценка: КАЧЕСТВЕН дефицит, не количествен. Sleep Score 58/100, Physical Recovery 54%
- Ново заключение: тренировъчна честота е приоритет №1 — всички останали метрики зависят от нея
- [health.md](http://health.md) обновен, backup: health_backup_20260424.md

## 25 Април 2026 (Windows оптимизация + Bitcoin Core fix)

- Пълна системна диагностика: CPU/RAM/дискове/процеси/мрежа
- **Bitcoin Core fix:** нодът не стартираше — добавен `prune=153600` в bitcoin.conf. Нодът тръгна и синхронизира.
- [**tech.md**](http://tech.md) **коригиран:** ADATA е един 954GB диск с 2 партиции (не 2 отделни SSD-та), добавени Bitcoin Core v30.0.0, Syncthing, Tailscale, IIS/cdb-webdav
- **Startup cleanup:** премахнати/disabled — BTC Core.lnk дубликат, Edge AutoLaunch, WingetUI, AMDNoiseSuppression, MiniTool, GPU Tweak III, ASUS Armoury Crate tasks и services
- **Оптимизации:** SysMain disabled, Update cache изчистен (+5.2GB), DISM WinSxS cleanup (-5.5GB на WinSxS), общо \~4.4GB свободно на C:
- **Мрежа:** латентност 14ms, Tailscale работи (S22 direct), Bitcoin Core портове ОК
- **IIS/cdb-webdav:** стар WebDAV сървър настроен с Copilot — не е malware, pending cleanup след Macrium backup
- **RAM XMP:** Patriot 2x32GB работи на 2933MHz — XMP не е активиран в BIOS (todo)
- Chrome Remote Desktop: грешно спрян и върнат — умишлено запазен
