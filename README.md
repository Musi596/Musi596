<h1 align="center">tw1nz</h1>

<p align="center">
  <b>Backend-инженер.</b> Python · PostgreSQL · асинхронные сервисы.<br/>
  Системы, которые быстро работают под нагрузкой и понятно устроены внутри.<br/>
  <b>Cybersecurity:</b> учусь атаковать и защищать, Red + Blue, цель — Grey Team.
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,postgres,docker,linux,kali,bash,cpp,git&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Kali_Linux-557C93?style=for-the-badge&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/sqlmap-B22222?style=for-the-badge" />
</p>

---

```cpp
#include <string_view>
#include <vector>

struct Developer {
    std::string_view handle;
    std::string_view role;
    std::string_view focus;
    std::vector<std::string_view> backend;
    std::vector<std::string_view> databases;
    std::vector<std::string_view> security;
    std::vector<std::string_view> languages;
    std::vector<std::string_view> tooling;
    std::vector<std::string_view> currently_learning;
    std::string_view principle;
    std::string_view contact;
};

inline const Developer me{
    .handle   = "tw1nz",
    .role     = "Backend Engineer",
    .focus    = "async services, data modeling, query performance",

    .backend  = {"Python", "asyncio", "aiogram 3", "FSM", "Telegram integrations"},
    .databases = {"PostgreSQL + asyncpg: EXPLAIN ANALYZE, indexes, isolation levels, triggers, views"},
    .security = {"Kali Linux", "Nmap", "sqlmap", "reverse engineering"},
    .languages = {"Python", "C++20", "Bash"},
    .tooling  = {"Linux", "Docker", "Git", "VS Code", "PyCharm"},

    .currently_learning = {"Cybersecurity: offensive (red) + defensive (blue) -> grey team"},

    .principle = "Measure first, optimize second.",
    .contact   = "t.me/Sybauzxz",
};

// Competitive programming: Codeforces Musi596 | target: IOI
// Security: learning both sides (attack and defense), reverse engineering, Kali Linux
// Side interests: systems programming, game engines
// Open to: collaboration | Telegram bot backend (Python, aiogram) | HTML/CSS site layouts
```

## 🛡️ Cybersecurity

Осваиваю безопасность с двух сторон: атака и защита. Backend-опыт помогает видеть уязвимости там, где они возникают: в логике приложения, SQL-запросах и конфигурации.

- **Offensive (red):** разведка и сканирование сети (Nmap), поиск и проверка SQL-инъекций (sqlmap), работа в Kali Linux
- **Defensive (blue):** безопасная архитектура backend, валидация ввода, параметризованные запросы, разграничение прав, логирование
- **Reverse engineering:** анализ программ и понимание их внутреннего устройства
- **Цель:** Grey Team, специалист, который понимает обе стороны
- **Правила:** только легальные цели: собственные лаборатории, CTF и учебные платформы

## 🚀 Избранные проект

- **[Company-Support-Bot](https://github.com/Musi596/Company-Support-Bot)** — Telegram-система поддержки для учебного центра программирования SoftClub
  - Стек: Python 3.10+, aiogram 3, asyncpg, PostgreSQL, Docker
  - Тикеты: обращения, жалобы и вопросы со статусами (`open` / `closed`), ответы администратора прямо из бота
  - Диалоги: многошаговые сценарии на FSM (запись на курс, обращение, диалог с AI)
  - AI-консультант: интеграция Mercury 2.5 (Inception API)
  - Админ-функции: рассылки текстом и фото по группам, управление курсами, выгрузка записей в Excel (openpyxl)
  - Структура: модульные хендлеры, отдельные слои для SQL и бизнес-логики, `ruff`, тесты, релиз `v1.2.0`

## 📬 Контакты

[Telegram](https://t.me/twinems) · [Codeforces](https://codeforces.com/profile/moyttac708) 
