# روش اعمال بسته در ریپو

محتویات این پوشه را در ریشهٔ ریپوی زیر کپی کن:

```text
C:\Users\shagh\Documents\GitHub\thesis-sources
```

ساختار `archive/` موجود را حذف یا جایگزین نکن. این بسته فقط به آن ارجاع می‌دهد.

## بررسی قبل از commit

```powershell
cd C:\Users\shagh\Documents\GitHub\thesis-sources
git status -sb
git diff -- README.md AGENTS.md docs/ai-context
```

## commit پیشنهادی

```powershell
git add README.md AGENTS.md docs/ai-context
git commit -m "docs: add thesis project instructions and research protocols"
git push
```

فایل `CHATGPT_PROJECT_INSTRUCTIONS.md` برای کپی در کادر Project Instructions است و لازم نیست حتماً داخل ریپو commit شود؛ نگه‌داشتنش در ریپو برای نسخه‌بندی مفید است.
