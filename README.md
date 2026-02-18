# Trainify Pro 💪
## Netlify Deployment Version

En professionell träningslogg med multi-user support, statistik och kalender.

## 🚀 Deploy till Netlify (Super Enkelt!)

### Metod 1: Netlify Drop (30 sekunder!)

1. **Zippa mappen** (om du laddat ner filerna separat)
2. **Gå till** [app.netlify.com/drop](https://app.netlify.com/drop)
3. **Dra och släpp** zip-filen ELLER hela mappen direkt på sidan
4. **KLART!** ✨ Du får en live URL typ: `random-name-123.netlify.app`

### Metod 2: Netlify CLI

```bash
# Installera Netlify CLI
npm install -g netlify-cli

# Logga in
netlify login

# Deploya från denna mapp
netlify deploy

# För production
netlify deploy --prod
```

### Metod 3: Via GitHub (Automatisk deploy vid varje commit)

1. Pusha filerna till ett GitHub repo
2. Gå till [app.netlify.com](https://app.netlify.com)
3. Klicka "Add new site" → "Import an existing project"
4. Välj GitHub → Välj ditt repo
5. Klicka "Deploy site"

**Varje gång du pushar kod till GitHub deployas sidan automatiskt!** 🎉

## 📁 Filer i detta paket

- `index.html` - Din kompletta Trainify Pro app
- `netlify.toml` - Netlify-konfiguration (redirects, headers, caching)
- `README.md` - Denna fil

## ✨ Funktioner

✅ **Multi-user system** - Flera användare med egna konton  
✅ **Träningsbibliotek** - Spara färdiga träningspass  
✅ **Smart kalender** - Planera och genomför pass  
✅ **Statistik & Grafer** - Följ din progress  
✅ **Styrketräning** - Logga övningar, vikt, reps  
✅ **Löpning** - Distans, tid, puls, tempo  
✅ **Mörkt tema** - Professionell design  

## 🎨 Anpassa din URL

Efter deployment kan du:
1. Gå till Site settings i Netlify
2. Klicka "Change site name"
3. Välj ett eget namn: `mitt-gym.netlify.app`

**ELLER** koppla din egen domän:
1. Gå till "Domain settings"
2. Klicka "Add custom domain"
3. Följ instruktionerna

## 🔒 Säkerhet

All data sparas **lokalt** i användarens webbläsare (localStorage).
- Ingen data skickas till servrar
- Ingen databas behövs
- Helt säkert och privat

## 💡 Tips

**Första användaren:**
1. Öppna din deployade sida
2. Klicka "Registrera"
3. Skapa konto
4. Börja logga träning!

**Bjud in kompisar:**
- Dela din Netlify-URL
- De kan skapa egna konton
- All data är separerad per användare

## 🛠️ Teknisk info

- **Framework:** Vanilla JavaScript (inga dependencies)
- **Grafik:** Chart.js (CDN)
- **Data:** localStorage
- **Hosting:** Netlify (gratis plan räcker!)

## 📞 Support

Funkar inte? Kolla:
1. Att du öppnar `index.html` (inte någon annan fil)
2. Att localStorage är aktiverat i webbläsaren
3. Konsollen i Developer Tools (F12) för felmeddelanden

---

**Lycka till med träningen!** 💪🔥
