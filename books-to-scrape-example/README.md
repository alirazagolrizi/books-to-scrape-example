# Books to Scrape: Simple Web Scraper | نمونهٔ خزش وب‌سایت Books to Scrape

**Proposed GitHub repository name:** `books-to-scrape-example`

## Purpose | هدف
Fetch and parse up to ten book titles and prices from the Books to Scrape demo site, saving CSV.

نمونهٔ خزش وب‌سایت Books to Scrape: این مخزن یک نمونهٔ مستقل مبتنی بر یک سلول کد استخراج‌شده است؛ برای شرح کوتاه فارسی، هدف پروژه را در عنوان بالا ببینید.

## Prerequisites | پیش‌نیازها
Python 3.9+; requests; beautifulsoup4; internet access.

## Install | نصب
Use Python 3 and Jupyter. Install the packages listed in `requirements.txt` with:

```bash
python -m pip install -r requirements.txt
```

پایتون و Jupyter را نصب کنید؛ سپس وابستگی‌های `requirements.txt` را با دستور بالا نصب کنید. برخی وابستگی‌ها اختیاری یا وابسته به سیستم‌عامل/سخت‌افزار هستند.

## Run | اجرا
Open notebook.ipynb in Jupyter and run its single code cell; it writes books_bs4.csv to the current directory.

فایل `notebook.ipynb` را در Jupyter باز کنید و یک سلول کد آن را اجرا کنید. ورودی‌ها و مسیرهای لازم در بخش محدودیت‌ها آمده‌اند.

## Limitations and input assets | محدودیت‌ها و ورودی‌ها
Requires network access and depends on the site remaining reachable and permitting requests. Not intended for scraping sites without permission.

این نمونه‌ها صرفاً آموزشی‌اند و اجرای انتها‌به‌انتها در این بسته تضمین یا تأیید نشده است. ورودی/دادهٔ تخصصی یا سخت‌افزار در صورت نیاز باید جداگانه فراهم شود.
