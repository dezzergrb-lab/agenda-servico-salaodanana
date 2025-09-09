# Salão da Naná — Agendamento (Vite + React + Tailwind)

App de agendamento para o **Salão da Naná** com serviços, calendário, horários e confirmação via WhatsApp.

## 🚀 Rodar localmente

```bash
npm install
npm run dev
# abra http://localhost:5173
```

## 🏗️ Build de produção

```bash
npm run build
npm run preview
```

## 🌐 Publicar no Netlify

1. Suba este projeto para um repositório **GitHub/GitLab/Bitbucket**.
2. No **Netlify**, clique em **Add new site** → **Import an existing project**.
3. Conecte seu repositório e confirme:
   - Build command: `npm run build`
   - Publish directory: `dist`
4. Deploy!

> Para SPA funcionar no Netlify, incluímos `public/_redirects` com: `/* /index.html 200`.

## 🧪 Testes (console)

Os testes básicos rodam no **console do navegador** quando o app é carregado (ver `src/App.jsx`).

## 📱 Mobile-first & iPhone

Layout vertical, sem rolagem lateral, e compatível com iPhone X+.