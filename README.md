# IELTS 03 — Gulora Muzaffarova

03 saytning binafsha rangli kodli nusxasi.

## Tayyor qismlar

- 347 px kenglikdagi dizayn telefon va kompyuterda markazda qoladi.
- Mahalliy PNG rasmlar, alohida tahrirlanadigan matn va tugmalar.
- Har ochilganda 50 soniyadan boshlanib, 00:00 da to‘xtaydigan taymer.
- Ikkala tugma ham ism va telefon formasini ochadi. Taymer tugmalarga ta’sir qilmaydi.
- Forma server tasdig‘idan keyingina thank-you.html sahifasiga o‘tadi.
- Thank you sahifasida Telegram tugmasi bor.

## Ulanish

1. Telegram tugmasiga `https://t.me/+pI8qgctAozFjZTIy` havolasi kiritilgan.
2. Forma `03` sayt raqamini yuboradi. Google Sheets manzili tanlangan va Apps Script `01`, `02`, `03` qiymatlarini qabul qiladi.
3. Vercel’da oldingi saytlardagi bir xil `LEAD_WEBHOOK_URL` hamda `LEAD_WEBHOOK_TOKEN` o‘zgaruvchilarini kiriting.
4. Server Apps Script javobida `ok: true` bo‘lsagina thank-you sahifasiga o‘tadi. Bir arizani takror yuborish bir xil Ariza ID bilan ikkinchi satr yaratmaydi.

## Ko‘rish

`dist/index.html` va `dist/thank-you.html` fayllarini brauzerda ochib dizaynni ko‘rish mumkin. API mahalliy HTML faylini ochish bilan ishlamaydi.

## Vercel

Arxivni oching. `vercel.json`, `package.json`, `api` va `dist` birgalikda GitHub reposining asosiy papkasida bo‘lsin. Vercel’da shu reponi import qiling. Framework: Other; Output Directory: dist; build buyrug‘i talab qilinmaydi. `vercel.json` chiqish papkasini belgilaydi.

Rasmiy hujjatlar: https://vercel.com/docs/project-configuration va https://vercel.com/docs/functions/runtimes/node-js

Ommaga tarqatishdan oldin sinov arizasi `Sayt = 03` bilan saqlangani va undan keyin Thank you sahifasi ochilganini tekshiring.

## Matn tahrirlari

“2000+ o‘quvchilar” → “2000+ o‘quvchi”; takrorlangan “uchun” olib tashlandi; Speaking bandining tugallanmagan “hamda” qismi to‘liq gapga almashtirildi.
