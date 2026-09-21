# 🏅 Medaglie 3D Interattive NFC

Progetto per la creazione e visualizzazione di medaglie e trofei stampati in 3D con tag NFC integrato.

## ✨ Funzionalità
- 📱 **Mobile-First & PWA Feel**: Ottimizzato per la visualizzazione immediata su qualsiasi smartphone (iOS e Android) quando si tocca il tag NFC.
- 🔄 **Effetto 3D Tilt**: Reagisce al giroscopio del telefono o al movimento del mouse con rendering tridimensionale e riflessi metallici.
- 🎉 **Animazione Coriandoli**: Esplosione di festa all'apertura del trofeo.
- 🏹 **Multi-Sport**: Supporto per Tiro con l'Arco, Corsa, Nuoto, Ciclismo, Calcio, Padel, Arti Marziali, Hackathon, Laurea e molto altro.
- 🛡️ **Zero-Database**: I dati viaggiano in modo sicuro nei parametri URL, senza necessità di configurare database.
- 🪄 **Generatore Integrato**: Tool interattivo (`generator.html`) per creare link e generare QR Code in tempo reale.

## 🚀 Come testare in locale
Apri un server locale:
```bash
python -m http.server 3000
```
- **Generatore**: `http://localhost:3000/generator.html`
- **Visualizzatore Medaglia**: `http://localhost:3000/index.html`
