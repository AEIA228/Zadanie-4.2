# Zadanie 4.2
 
# Отчёт по настройке безопасности

## 1. Обоснование выбора антивирусного ПО

Исследовали три популярных антивируса: Kaspersky, Avast, Windows Defender.

| Антивирус       | Плюсы | Минусы | Бесплатная версия | Потребление ресурсов |
|-----------------|-------|--------|--------------------|-----------------------|
| Kaspersky       | - Высокая эффективность   <br> - Регулярные обновления   <br> - Много функций безопасности | - Платный   <br> - Высокое потребление ресурсов | Нет | Высокое |
| Avast           | - Удобный интерфейс   <br> - Есть бесплатная версия   <br> - Хорошая защита от фишинга | - Навязывает установку доп. ПО   <br> - Реклама в бесплатной версии | Да | Среднее |
| Windows Defender | - Встроен в Windows   <br> - Бесплатный   <br> - Интеграция с системой | - Меньше функций по сравнению с платными аналогами   <br> - Требует настройки для максимальной эффективности | Да | Низкое |

**Выбранный антивирус:** Windows Defender

**Почему выбран именно он:**
Windows Defender был выбран из-за того, что он встроен в Windows, бесплатный и не требует дополнительной установки. Также он хорошо интегрируется с системой и имеет низкое потребление ресурсов, что важно для слабых ПК.

---

## 2. Установка антивируса

### Процесс установки:

- **Где скачали?**
  Windows Defender уже встроен в Windows, поэтому скачивать его не нужно.

- **Что предлагалось установить дополнительно?**
  Ничего, так как Windows Defender является частью операционной системы.

- **Какие опции выбрали?**
  Включили активную защиту и обновили базы данных.

**Скриншоты:**
![alt text](image-1.png)

---

## 3. Первичная настройка безопасности

### Настроенные параметры:

- ✅ Обновление баз данных
- ✅ Включение активной защиты
- ✅ Настройка автоматического сканирования (ежедневно в 2:00)
- ✅ Проведена полная проверка системы
- ✅ Включены следующие функции:
  - [x] Фаерволл
  - [x] Веб-защита/блокировка вредоносных сайтов


