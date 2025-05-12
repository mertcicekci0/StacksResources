# StacksResources




```mermaid
graph TD
    BTC[Bitcoin Layer 1] -->|Proof of Transfer| STX[Stacks Blockchain]
    STX -->|Clarity Contracts| CLARITY[Clarity Engine]
    STX -->|Stacks Blocks| BLOCKS[Block Production]
    STX -->|PoX Mekanizması| POX[Stacking ve Reward Dağılımı]
    STX -->|Köprüleme| SBTC[sBTC Bridge]
    SBTC --> BTC
    CLARITY --> TOKENS[SIP-010 Fungible Tokens]
    CLARITY --> NFT[NFT & Dijital Varlıklar]
    SBTC --> APP[Bitcoin Destekli dApp'ler]
    APP --> UI[Frontend (React, Next.js vb.)]
    UI --> USERS[Kullanıcı Etkileşimi]
```
