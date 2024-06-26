## Клиенты на ПЗ (просроченной задолженности)

**Цель** — составить реестр клиентов, погасивших просроченную задолженность. Определить номер займа у клиента и сформировать группы по дню просрочки.

**Исходные данные** — таблицы в базе данных SQL:

**Skill** — таблица, содержащая данные о группе клиента на дату выгрузки 
- ID клиента — идентификатор клиента,
- ID кредита — идентификатор займа,
- score — баллы клиентского скоринга,
- Дней просрочки — количество дней на ПЗ на дату выгрузки реестра,
- Дата реестра — дата выгрузки реестра
- skill — группа клиента:
  - soft — группа мягкого сбора,
  - hard — группа тяжелого сбора,
- Тип займа — тип продукта:
  - 1 — краткосрочный займ,
  - 0 — долгосрочный займ.
 
**Unical** — таблица, содержащая данные о клиенте 
- ID клиента — идентификатор клиента,
- ID кредита — идентификатор займа,
- GMT — часовой пояс клиента,
- Номер займа — номер займа у клиента,
- Дата рождения — дата рождения клиента,
- Социальный статус — социальный статус клиента:
  - студент,
  - пенсионер,
  - временно не работаю,
  - сотрудник по найму,
  - ИП. 

**Навыки и инструменты** — MS SQL.