![4 2](https://github.com/user-attachments/assets/edc6ce51-f66f-4e7b-8a3d-2c7692f1442c)
![alt text](image.png)

---

## 4. Дополнительные меры безопасности

### Выполненные действия:

- [x] Обновление системы Windows / драйверов
  - **Что сделали:** Запустили Центр обновления Windows и установили все доступные обновления.
  - **Где:** Панель управления -> Центр обновления Windows.

- [x] Смена или установка надёжного пароля на вход
  - **Что сделали:** Установили сложный пароль для учётной записи.
  - **Где:** Панель управления -> Учётные записи пользователей.

- [x] Включение BitLocker для шифрования диска
  - **Что сделали:** Включили BitLocker для защиты данных на системном диске.
  - **Где:** Панель управления -> Система и безопасность -> BitLocker.

- [x] Отключение автозапуска с флешек
  - **Что сделали:** Отключили автозапуск в настройках системы.
  - **Где:** Панель управления -> Автозапуск.

---

## 5. Настройка двухфакторной аутентификации для аккаунтов

### Процесс настройки:

- **Google Аккаунт:**
  - Перешли в настройки аккаунта -> Безопасность -> Двухфакторная аутентификация.
  - Выбрали способ подтверждения (SMS, приложение Google Authenticator).

- **Microsoft Аккаунт:**
  - Перешли в настройки аккаунта -> Безопасность -> Дополнительные параметры безопасности.
  - Включили двухфакторную аутентификацию.

---

## Подводятся итоги:

- **Что нового узнали:**
  - Узнали о важности регулярного обновления антивирусных баз.
  - Поняли, как настроить двухфакторную аутентификацию для разных аккаунтов.

- **Что было непонятно или вызвало трудности:**
  - Некоторые настройки Windows Defender были сложными для понимания.
  - Трудности возникли с настройкой автоматического сканирования.

- **Какие выводы сделали о важности настройки безопасности:**
  - Настройка безопасности является критически важной для защиты данных.
  - Регулярное обновление и использование современных методов аутентификации значительно повышают уровень безопасности.

# Удаление антивируса и работа с реестром Windows

## 1. Удаление антивируса

### Удаление через "Панель управления"

1. **Откройте "Панель управления":**
   - Нажмите `Win + R`, введите `control` и нажмите `Enter`.
   - Перейдите в раздел **"Программы"** > **"Программы и компоненты"**.

2. **Найдите антивирус:**
   - В списке установленных программ найдите ваш антивирус (например, Avast, Kaspersky, Bitdefender).

3. **Удалите антивирус:**
   - Щёлкните правой кнопкой мыши на антивирусе и выберите **"Удалить"**.
   - Следуйте инструкциям мастера удаления.

4. **Перезагрузите компьютер:**
   - После удаления антивируса рекомендуется перезагрузить компьютер, чтобы изменения вступили в силу.

---

### Удаление через "Параметры" (для Windows 10/11)

1. **Откройте "Параметры":**
   - Нажмите `Win + I`, чтобы открыть **"Параметры"**.

2. **Перейдите в раздел "Приложения":**
   - Выберите **"Приложения"** > **"Приложения и возможности"**.

3. **Найдите антивирус:**
   - В списке установленных приложений найдите ваш антивирус.

4. **Удалите антивирус:**
   - Щёлкните на антивирусе и нажмите **"Удалить"**.
   - Подтвердите удаление и следуйте инструкциям.

5. **Перезагрузите компьютер:**
   - После удаления антивируса перезагрузите компьютер.

---

## 2. Работа с реестром Windows

### Предупреждение
Работа с реестром Windows может привести к нестабильной работе системы, если что-то будет сделано неправильно. Всегда делайте резервную копию реестра перед внесением изменений.

### Создание резервной копии реестра

1. **Откройте редактор реестра:**
   - Нажмите `Win + R`, введите `regedit` и нажмите `Enter`.

2. **Создайте резервную копию:**
   - В редакторе реестра выберите **"Файл"** > **"Экспортировать"**.
   - Укажите имя файла (например, `Backup.reg`) и сохраните его в безопасном месте.

---

### Удаление остатков антивируса из реестра

1. **Откройте редактор реестра:**
   - Нажмите `Win + R`, введите `regedit` и нажмите `Enter`.

2. **Перейдите к ключам реестра, связанным с антивирусом:**
   - Обычно антивирусы сохраняют свои настройки в следующих разделах:
     - `HKEY_LOCAL_MACHINE\SOFTWARE\<Название антивируса>`
     - `HKEY_CURRENT_USER\SOFTWARE\<Название антивируса>`
   - Например, для Avast это может быть:
     - `HKEY_LOCAL_MACHINE\SOFTWARE\Avast Software`

3. **Удалите папки, связанные с антивирусом:**
   - Щёлкните правой кнопкой мыши на папке антивируса и выберите **"Удалить"**.
   - Подтвердите удаление.

4. **Перезагрузите компьютер:**
   - После удаления остатков антивируса из реестра перезагрузите компьютер.

---

## 3. Проверка системы на наличие остатков антивируса

1. **Используйте встроенную утилиту "Проверка системных файлов":**
   - Откройте командную строку от имени администратора (нажмите `Win + X` и выберите **"Командная строка (администратор)"**).
   - Введите команду:
     ```
     sfc /scannow
     ```
   - Дождитесь завершения сканирования и следуйте инструкциям на экране.

2. **Используйте сторонние утилиты (опционально):**
   - Программы, такие как CCleaner, могут помочь удалить остатки антивируса из системы.

---

## 4. Заключение

В ходе выполнения этого задания я узнала, как правильно удалять антивирусное программное обеспечение и работать с реестром Windows. Удаление антивируса через "Панель управления" или "Параметры" оказалось довольно простым процессом, но работа с реестром потребовала большей осторожности. Я научилась создавать резервные копии реестра и удалять остатки антивируса, что является важным навыком для поддержания стабильной работы системы.

Также я поняла, насколько важно следовать инструкциям и быть внимательной при работе с системными настройками. Это поможет избежать ошибок и сохранить работоспособность компьютера. В целом, это задание было полезным и познавательным, и я смогу применить полученные знания в будущем.

