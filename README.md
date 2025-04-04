# tea_deploy_tx
This script use to tesnet TEA for deploy and auto tx
# Auto Deploy dan Transfer EVM

Aplikasi untuk otomatisasi deploy dan transfer token di jaringan EVM (Ethereum Virtual Machine).

## Fitur

- Deploy smart contract token
- Transfer token ke multiple wallet
- Manajemen wallet dan private key

## Struktur Proyek

```
├── config/
│   ├── chains.js    
│   ├── index.js    
│   └── gas.json    
├── contracts/
│   └── Token.sol    
├── data/
│   ├── deployments/
│   └── wallet.txt  
└── src/
    ├── services/
    │   ├── TokenDeployService.js    
    │   └── TokenTransferService.js  
    ├── utils/
    │   ├── displayHeader.js        
    │   └── walletmanager.js       
    ├── tokenApp.js  
    └── tokencli.js
```

## Instalasi

1. Clone repository ini
2. Install dependencies:
```bash
npm install
```
```bash
npx hardhat compile
```

## RUN
```bash
npm start
```

## Konfigurasi

1. Input PK
2. Sesuaikan konfigurasi chain di `config/chains.js`
3. Atur parameter gas di `config/gas.json`

## Kontribusi

Kontribusi selalu diterima. Silakan buat pull request untuk perbaikan atau penambahan fitur.

## License

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail.

