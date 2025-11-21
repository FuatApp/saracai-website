# 🚀 Deployment-Anleitung für Vercel

## Schnell-Anleitung

### Methode 1: Vercel CLI (Empfohlen)

1. **Öffne dein Terminal/PowerShell**

2. **Navigiere zum Projektordner:**
```bash
cd pfad/zu/deinem/projekt
```

3. **Installiere Vercel CLI (einmalig):**
```bash
npm install -g vercel
```

4. **Login bei Vercel:**
```bash
vercel login
```

5. **Deploye deine Website:**
```bash
vercel
```

6. **Für Produktions-Deployment:**
```bash
vercel --prod
```

Das war's! Deine Website ist jetzt live! 🎉

---

### Methode 2: GitHub + Vercel (Automatisch)

1. **Erstelle ein neues GitHub Repository:**
   - Gehe zu github.com
   - Klicke auf "New Repository"
   - Benenne es z.B. "saracai-website"

2. **Pushe deinen Code zu GitHub:**
```bash
cd pfad/zu/deinem/projekt
git init
git add .
git commit -m "Initial commit - Responsive SaracAI Website"
git branch -M main
git remote add origin https://github.com/DEIN-USERNAME/saracai-website.git
git push -u origin main
```

3. **Verbinde mit Vercel:**
   - Gehe zu vercel.com
   - Klicke "New Project"
   - Wähle dein GitHub Repository
   - Klicke "Deploy"

4. **Fertig!** Jedes Mal wenn du zu GitHub pushst, deployt Vercel automatisch! 🚀

---

### Methode 3: Vercel Dashboard (Einfachste Methode)

1. **Gehe zu vercel.com**
2. **Klicke auf "Add New..." → "Project"**
3. **Wähle "Upload" und lade alle HTML-Dateien hoch**
4. **Klicke auf "Deploy"**
5. **Fertig! Deine Website ist live!** ✨

---

## ✅ Checkliste vor dem Deployment

- [ ] Alle HTML-Dateien sind im gleichen Ordner
- [ ] Links funktionieren lokal (teste mit Live Server oder ähnlichem)
- [ ] Telefonnummer und E-Mail sind korrekt
- [ ] Impressum, Datenschutz und AGB sind ausgefüllt

---

## 🔧 Problemlösung

### "Vercel CLI nicht gefunden"
```bash
# Installiere Node.js von nodejs.org
# Dann erneut versuchen:
npm install -g vercel
```

### "Permission denied" bei npm install
```bash
# Für Mac/Linux:
sudo npm install -g vercel

# Für Windows: 
# Führe PowerShell als Administrator aus
```

### Website wird nicht korrekt angezeigt
- Überprüfe, dass die index.html im Root-Verzeichnis ist
- Stelle sicher, dass alle Dateinamen kleingeschrieben sind
- Cache leeren (Strg+F5 oder Cmd+Shift+R)

---

## 📞 Support

Bei Problemen:
- Vercel Dokumentation: vercel.com/docs
- Oder kontaktiere mich: info@saracai.de
