<p align="center">
  <img src="assets/cover.svg" alt="Indie Solo Playbooks" width="100%" />
</p>

<p align="center">
  Русский · <a href="en/README.md">English</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/playbooks-14-C9A24A?style=flat-square" alt="14 playbooks" />
  <img src="https://img.shields.io/badge/skills-7-C9A24A?style=flat-square" alt="7 skills" />
  <img src="https://img.shields.io/badge/updated-10%20Sep%202026-111111?style=flat-square" alt="Updated 10 Sep 2026" />
  <img src="https://img.shields.io/badge/lang-RU%20%2B%20EN-444444?style=flat-square" alt="Russian and English" />
  <img src="https://img.shields.io/badge/format-SKILL.md-2A261C?style=flat-square" alt="SKILL.md" />
</p>

<p align="center"><strong>Не мотивация.</strong> Публичные системы запуска и роста от людей, которые в 2026 всё ещё шипят и пишут, как это делают.</p>

---

## Зачем этот репозиторий

Два слоя.

1. **Плейбуки** — сборники открытых тезисов одного основателя: философия, запуск, каналы, ошибки, 30 дней, источники.
2. **Скилы** — короткие процедуры для агентов в формате [Agent Skills](https://agentskills.io) (`SKILL.md`). Агент не тащит все 14 текстов в каждый чат.

Критерий отбора: соло / почти соло, живые продукты в 2025–2026, публичные цифры и повторяемый метод — не разовый хайп.

Цифры внутри — их публичные заявления и скрины, не аудит. Русские файлы — источник правды. Английские — зеркало в [`en/`](en/README.md).

---

## Плейбуки

| # | Кто | Хендл | Суть системы |
| ---: | --- | --- | --- |
| 01 | [Jack Friks](playbooks/01-jack-friks.md) | [@jackfriks](https://x.com/jackfriks) | Аудитория сначала, прогрев, запуск как событие |
| 02 | [Marc Lou](playbooks/02-marc-lou.md) | [@marclou](https://x.com/marclou) | Ship or Die: портфель, скорость, один канал |
| 03 | [Pieter Levels](playbooks/03-pieter-levels.md) | [@levelsio](https://x.com/levelsio) | Шипить грязно, жить в публике, ловить волну |
| 04 | [Tony Dinh](playbooks/04-tony-dinh.md) | [@tdinh_me](https://x.com/tdinh_me) | Один продукт — один канал. X как движок |
| 05 | [Danny Postma](playbooks/05-danny-postma.md) | [@dannypostma](https://x.com/dannypostma) | Paid + продукт, который сам себя показывает |
| 06 | [Nico Jeannen](playbooks/06-nico-jeannen.md) | [@nico_jeannen](https://x.com/nico_jeannen) | Meta ads и креатив, не треды |
| 07 | [Tibo](playbooks/07-tibo.md) | [@tibo_maker](https://x.com/tibo_maker) | Портфель и партнёрства, не один хит |
| 08 | [Rob Hallam](playbooks/08-rob-hallam.md) | [@robj3d3](https://x.com/robj3d3) | Сначала спрос, потом код. Валидация до сборки |
| 09 | [Alex Nguyen](playbooks/09-alex-nguyen.md) | [@alexcooldev](https://x.com/alexcooldev) | Объём в коротких видео, прибыль за неделю |
| 10 | [Yasser Elsaid](playbooks/10-yasser-elsaid.md) | [@yasser_elsaid_](https://x.com/yasser_elsaid_) | Прозрачный MRR как канал и доверие |
| 11 | [Nevo David](playbooks/11-nevo-david.md) | [@wickedguro](https://x.com/wickedguro) | Продавать результат, не «ещё один Buffer» |
| 12 | [Dan Kulkov](playbooks/12-dan-kulkov.md) | [@DanKulkov](https://x.com/DanKulkov) | Одна аудитория, простое решение, маркетинг вне X |
| 13 | [Damon Chen](playbooks/13-damon-chen.md) | [@damonchen](https://x.com/damonchen) | Домен = запрос. X стартует, Google масштабирует |
| 14 | [Ilias Ism](playbooks/14-illyism.md) | [@illyism](https://x.com/illyism) | SEO ловит спрос. Сначала продажи руками |

---

## Скилы для агентов

Формат [agentskills.io](https://agentskills.io): папка + `SKILL.md`. Работает в Claude Code, Cursor, Codex, Copilot, Gemini CLI и других, кто читает стандарт.

Каталог: [`skills/`](skills/) · как грузить: [`AGENTS.md`](AGENTS.md)

| Скил | Когда включать |
| --- | --- |
| [indie-solo-router](skills/indie-solo-router/SKILL.md) | непонятно, какую систему брать |
| [indie-launch-x](skills/indie-launch-x/SKILL.md) | прогрев и запуск в X |
| [indie-launch-seo](skills/indie-launch-seo/SKILL.md) | поиск, домены, AEO |
| [indie-launch-shortform](skills/indie-launch-shortform/SKILL.md) | TikTok / UGC |
| [indie-launch-ads](skills/indie-launch-ads/SKILL.md) | Meta ads, креатив |
| [indie-validate-offer](skills/indie-validate-offer/SKILL.md) | идея ещё не продаётся |
| [indie-ship-portfolio](skills/indie-ship-portfolio/SKILL.md) | много маленьких продуктов |

Поставить локально:

```bash
cp -R skills/* ~/.claude/skills/     # Claude Code
cp -R skills/* ~/.agents/skills/     # Codex и часть CLI
cp -R skills/* ~/.cursor/skills/     # Cursor
```

Или открыть репозиторий как проект — `AGENTS.md` уже указывает на скилы. Адаптеры: [`CLAUDE.md`](CLAUDE.md), [`.github/copilot-instructions.md`](.github/copilot-instructions.md).

---

## Как читать

В каждом плейбуке один и тот же каркас:

1. **Кто и цифры** — что человек сам публикует в 2026
2. **Философия** — через что он фильтрует идеи
3. **Запуск и маркетинг** — повторяемые ходы, не «пость 5 раз в день»
4. **Ошибки** — что он сам называет слитым временем
5. **30 дней** — сжатый план в его стиле
6. **Источники** — ссылки на треды, статьи, Stripe-профили

Не читать всё подряд. Выбрать одну систему под свой канал и пройти 30 дней только по ней. Агенту — сначала скил, потом один плейбук.

---

## Чего тут нет

- Нет секретных фич и слитых персональных переписок
- Нет универсального «лучшего» метода — у каждого своя игра
- Нет обещания, что их цифры правда. Это компиляция их слов

---

<p align="center">
  <sub>Живой архив · обновлено 10 сентября 2026 · <a href="playbooks/01-jack-friks.md">плейбуки</a> · <a href="skills/">скилы</a> · <a href="en/README.md">English</a></sub>
</p>
