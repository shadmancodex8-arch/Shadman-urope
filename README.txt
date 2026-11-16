SHADMAN LIKE API - Simple Key+Limit Version

keys.json e 5ta slot ache:
  PUT_KEY_1_HERE ... PUT_KEY_5_HERE
Nijer pochonder key diye bodle felo, jemon:
  "afnaan": {"limit": 120, "used": 0}

Rule:
- Protteke key er limit 120 (chaile bodlaite paro)
- Daily reset nai, used joto hobe thakbe
- LikesGivenByAPI >= 100 hole-i 1 count hobe, 100er niche hole count hobe na
- Reset/renew korte:
/reset?owner=YOUR_OWNER_KEY&key=YOURKEY&limit=120
(OWNER_KEY app.py file e PUT_OWNER_KEY_HERE er jaygay nijer gopon password bosao)

limit shesh hole: "API limit ended. Contact owner for renew."

Use:
/like?key=YOURKEY&uid=UID&region=BD
/remain?key=YOURKEY

Deploy: sob file Vercel root e upload kore deploy koro.
