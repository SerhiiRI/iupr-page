---
title: "Контактна інформація"
date: ""
tags: []
build_from:
  - pro-nas/pro-instytut.md
  - kontakty/adresa-telefony-mapa.md
---

# Контактна інформація

[⬆ Карта сайту](../SITEMAP.md) · [Інститут](landing.md)

> TODO(контакти-на-кожній-сторінці): це тимчасове місце для контактів. Згодом блок
> «Контакти» розміщується на кожній сторінці сайту (рішення власника, 2026-09-29);
> тоді ця сторінка або лишається повним довідником, або зникає.

## Контакти

`ui-component: block-double`

`slot: left`

### Адреса та зв'язок

`ui-component: contact-block`

- **Адреса:** вул. Тютюнника, 11-А, м. Коломия, Івано-Франківська обл., 78200
- **Телефон:** +38 099 077-03-00, +38 067 324-58-52
- **Email:** [iupr@live.krok.edu.ua](mailto:iupr@live.krok.edu.ua)
- **Години:** Пн–Пт 9:00–18:00, без обідньої перерви; Сб, Нд — вихідні

`slot: right`

### Ми в соцмережах

`ui-component: list-links`

- [Facebook](https://www.facebook.com/iuprkrok) ↗
- [Instagram](https://www.instagram.com/iupr.klm/) ↗

> TODO(мапа): стара сторінка називалась «Адреса, телефони, мапа», але мапи в джерелі
> немає. Додати `map-embed` з посиланням на карту (потрібне рішення власника).

## Директор

`ui-component: block-double; tone=paper-2`

`slot: left`

`ui-component: image`

![Грицан Марія Миколаївна, директор Інституту](../assets/pro-nas/pro-instytut/zobrazhennya-5.jpg)

`slot: right`

### Грицан Марія Миколаївна

`ui-component: list-facts`

- **Посада:** директор Інституту
- **Відзнака:** Відмінник освіти України

## Кабінети

`ui-component: block-single`

`ui-component: list-links`

- [Кабінет студента](https://login.microsoftonline.com/cf94ad9d-2983-43f5-9909-722602ea2165/oauth2/authorize?client%5Fid=00000003%2D0000%2D0ff1%2Dce00%2D000000000000&response%5Fmode=form%5Fpost&response%5Ftype=code%20id%5Ftoken&resource=00000003%2D0000%2D0ff1%2Dce00%2D000000000000&scope=openid&nonce=76E497A05F8F1C69F5086F4896A69C466B3FF9DDE62F351F%2DE2174B82A8A09F8E2ADD9FB2AEFB5CDCC61278D68FC879EF4CB8CF4DA1C81519&redirect%5Furi=https%3A%2F%2Flivekrokedu%2Esharepoint%2Ecom%2F%5Fforms%2Fdefault%2Easpx&state=OD0w&claims=%7B%22id%5Ftoken%22%3A%7B%22xms%5Fcc%22%3A%7B%22values%22%3A%5B%22CP1%22%5D%7D%7D%7D&wsucxt=1&cobrandid=11bd8083%2D87e0%2D41b5%2Dbb78%2D0bc43c8a8e8a&client%2Dreques) ↗
- [Кабінет викладача](https://login.microsoftonline.com/cf94ad9d-2983-43f5-9909-722602ea2165/oauth2/authorize?client%5Fid=00000003%2D0000%2D0ff1%2Dce00%2D000000000000&response%5Fmode=form%5Fpost&response%5Ftype=code%20id%5Ftoken&resource=00000003%2D0000%2D0ff1%2Dce00%2D000000000000&scope=openid&nonce=3B38F40AE134DC973A4454DDE1693A47D94F0937DB3A106A%2DDFBCA5442611ADC452102B3FB8BFB573B2EC85D8A4F8B73EB82572BA1424DDE5&redirect%5Furi=https%3A%2F%2Flivekrokedu%2Esharepoint%2Ecom%2F%5Fforms%2Fdefault%2Easpx&state=OD0w&claims=%7B%22id%5Ftoken%22%3A%7B%22xms%5Fcc%22%3A%7B%22values%22%3A%5B%22CP1%22%5D%7D%7D%7D&wsucxt=1&cobrandid=11bd8083%2D87e0%2D41b5%2Dbb78%2D0bc43c8a8e8a&client%2Dreques) ↗

> TODO(кабінети): посилання перенесено дослівно зі старої головної, вони не мають
> стабільної цілі: це авторизаційні посилання Microsoft із разовим `nonce`, обрізані
> в джерелі («…client%2Dreques»). Замінити на постійну адресу входу (SharePoint
> `livekrokedu.sharepoint.com`) і згодом перенести на сторінки `studentam/` і
> `vykladacham/`.

## Скринька довіри

`ui-component: block-single; tone=paper-2`

`ui-component: text`

Напишіть анонімне повідомлення для адміністрації.

> TODO(скринька довіри): на старому сайті це форма з кнопкою «Надіслати» (у статичній
> копії немає ні адреси, куди вона надсилає, ні механізму). Потрібне рішення власника:
> зовнішня форма (Google Forms), поштова адреса чи прибрати.
