# CV — Andrii Deleniv

Static CV site (Vercel).

- Site: `/`
- PDF download: `/cv.pdf` (also `/Andrii-Deleniv-CV.pdf`)

## Deploy na lh.pl (cv.deweb.studio)

Пуш у `main` → GitHub Actions заливає сайт по FTP (як deweb.studio).
Секрети (Settings → Secrets and variables → Actions):

| Назва | Що це |
|---|---|
| `FTP_SERVER` | FTP-сервер lh.pl (той самий, що для deweb.studio) |
| `FTP_USERNAME` | логін FTP |
| `FTP_PASSWORD` | пароль FTP |

Папка на сервері: `/cv.deweb.studio/` (у панелі LH: `/public_html/cv.deweb.studio`). Заливка — `lftp mirror`.
