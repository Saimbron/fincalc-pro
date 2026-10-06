# 💰 FinCalc Pro — Calculadora Financiera de Alto CPC para Google AdSense

**FinCalc Pro** es una suite completa de herramientas financieras interactivas desarrollada con diseño ultramoderno (Tailwind CSS, Chart.js, Lucide Icons) pensada para lograr:
1. **Alto tiempo de permanencia en página (Dwell Time)**: Los usuarios pasan entre 2 y 5 minutos ajustando cifras y consultando gráficos.
2. **Nicho de máximo CPC en Google Ads**: Las hipotecas, préstamos y finanzas personales tienen los costes por clic más altos del mercado publicitario (entre 2 € y más de 25 € por clic según el país).
3. **Aprobación fácil en Google AdSense**: Incluye página de Privacidad RGPD, Aviso Legal, banner de cookies, archivo `ads.txt` y contenido educativo exhaustivo para superar el filtro de "contenido de bajo valor".

---

## 🛠️ Herramientas incluidas:
1. **Simulador de Hipotecas Avanzado con Amortización Anticipada**:
   - Cálculo de cuota mensual, TIN, gastos anuales (IBI, seguros).
   - Soporte completo de amortización anticipada: aportaciones mensuales recurrentes, anuales y extraordinarias puntuales.
   - Estrategias de amortización: **Reducir Plazo** (máximo ahorro de intereses) o **Reducir Cuota**.
   - Panel dinámico de estadísticas de ahorro con comparativa de tiempo y dinero ganado.
   - Gráfico de líneas de evolución de saldo restante estándar vs. acelerado.
   - **Gráfico de barras comparativo de ahorro de intereses** (estilo Bankrate).
   - Tabla completa de amortización anual o mensual exportable a CSV con codificación UTF-8.
   - Soporte de impresión y exportación a PDF limpia y certificada (`@media print`).
2. **Calculadora de Interés Compuesto**: Estimador de patrimonio a largo plazo con aportaciones periódicas y gráfico dinámico de crecimiento exponencial.
3. **Comparador de 2 Préstamos**: Algoritmo de decisión directa para evaluar qué oferta bancaria ahorra más comisiones e intereses totales.
4. **Calculadora de Inflación**: Herramienta de impacto sobre el poder adquisitivo real de los ahorros.
5. **SEO & Structured Data Rich Snippets**: Schema.org JSON-LD completo (`WebApplication`, `FinancialProduct`, `FAQPage`) optimizado para posicionar en el puesto #1 de Google.

---

## 🚀 Cómo publicar la web gratis en Internet (en 2 minutos)

Para que Google AdSense pueda aprobar la web, esta debe estar alojada en Internet con un enlace público. Tienes estas opciones 100% gratuitas:

### Opción A: Vercel (Recomendada - La más rápida)
1. Ve a [vercel.com](https://vercel.com) y crea una cuenta gratuita (puedes iniciar sesión con tu cuenta de GitHub).
2. Haz clic en **Add New... > Project**.
3. Arrastra directamente esta carpeta `fincalc-pro` o selecciona el repositorio de GitHub.
4. Haz clic en **Deploy**. En 15 segundos tendrás una URL pública tipo `fincalc-pro.vercel.app`.

### Opción B: GitHub Pages
1. Sube esta carpeta a un nuevo repositorio de GitHub (ej: `fincalc-pro`).
2. Ve a **Settings > Pages**.
3. En la sección "Branch", selecciona `main` y la carpeta `/ (root)`. Haz clic en **Save**.
4. En 1 minuto tu web estará pública en `tu-usuario.github.io/fincalc-pro`.

---

## 💵 Cómo conectar tu cuenta de Google AdSense

Una vez que la web esté publicada en Internet:
1. Entra a tu panel de [Google AdSense](https://adsense.google.com).
2. Ve a **Sitios web (Sites)** > haz clic en **Añadir sitio web (Add Site)**.
3. Introduce tu URL (idealmente con dominio propio si compras uno económico, como `.com` o `.es`, o la URL pública).
4. Google te proporcionará tu código de cliente (ej: `ca-pub-1234567890123456`).
5. Abre el archivo [index.html](file:///C:/Users/Usuari/Documents/GitHub/fincalc-pro/index.html), busca `ca-pub-XXXXXXXXXXXXXXXX` y coloca tu número de AdSense.
6. Abre el archivo [ads.txt](file:///C:/Users/Usuari/Documents/GitHub/fincalc-pro/ads.txt) y sustituye también `pub-XXXXXXXXXXXXXXXX` por tu número.
7. En el panel de AdSense, haz clic en **Solicitar revisión**. Google verificará el sitio en 24h - 48h y comenzarán a mostrarse los anuncios reales generando ingresos automáticos por cada visita y clic.
