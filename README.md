# LeonardoTrader 📈

Visor gratuito de charts de acciones con análisis IA (Claude).  
Powered by **Yahoo Finance** (data pública) + **Claude AI** via claude.ai.

## 🚀 Deploy en Vercel (5 minutos)

### Paso 1 — Sube a GitHub
1. Ve a https://github.com/new
2. Crea un repositorio llamado `leonardo-trader` (público o privado)
3. Sube todos estos archivos

### Paso 2 — Conecta Vercel
1. Ve a https://vercel.com/new
2. Importa tu repositorio de GitHub
3. **Framework Preset:** Other  
4. **Root Directory:** `.` (dejar por defecto)  
5. Haz clic en **Deploy**

### Paso 3 — Cambia el nombre del proyecto
En el dashboard de Vercel:
1. Ve a **Settings → General**
2. Cambia el **Project Name** a `leonardo-trader` (o el nombre que quieras)
3. Tu URL será: `https://leonardo-trader.vercel.app`

> ⚠️ El nombre exacto depende de disponibilidad en Vercel.  
> Puedes probar: `leonardotrader`, `leonardo-trader-cl`, etc.

## ✨ Funciones

- **Charts de velas** (OHLC) en tiempo real
- **Watchlist** con tus acciones favoritas  
- **EMA 20 y EMA 50** activables/desactivables  
- **Volumen** en la parte inferior  
- **Tooltips** con datos exactos  
- **Añadir tickers** con el botón `+` (se guardan en el navegador)  
- **Análisis IA** — abre Claude con el contexto completo del chart  

## 📊 Tickers incluidos por defecto

AAPL, NVDA, AMZN, MSFT, UBER, NFLX, META, HOOD, C, NKE, DIS, VZ, NVDL, AMZU, AMDL

## 🔧 Cómo añadir más funciones

Abre claude.ai y dile:  
> "Quiero añadir [RSI / MACD / Bollinger Bands / señales automáticas] a mi visor LeonardoTrader"

Pega el contenido de `index.html` y te genero el código actualizado.

## 📁 Estructura del proyecto

```
leonardo-trader/
├── public/
│   └── index.html    ← toda la app (un solo archivo)
├── vercel.json       ← configuración de Vercel
└── README.md
```

## 🌐 Data source

Yahoo Finance API (pública, sin API key requerida).  
Proxy CORS: allorigins.win (gratuito).

---

Hecho con ♥ por LeonardoTrader
