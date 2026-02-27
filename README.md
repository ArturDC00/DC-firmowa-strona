# DC House — Landing Pages

Projekt zawiera standalone landing pages hostowane na Vercel.

## Strony
- `/checklista-software-house` — lead magnet z checklistą PDF
- `/kalkulatory` — hub kalkulatorów IT

## Deployment
1. `vercel --prod` lub push do GitHub → auto-deploy

## Konfiguracja
Przed deployem zmień w `checklista-software-house.html`:
```
const BITRIX_WEBHOOK_URL = 'WSTAW_SWOJ_WEBHOOK_URL_TUTAJ';
```
