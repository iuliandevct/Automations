# Automations

# 🏨 HELP.md  
## Automatizări WiFi Matter cu Shelby pentru Economia Energiei în Pensiuni

---

## 📌 Scop

Acest document descrie implementarea și utilizarea sistemului de automatizări **WiFi Matter** bazat pe Shelby pentru reducerea consumului energetic în pensiuni, hoteluri mici și unități turistice.

Obiective:
- Reducerea costurilor la energie electrică
- Automatizarea iluminatului și climatizării
- Control inteligent pe bază de prezență
- Monitorizare consum în timp real
- Integrare cu aplicații mobile și dashboard-uri

---

# 🧠 1. Ce este Matter?

**Matter** este un standard universal pentru dispozitive smart home, dezvoltat de:
- Apple
- Google
- Amazon
- Samsung

Avantaje:
- Funcționează local (nu depinde de cloud)
- Comunicare sigură
- Compatibilitate între ecosisteme
- Stabilitate mai mare față de soluții vechi WiFi-only

---

# 🏗 2. Arhitectura Sistemului

### Componente:

1. Dispozitive Matter WiFi:
   - Prize inteligente
   - Întrerupătoare
   - Termostate
   - Senzori mișcare
   - Senzori ușă/fereastră

2. Controller Shelby:
   - Hub central
   - Rulează automatizările
   - Conectat la rețeaua WiFi a pensiunii

3. Dashboard administrativ:
   - Monitorizare camere
   - Consum energie
   - Status echipamente

---

# ⚡ 3. Automatizări pentru Economie de Energie

## 🛏 3.1 Cameră Neocupată

**Trigger:**
- Senzor ușă închis
- Fără mișcare 15 minute

**Acțiuni:**
- Oprire lumină
- Oprire priză boiler / TV
- Setare AC pe 22°C sau OFF
- Dezactivare încălzire suplimentară

---

## ❄ 3.2 Control Climatizare Inteligentă

Reguli recomandate:

| Situație | Setare |
|----------|--------|
| Cameră ocupată | 21-23°C |
| Cameră neocupată | 18°C |
| Geam deschis | Oprire AC |
| Check-out efectuat | OFF total |

---

## 💡 3.3 Iluminat Automat

- Lumina hol activată doar la detecție mișcare
- Oprire automată după 2 minute
- Program nocturn (luminozitate 30%)

---

## 🔌 3.4 Control Prize Inteligente

Prizele pot fi dezactivate:
- După checkout
- Noaptea în zone comune
- În perioade de neocupare sezonieră

---

# 📊 4. Monitorizare Consum

Shelby permite:
- Măsurare consum per cameră
- Alertă consum anormal
- Raport lunar automat
- Identificare echipamente ineficiente

Recomandare:
- Prag alertă la +20% peste media camerei

---

# 🔐 5. Securitate

- Toate dispozitivele trebuie să fie în rețea separată VLAN
- Acces dashboard doar prin autentificare
- Backup automat al configurației
- Firmware actualizat periodic

---

# 🏢 6. Scenarii Practice pentru Pensiuni

## 🧾 Check-in automat:
- Activare lumină
- Setare temperatură confort
- Activare priză frigider

## 🚪 Check-out:
- Oprire totală echipamente
- Reset temperatură economic
- Notificare personal curățenie

## 🌙 Mod Noapte:
- Iluminat exterior redus
- Dezactivare prize inutile
- Monitorizare activitate

---

# 📈 7. Economii Estimate

Pentru o pensiune de 10 camere:

| Componentă | Economie estimată |
|------------|-------------------|
| Climatizare | 20-35% |
| Iluminat | 30-50% |
| Standby echipamente | 10-20% |

Economia anuală poate ajunge la:
> 15-30% din factura totală de energie

---

# 🔧 8. Implementare Recomandată

1. Audit energetic inițial
2. Instalare senzori și prize
3. Configurare Shelby
4. Testare scenarii
5. Training personal
6. Monitorizare 30 zile
7. Optimizare reguli

---

# 🚀 9. Extensii Avansate

- Integrare cu sistem PMS (Property Management System)
- Control prin aplicație mobilă
- Integrare panouri fotovoltaice
- Optimizare consum în funcție de tarif orar energie
- Automatizare boiler în funcție de ocupare

---

# 📞 10. Suport

Pentru suport tehnic:
- Verificare conexiune WiFi
- Restart controller Shelby
- Verificare firmware dispozitive
- Reset automatizări

---

# 🏁 Concluzie

Automatizările WiFi Matter cu Shelby oferă:

- Reducere costuri
- Control inteligent
- Monitorizare în timp real
- Scalabilitate
- Independență față de cloud

Soluția este ideală pentru pensiuni care doresc:
- Eficiență energetică
- Control centralizat
- Modernizare infrastructură

---

**Document versiunea 1.0**