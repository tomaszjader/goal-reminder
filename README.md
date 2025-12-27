# n8n: Daily Goals Reminder

Workflow służący do codziennego przypominania o celach zapisanych w Google Docs.

### Działanie
* **Trigger**: Codzienne przypomnienie o godzinie **08:08**.
* **Źródło**: Pobiera listę celów z dokumentu **Google Docs**.
* **Odbiorcy**: Pobiera identyfikatory czatów (`id_chat`) z tabeli danych n8n.
* **Wysyłka**: Bot Telegram przesyła wiadomość z aktualnymi celami.

### Konfiguracja
* **Credentials**: Google Docs OAuth2 & Telegram API.
* **Doc ID**: Zawiera listę celów do przypomnienia.
* **Table ID**: `r5iHFZ9vD734mOPl`
