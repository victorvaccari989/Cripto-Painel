# CriptoPainel — versão inicial

Site responsivo para acompanhar gráficos e cotações de criptomoedas no navegador.

## O que já tem
- Gráfico de candles interativo
- Bitcoin, Ethereum, Solana, BNB, XRP, Dogecoin, Cardano e Litecoin
- Períodos de 1m, 5m, 15m, 30m, 1h, 4h, **12h** e 1D
- Lista de cotações em destaque
- Tema escuro adaptado ao celular

## Publicar gratuitamente com GitHub Pages
1. Crie um repositório público chamado `cripto-painel` no GitHub.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Entre em **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha `main` e `/ (root)`, depois salve.
6. Aguarde a publicação e abra a URL indicada pelo GitHub Pages.

## Dados e limitações
- Os dados vêm dos endpoints públicos da Binance e os pares são cotados em USDT, não em reais.
- O site precisa de internet; a disponibilidade pode variar por região ou limite da API.
- RSI, MACD, médias móveis e alertas ainda não foram implementados nesta versão.
- A biblioteca de gráficos é carregada por CDN.
- Protótipo educacional, não é recomendação de investimento.
