# 🔐 My Last Key

En avanceret client-side applikation til at generere sikre, fysiske nøgledokumenter med kryptering og QR-koder.

## 🎯 Formål

My Last Key hjælper dig med at oprette et sikkert, fysisk dokument med alle dine vigtige koder og passwords. Dokumentet kan printes og gemmes sikkert, mens sensitive oplysninger kan krypteres med en master nøgle.

## ✨ Features

- **🔒 AES Kryptering**: Krypter sensitive oplysninger med en master nøgle
- **📱 QR-koder**: Generer QR-koder for nem scanning
- **🎨 Farvekodning**: Visuel formatering af passwords (tal=blå, små bogstaver=sort, store bogstaver=grøn, specialtegn=rød)
- **📦 Sekvens-bokse**: Tydelig visning af pinkoder i separate bokse
- **📄 Print-optimeret**: Perfekt formatering til print
- **📱 Responsivt design**: Fungerer på alle enheder
- **🔓 Dekrypteringsværktøj**: Separat værktøj til at dekryptere krypterede oplysninger

## 🚀 Brug

### Hovedapplikation (`index.html`)
1. Åbn `index.html` i din browser
2. Indtast en stærk master krypteringsnøgle
3. Tilføj dine oplysninger i formularen:
   - Vælg kategori (Bruger/Password, Pinkode, etc.)
   - Indtast titel og værdi
   - Marker "Krypter" for sensitive oplysninger
   - Marker "QR" for at generere QR-kode
4. Se live preview til højre
5. Print dokumentet når du er tilfreds

### Dekrypteringsværktøj (`dekrypter.html`)
1. Åbn `dekrypter.html` i din browser
2. Indsæt den krypterede tekst fra dit dokument
3. Indtast din master krypteringsnøgle
4. Klik "Dekrypter" for at se den originale tekst

## 🛠️ Teknologi

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Kryptering**: CryptoJS (AES)
- **QR-koder**: qrcode.js
- **Hosting**: Statisk hosting (Vercel, GitHub Pages, etc.)

## 📁 Filstruktur

```
MyLastKey/
├── index.html          # Hovedapplikation
├── dekrypter.html      # Dekrypteringsværktøj
└── README.md          # Denne fil
```

## 🔐 Sikkerhed

- **Client-side only**: Alle operationer sker lokalt i din browser
- **Ingen data sendes**: Intet uploades til servere
- **AES kryptering**: Industristandard kryptering
- **Master nøgle**: Kun du kender din krypteringsnøgle

## 📋 Kategorier

- **Bruger/Password**: Farvekodede passwords
- **Pinkode**: Sekvens-bokse for hver cifre
- **Sikkerhedsspørgsmål**: Spørgsmål og svar
- **Wi-Fi Kode**: Netværkskoder
- **Note/Tekst**: Generelle noter
- **Licensnøgle**: Software licenser

## 🖨️ Print Tips

- Brug "Print" funktionen i din browser
- Kun preview-området printes (formular skjules automatisk)
- Farver bevares for bedre læsbarhed
- QR-koder printes i høj kvalitet

## 🔗 Links

- **GitHub Repository**: [https://github.com/rasmusnielsen-eu/MyLastKey](https://github.com/rasmusnielsen-eu/MyLastKey)
- **Live Demo**: [Kommer snart]

## 📄 Licens

© 2025 Rasmus Nielsen. Alle rettigheder forbeholdt.

---

**⚠️ Vigtigt**: Husk din master krypteringsnøgle! Uden den kan krypterede oplysninger ikke dekrypteres. 