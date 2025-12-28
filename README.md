# Balex v1.3

**Python library for Bale Messenger bots** 🚀 
.

---

## نصب

```bash
pip install balex==1.3.0
```

# مثال استفاده 
```bash
from balex.client import  BotClient
app = BotClient("Bot_token")
app.send_message(chat_id, "hello")
```

# متد های موجود

| متد | پارامتر | توضیح |
|--------|--------|-------|
|send_message | chat_id , text | ارسال پیام کاربر |
|set_webhook | url | ثبت کردن وب هوک |
