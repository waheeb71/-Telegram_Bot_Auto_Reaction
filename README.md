

# Telegram Bot - Auto Reaction

![Python](https://img.shields.io/badge/Python-3.7%2B-blue) ![Telegram](https://img.shields.io/badge/Telegram-API-green)

هذا البوت يقوم تلقائيًا بإضافة رد فعل (❤️) على أي رسالة يتم إرسالها في الدردشة. يمكن استخدامه في المجموعات والقنوات لتعزيز التفاعل مع الرسائل.

---

## 📋 المتطلبات

لتشغيل هذا البوت، تحتاج إلى:

1. **Python 3.7+**: تأكد من تثبيت Python على جهازك.
   - [رابط تحميل Python](https://www.python.org/downloads/)

2. **مكتبة Requests**:
   - قم بتثبيتها باستخدام الأمر التالي:
     ```bash
     pip install requests
     ```


---

## 🚀 كيفية الاستخدام

1. **تنزيل الكود:**
   - قم بتنزيل الكود من هذا المستودع أو استنساخه باستخدام Git:
     ```bash
     git clone https://github.com/your-repo/telegram-auto-reaction-bot.git
     ```

2. **إعداد التوكن:**
   - افتح الملف `bot_w.py` وضع توكن البوت الخاص بك في المتغير `TOKEN`:
     ```python
     TOKEN = "YOUR_BOT_TOKEN"
     ```

3. **تشغيل البوت:**
   - قم بتشغيل البوت باستخدام الأمر التالي:
     ```bash
     python bot_w.py
     ```

4. **إضافة البوت إلى مجموعة:**
   - أضف البوت إلى المجموعة التي تريد أن يعمل فيها.

---

### 1. تغيير رد الفعل:
يمكنك تغيير الرمز التفاعلي (Emoji) الذي يضيفه البوت عن طريق تعديل السطر التالي في الكود:
```python
send_reaction(chat_id, message_id, "❤️")  # يمكنك تغيير "❤️" إلى أي رمز آخر مثل "👍" أو "😂".
