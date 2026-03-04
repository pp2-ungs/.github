# pp2-ungs

Organization for **Professional Project II** (BSc in Information Systems) at **Universidad Nacional de General Sarmiento (UNGS)**.

We collaborate on academic software projects and supporting modules—currently focused on the **TASkOcupado** ecosystem (core, UI, configuration, and external notifiers/services).

## Members

- **Ximena Ebertz** ([@xebertz](https://github.com/xebertz))
- **Gonzalo López** ([@Gonza-JL](https://github.com/Gonza-JL))
- **Lucifer** ([@rondelli](https://github.com/rondelli))

## Repositories

- **[TASkOcupadoCore](https://github.com/pp2-ungs/TASkOcupadoCore)** — TASkOcupado's domain model and core logic. Implements task scheduling and real-time observer pattern notifications with discovery.
- **[TASkOcupadoUI](https://github.com/pp2-ungs/TASkOcupadoUI)** — Desktop interface and controller layer for TASkOcupado. Implements MVC architecture and Observer pattern to handle task assignments and real-time UI updates.
- **[TASkOcupadoConfig](https://github.com/pp2-ungs/TASkOcupadoConfig)** — Configuration and extensibility module for TASkOcupado. Manages dynamic resource loading and external notifier integrations.
- **[EmailNotifier](https://github.com/pp2-ungs/EmailNotifier)** — Dynamic Email notifier for TASkOcupado. Designed for automated discovery and loading, it implements the Observer pattern to deliver task assignment alerts via SMTP.
- **[TelegramNotifier](https://github.com/pp2-ungs/TelegramNotifier)** — Dynamic Telegram notifier for TASkOcupado. Designed for automated discovery and loading, it observes task assignments to deliver instant notifications via Telegram.
- **[AssignmentLogger](https://github.com/pp2-ungs/AssignmentLogger)** — External logging service for TASkOcupado. Implements a direct Observer subscription to track and persist all task assignment history.
