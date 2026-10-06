# 💰 FinCalc Pro — Calculadora Financera d'Alt CPC per a Google AdSense

**FinCalc Pro** és una suite completa d'eines financeres interactives desenvolupada amb disseny ultra-modern (Tailwind CSS, Chart.js, Lucide Icons) pensada per aconseguir:
1. **Alt temps de permanència a la pàgina (Dwell Time)**: Els usuaris passen entre 2 i 5 minuts ajustant xifres i consultant gràfics.
2. **Nínxol de màxim CPC a Google Ads**: Les hipoteques, préstecs i finances personals tenen els costos per clic més alts del mercat publicitària (entre 2€ i més de 25€ per clic depenent del país).
3. **Aprovació fàcil a Google AdSense**: Inclou pàgina de Privadesa RGPD, Avís Legal, banner de cookies, fitxer `ads.txt` i contingut educatiu exhaustiu per superar el filtre de "contingut de baix valor".

---

## 🛠️ Eines incloses:
1. **Simulador d'Hipoteques Avançat amb Amortització Anticipada**:
   - Càlcul de quota mensual, TIN, despeses anuals (IBI, assegurances).
   - Suport complet d'amortització anticipada: aportacions mensuals recurrents, anuals i extraordinàries puntuals.
   - Estratègies d'amortització: **Reduir Termini** (màxim estalvi d'interessos) o **Reduir Quota**.
   - Tauler dinàmic d'estadístiques d'estalvi amb comparativa de temps i diners guanyats.
   - Gràfica de línies d'evolució de saldo restant estàndard vs accelerat.
   - **Gràfica de barres comparativa d'estalvi d'interessos** (estil Bankrate).
   - Taula completa d'amortització anual o mensual exportable a CSV amb codificació UTF-8.
   - Suport d'impressió i exportació a PDF neta i certificada (`@media print`).
2. **Calculadora d'Interès Compost**: Estimador de riquesa a llarg termini amb aportacions periòdiques i gràfica dinàmica de creixement exponencial.
3. **Comparador de 2 Préstecs**: Algorisme de decisió directa per avaluar quina oferta bancària estalvia més comissions i interessos totals.
4. **Calculadora d'Inflació**: Eina d'impacte sobre el poder adquisitiu real dels estalvis.
5. **SEO & Structured Data Rich Snippets**: Schema.org JSON-LD complet (`WebApplication`, `FinancialProduct`, `FAQPage`) optimitzat per posicionar al rang #1 de Google.

---

## 🚀 Com publicar la web gratuïtament a Internet (en 2 minuts)

Perquè Google AdSense pugui aprovar la web, aquesta ha d'estar allotjada a Internet amb un enllaç públic. Tens aquestes opcions 100% gratuïtes:

### Opció A: Vercel (Recomanada - La més ràpida)
1. Ves a [vercel.com](https://vercel.com) i crea un compte gratuït (pots entrar amb el teu GitHub).
2. Fes clic a **Add New... > Project**.
3. Arrossega directament aquesta carpeta `fincalc-pro` o selecciona el repositori de GitHub.
4. Fes clic a **Deploy**. En 15 segons tindràs una URL pública tipus `fincalc-pro.vercel.app`.

### Opció B: GitHub Pages
1. Puja aquesta carpeta a un nou repositori de GitHub (ex: `fincalc-pro`).
2. Ves a **Settings > Pages**.
3. A la secció "Branch", selecciona `main` i la carpeta `/ (root)`. Fes clic a **Save**.
4. En 1 minut la teva web serà pública a `el-teu-usuari.github.io/fincalc-pro`.

---

## 💵 Com connectar el teu compte de Google AdSense

Un cop la web estigui penjada a Internet:
1. Entra al teu tauler de [Google AdSense](https://adsense.google.com).
2. Ves a **Llocs web (Sites)** > fes clic a **Afegeix un lloc web (Add Site)**.
3. Introdueix la teva URL (idealment amb domini propi si en compres un barat, com `.com` o `.es`, o la URL pública).
4. Google et donarà el teu codi de client (ex: `ca-pub-1234567890123456`).
5. Obre l'arxiu [index.html](file:///C:/Users/Usuari/Documents/GitHub/fincalc-pro/index.html), cerca `ca-pub-XXXXXXXXXXXXXXXX` i posa-hi el teu número d'AdSense.
6. Obre l'arxiu [ads.txt](file:///C:/Users/Usuari/Documents/GitHub/fincalc-pro/ads.txt) i substitueix també `pub-XXXXXXXXXXXXXXXX` pel teu número.
7. Al tauler d'AdSense, clica a **Demanar revisió**. Google verificarà el lloc en 24h - 48h i començaran a sortir els anuncis reals generant ingressos automàtics per cada visita i clic.
