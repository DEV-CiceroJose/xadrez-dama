# Xadrez ETE

Aplicação web de jogos de tabuleiro para partidas locais no mesmo dispositivo.

## Funcionalidades
- Xadrez com validação de movimentos, roque, en passant, promoção, xeque, xeque-mate e empate (motor `chess.js`).
- Damas em tabuleiro 8×8, com captura obrigatória, sequência de capturas para o jogador e promoção a dama. (Regras simplificadas; não implementa todas as particularidades das damas brasileiras.)
- Modos contra computador e dois jogadores locais.
- Três níveis de dificuldade, interface responsiva e reinício de partida.

## Executar localmente
Requer Node.js 18 ou superior.

```bash
npm install
npm run dev
```

Abra o endereço local informado pelo Vite (normalmente http://localhost:5173).

## Gerar versão de produção
```bash
npm run build
npm run preview
```

A pasta `dist/` contém o site estático.

## Publicar na Render
Crie um **Static Site** conectado ao repositório GitHub:
- Build Command: `npm install && npm run build`
- Publish Directory: `dist`
- URL desejada: `xadrez-ete.onrender.com` (se disponível na conta Render).

O arquivo `render.yaml` também contém a configuração declarativa do serviço.
