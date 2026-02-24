# 🏔️ Método Everest — Deploy no Vercel

## O que está nesta pasta

- `index.html` — O app completo (PWA)
- `manifest.json` — Configuração de instalação na tela inicial
- `sw.js` — Service Worker (funciona offline)
- `DEPLOY.md` — Este arquivo

---

## Como colocar no ar em 10 minutos

### Passo 1 — Crie uma conta gratuita
Acesse [vercel.com](https://vercel.com) e crie uma conta (pode entrar com Google).

### Passo 2 — Instale a Vercel CLI (opcional, mais fácil)
Se preferir pelo navegador, pule para o Passo 3.

```bash
npm install -g vercel
vercel login
vercel --prod
```

### Passo 3 — Deploy pelo navegador (sem código)
1. Acesse [vercel.com/new](https://vercel.com/new)
2. Clique em **"Browse"** ou **"Import"**
3. Selecione esta pasta (`everest-app`)
4. Clique em **Deploy**
5. Em ~30 segundos você terá uma URL do tipo: `everest-app.vercel.app`

---

## Como adicionar à tela inicial (instruções para o aluno)

### Android (Chrome):
1. Abrir o app no Chrome
2. Menu (⋮) → "Adicionar à tela inicial"
3. Confirmar

### iPhone (Safari):
1. Abrir o app no Safari
2. Botão de compartilhar (□↑) → "Adicionar à Tela de Início"
3. Confirmar

---

## Domínio personalizado (opcional)
No painel da Vercel: Settings → Domains → Add Domain
Recomendado: `metodoeverest.com.br` ou `app.metodoeverest.com.br`

---

## Funcionalidades do MVP

✅ Login e cadastro com email/senha  
✅ Checklist diário com 15 protocolos (4 pilares)  
✅ Dashboard com ring de progresso diário  
✅ Streak dos últimos 7 dias  
✅ Página de progresso com gráfico de 14 dias  
✅ Breakdown por pilar (% da semana)  
✅ Dados salvos localmente por usuário  
✅ Instalável como app na tela inicial  
✅ Funciona offline  

---

## Próximas versões (quando tiver orçamento)

- [ ] Banco de dados na nuvem (sincroniza entre dispositivos)
- [ ] Notificações push automáticas
- [ ] Biblioteca de vídeos por protocolo
- [ ] Comunidade e feed interno
- [ ] Integração com pagamento (Kiwify)
