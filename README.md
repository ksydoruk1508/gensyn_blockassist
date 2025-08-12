# BlockAssist Installation & Usage Guide

## English Version

## 📋 Requirements

**EN:**  
- **Ubuntu 22.04** (tested on `CPU 16 / RAM 32` at [Hetzner](https://hetzner.cloud/?ref=NfF1b8e27Djj)) You can rent it by the hour.
- VNC client (e.g. **MobaXterm**, RealVNC, TigerVNC, etc.)  
- Stable internet connection  
- Hugging Face account with **Write-enabled access token**  
- Java 8 (installed automatically by script)  
- Google Chrome (installed automatically by script, set as default browser)  

---

### 1. Rent a Server
To use this script, you will need to rent a server.  
I tested it on **Ubuntu 22.04, CPU 16 cores, RAM 32 GB** at [Hetzner Cloud](https://hetzner.cloud/?ref=NfF1b8e27Djj).

---

### 2. Download and Run the Script
```bash
wget -q -O blockassist.sh https://raw.githubusercontent.com/ksydoruk1508/gensyn_blockassist/main/blockassist.sh && sudo chmod +x blockassist.sh && ./blockassist.sh
```
<img width="431" height="470" alt="Снимок экрана 2025-08-12 032341" src="https://github.com/user-attachments/assets/f3e94b24-885a-4ee6-9790-a0a44060760c" />

---

### 3. Install VNC Server
Choose **Function 1**: `Update repositories and install VNC (server)` and wait until installation completes.  
At the end, you will see the **login details** for VNC.
<img width="707" height="644" alt="Снимок экрана 2025-08-12 040042" src="https://github.com/user-attachments/assets/ac500bec-9d9e-4b57-b903-d84ab5114459" />

---

### 4. Connect to the Server via VNC
Use the provided VNC login details.  
Example using **MobaXterm**:  
1. Click **Session** (top left).  
2. Select **VNC**.  
3. Enter your server IP and change the port.  
4. Click **OK**, enter your password.
<img width="954" height="598" alt="image" src="https://github.com/user-attachments/assets/2bd456d3-2943-48a5-b153-45e9d5fc70c2" />

---

### 5. Run the Script Inside VNC
```bash
wget -q -O blockassist.sh https://raw.githubusercontent.com/ksydoruk1508/gensyn_blockassist/main/blockassist.sh && sudo chmod +x blockassist.sh && ./blockassist.sh
```
<img width="1474" height="826" alt="image" src="https://github.com/user-attachments/assets/40d32849-cd13-4a33-bee8-6c1419a3ee99" />
<img width="611" height="418" alt="Снимок экрана 2025-08-12 040459" src="https://github.com/user-attachments/assets/b12f9b45-69d5-4008-8004-2a877b49483e" />

---

### 6. Install BlockAssist
Choose **Function 2**: `Install Block Assist (inside VNC)`.
<img width="859" height="567" alt="Снимок экрана 2025-08-12 040520" src="https://github.com/user-attachments/assets/b4b497e6-9855-468f-a7ff-b00787a234cb" />

---

### 7. Launch BlockAssist
Choose **Function 3**: `Run Block Assist (inside VNC)`.

---

### 8. Get Hugging Face Write Token
Register at [Hugging Face](https://huggingface.co/) → confirm email → [Create Token](https://huggingface.co/settings/tokens) → **Write** type.

---

### 9. Enter the Token
Paste token into terminal.
<img width="840" height="547" alt="Снимок экрана 2025-08-12 040838" src="https://github.com/user-attachments/assets/b6476755-0645-41d7-8648-754a89dc8678" />

---

### 10. Login in Browser
When prompted, login in VNC browser.
<img width="699" height="740" alt="image" src="https://github.com/user-attachments/assets/046cae4e-9f95-40a4-830e-599bb10c0ca0" />

---

### 11. Wait for Minecraft 2 Windows
Press **Enter** in terminal when ready.
<img width="1473" height="843" alt="Снимок экрана 2025-08-12 142749" src="https://github.com/user-attachments/assets/3fde5967-71f2-49b1-8abc-61e8f8f18f08" />

---

### 12. Play
No need for 100% completion.

---

### 13. Stop Recording
Press **Esc** in Minecraft → **Enter** in terminal.
<img width="1478" height="832" alt="Снимок экрана 2025-08-12 142944" src="https://github.com/user-attachments/assets/24e7f3c0-e4cc-4553-9c77-34b0f61d2b1b" />

---

### 14. Model Training
Takes about **1 hour**.
<img width="1470" height="803" alt="image" src="https://github.com/user-attachments/assets/1c4d13b5-dd7c-49ff-8c38-00da8bfab491" />
---

### 15. Upload Complete
Check Hugging Face model URL.

---

### 16. Check Your Model
Go to [Hugging Face](https://huggingface.co/).

---

### 17. Get Role in Discord
Open `gensyn.json` for `eoa`, `trainingId`, and `heid`.

---

## 📬 Support & Contacts

💬 Telegram Chat: [@nod3r\_team](https://t.me/nod3r_team)
📢 Telegram Channel: [@nod3r](https://t.me/nod3r)
🤖 Bot: [@wiki\_nod3r\_bot](https://t.me/wiki_nod3r_bot)
💻 GitHub: [ksydoruk1508/gensyn_blockassist](https://github.com/ksydoruk1508/gensyn_blockassist)

---

**If you have questions or issues — join our Telegram chat or open a GitHub Issue!**

---

## Русская версия

## 📋 Требования

**RU:**  
- **Ubuntu 22.04** (тестировалось на `CPU 16 / RAM 32` в [Hetzner](https://hetzner.cloud/?ref=NfF1b8e27Djj)) Есть возможность арендовать почасово 
- VNC-клиент (например, **MobaXterm**, RealVNC, TigerVNC и др.)  
- Стабильное интернет-соединение  
- Аккаунт Hugging Face с **токеном доступа типа Write**  
- Java 8 (устанавливается автоматически скриптом)  
- Google Chrome (устанавливается автоматически скриптом и назначается браузером по умолчанию) 

### 1. Арендуйте сервер
Тестировано на **Ubuntu 22.04, CPU 16 ядер, RAM 32 ГБ** — [Hetzner Cloud](https://hetzner.cloud/?ref=NfF1b8e27Djj).

---

### 2. Скачайте и запустите скрипт
```bash
wget -q -O blockassist.sh https://raw.githubusercontent.com/ksydoruk1508/gensyn_blockassist/main/blockassist.sh && sudo chmod +x blockassist.sh && ./blockassist.sh
```
<img width="431" height="470" alt="Снимок экрана 2025-08-12 032341" src="https://github.com/user-attachments/assets/853e8f94-81ff-4c7e-8d4e-d71a2ef51b95" />

---

### 3. Установите VNC Server
**Функция 1**: `Обновить репозитории и установить VNC (сервер)`.
<img width="707" height="644" alt="Снимок экрана 2025-08-12 040042" src="https://github.com/user-attachments/assets/36f23db8-a000-4db3-a510-f2a28c8b2dad" />

---

### 4. Подключитесь через VNC
Пример через **MobaXterm**:  
1. **Session**.  
2. **VNC**.  
3. IP и порт.  
4. Пароль.
<img width="954" height="598" alt="image" src="https://github.com/user-attachments/assets/0e7b4bb8-1f5e-43d7-b43b-4152f0cea764" />

---

### 5. Запустите скрипт в VNC
```bash
wget -q -O blockassist.sh https://raw.githubusercontent.com/ksydoruk1508/gensyn_blockassist/main/blockassist.sh && sudo chmod +x blockassist.sh && ./blockassist.sh
```
<img width="1474" height="826" alt="image" src="https://github.com/user-attachments/assets/dd2cb10f-f3bc-4e75-a862-fe80ffbe599b" />
<img width="611" height="418" alt="Снимок экрана 2025-08-12 040459" src="https://github.com/user-attachments/assets/42a27355-0530-4498-b9a4-1592c8712d24" />

---

### 6. Установите BlockAssist
**Функция 2**.
<img width="859" height="567" alt="Снимок экрана 2025-08-12 040520" src="https://github.com/user-attachments/assets/bf0af36b-a311-46f6-b9f1-13c917d24b3e" />

---

### 7. Запустите BlockAssist
**Функция 3**.

---

### 8. Получите токен Hugging Face
[Hugging Face](https://huggingface.co/) → Подтвердите почту → [Создать токен](https://huggingface.co/settings/tokens) → тип **Write**.

---

### 9. Введите токен
Вставьте в терминал.
<img width="840" height="547" alt="Снимок экрана 2025-08-12 040838" src="https://github.com/user-attachments/assets/0d18a69b-faa3-4d66-835e-1c3b34e4ef50" />

---

### 10. Вход через браузер
Войдите в браузере внутри VNC.
<img width="699" height="740" alt="image" src="https://github.com/user-attachments/assets/7b579e3b-beab-4a9e-996f-e2fea96d9d9e" />

---

### 11. Дождитесь 2 окон Minecraft
Нажмите **Enter** в терминале.
<img width="1473" height="843" alt="Снимок экрана 2025-08-12 142749" src="https://github.com/user-attachments/assets/4be97959-dc0a-4641-b36d-397eb2dbdfb3" />

---

### 12. Играйте
Не обязательно 100%.

---

### 13. Остановите запись
**Esc** в Minecraft → **Enter** в терминале.
<img width="1478" height="832" alt="Снимок экрана 2025-08-12 142944" src="https://github.com/user-attachments/assets/5eef28a0-7c29-470b-b686-2fb15dbeb64e" />

---

### 14. Обучение модели
~1 час.
<img width="1470" height="803" alt="image" src="https://github.com/user-attachments/assets/1c4d13b5-dd7c-49ff-8c38-00da8bfab491" />

---

### 15. Завершение загрузки
Проверьте ссылку модели.

---

### 16. Проверьте модель
[Hugging Face](https://huggingface.co/).

---

### 17. Получите роль в Discord
Откройте `gensyn.json` → `eoa`, `trainingId`, `heid`.

---

## Поддержка и контакты

* Telegram-чат: [@nod3r\_team](https://t.me/nod3r_team)
* Telegram-канал: [@nod3r](https://t.me/nod3r)
* Бот: [@wiki\_nod3r\_bot](https://t.me/wiki_nod3r_bot)
* GitHub: [ksydoruk1508/gensyn_blockassist](https://github.com/ksydoruk1508/gensyn_blockassist)

---

**Если возникли вопросы или проблемы — пишите в чат или Issues на GitHub!**
