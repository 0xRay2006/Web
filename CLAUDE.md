# Trading Terminal

## Stack
- Frontend: React 18 + Vite + TypeScript, Tailwind
- Charts: lightweight-charts (TradingView open source)
- State: Zustand
- Data: IBKR Client Portal API (行情/持倉), Binance WebSocket (crypto)
- Deploy: Vercel

## Design
- Bloomberg/Wind 終端風格：深色底 (#0a0a0a)、等寬數字字體 (JetBrains Mono)
- 漲綠跌紅（美股慣例）／漲紅跌綠（台股慣例）— 依市場切換
- 高資訊密度、無多餘留白、grid-based 可拖拉面板

## Conventions
- Functional components only, no class components
- All I/O async
- Docstrings on public functions
