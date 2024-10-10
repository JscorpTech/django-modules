# Authbot module



> ## Modulni o'rnatish

```bash
jst install
```

> [!NOTE]
>
> Authbotni tanlang



> ## Sozlamalar

> .env fayliga bot token o'zgaruvchisini qo'shing

```
BOT_TOKEN=you bot token
```

> routes/common.py fayliga yangi url qo'shing



```python
url_patterns = [path("authbot/", include("core.apps.authbot.urls"))]
```



> ## Ishga tushurish

> [!NOTE]
>
> Ishga tushurishdan avval docker web container shell ga kirganingizga ishonch hosil qiling



```bash
python3 manage.py authbot
```