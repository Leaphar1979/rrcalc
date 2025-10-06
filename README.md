# RRCalc – Risk/Reward Calculator (PWA)

**RRCalc** é uma calculadora de **Risco/Recompensa (R:R)** para **operações de Futuros**, compatível com o formato numérico da **MEXC**.  
WebApp leve, **offline-ready (PWA)** e mobile-first – pode ser instalado como app em iOS e Android.

## Funcionalidades
- Entradas: **Margem**, **Alavancagem**, **Preço de Entrada**, **Direção (LONG/SHORT)**, **TP%**, **SL%**  
- Saídas automáticas: **Exposição**, **Mov. de liquidação (~1/alavancagem)**, **Preço TP/SL**, **Lucro/Perda** (absoluto e relativo), **R:R (1:X)**
- Padrão MEXC: **ponto decimal** (ex.: `123370.00`, `0.9414`)
- **Autosave** local (localStorage) das últimas entradas

## Como usar
1. Acesse a página (GitHub Pages) e insira as entradas.  
2. O app calcula TP/SL, exposição e **R:R** automaticamente.  
3. **Adicionar à Tela Inicial** para usar como um app nativo (PWA).

## Instalação (PWA)
- **Android/Chrome**: Menu ⋮ → *Add to Home screen*  
- **iOS/Safari**: Compartilhar → *Adicionar à Tela de Início*

## Observações
- O movimento de liquidação é **aproximado** (pode variar por manutenção, funding e regras da corretora).
- Use **ponto** como separador decimal e **sem separador de milhar** (formato internacional).

## Licença
Este projeto é distribuído com finalidade educacional. Use por sua conta e risco.
