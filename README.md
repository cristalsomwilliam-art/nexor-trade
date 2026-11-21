# Nexor Trade

**Nexor Trade** é um terminal profissional desktop para análise técnica institucional, monitoramento multi-corretoras e execução de operações cripto (Binance, Bitget, Bybit e BingX).

---

## 📥 Download (Windows 64-bit — v1.3.2)

Acesse a página de [**Releases**](https://github.com/cristalsomwilliam-art/nexor-trade/releases/latest) e baixe uma das opções abaixo:

- **`NexorTrade.exe`** *(Mais simples — Executável Único)*: apenas baixe e dê dois cliques para abrir.
- **`NexorTrade-v1.3.2-win64.zip`** *(Versão Portátil — mais rápida para abrir)*: clique com o botão direito no `.zip` → **Extrair Tudo...** para uma pasta no seu PC e só então abra `NexorTrade.exe` dentro da pasta extraída *(não execute direto de dentro do `.zip` fechado)*.

> **Observação sobre o Windows SmartScreen:** como o executável é distribuído de forma independente sem certificado pago da Microsoft, o Windows pode exibir um aviso na primeira execução. Clique em **Mais informações** → **Executar assim mesmo**.

---

## ✨ Recursos Principais

- **Estabilidade Desktop (v1.3.2):** inicialização GUI sem console (`--windowed`) corrigida e testada diretamente no executável `.EXE`.
- **Bitget Futures (Passphrase Criptografada):** descriptografia automática da Passphrase na consulta de saldo e margem livre reais.
- **Filtros Anti-Falsos Sinais:** validação de sustentação do gatilho Stormer 123 (bloqueio de pavios de martelo/estrela cadente), trava de conflito macro bidirecional com Bitcoin, filtro rigoroso de exaustão por RSI e banner exclusivo para sinais aprovados (`FIQUE DE FORA` nunca entra no banner).
- **Ficha Completa da Moeda no Gráfico:** carregamento paralelo (~1,2s) com Mercado 24h, Funding Rate, Open Interest, Long/Short Ratio, Market Cap, FDV, Supply em Circulação, ATH, TVL, EMAs, RSI, ATR, Suporte/Resistência, Força vs BTC, Pontos Fortes e Alertas.
- **Multi-Corretoras Oficiais:** suporte às APIs oficiais da Binance, Bitget Futures, Bybit e BingX (ambientes Simulado e Real).
- **Segurança em Primeiro Lugar:** inicia desconectado em modo **Fictício**, criptografa credenciais localmente com `Fernet` + `PBKDF2`, exige trava de instância única e possui **STOP GERAL** de emergência.
- **Gráfico Profissional & Raio-X Preciso:** VWAP Ancorada (±1σ, ±2σ, ±3σ), EMAs, RSI e salto automático de sinais Stormer / Divergência para o gráfico.
- **Módulo Scalp M15:** varredura de setups rápidos com cálculo de margem, risco em % do investimento, ganho estimado e disjuntor diário.
- **Atualização Automática:** verificação integrada de novas versões via GitHub Releases.

---

## 💻 Requisitos Mínimos

- Windows 10 ou Windows 11 (64-bit)
- Microsoft Edge ou Google Chrome instalado (usado para renderização nativa da janela desktop)
- Conexão com a internet para cotações em tempo real e APIs das corretoras
