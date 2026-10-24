# Rv-web3 | Plataforma Web3 de Ativos Reais

[![Production Ready](https://img.shields.io/badge/Status-Produção%20Real-red.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Ethers.js](https://img.shields.io/badge/Ethers.js-v6-blue.svg)]()
[![Vite](https://img.shields.io/badge/Vite-5-purple.svg)]()

Plataforma Web3 completa desenvolvida com **Vite**, **Vanilla JavaScript** e **Ethers.js v6**, projetada para interagir com redes blockchain reais (Mainnet/L2s) movimentando **ativos e valores reais**.

---

## 🚨 AVISOS DE SEGURANÇA CRÍTICOS (LEIA ANTES DE USAR)

1. **ATIVOS REAIS E IRREVERSÍVEIS:** Este software interage com redes de produção reais. Qualquer transação enviada (transferências, contratos, etc.) consome criptomoedas reais (como ETH) e **não pode ser desfeita ou revertida**.
2. **CHAVES PRIVADAS E CREDENCIAIS:** 
   - **NUNCA** insira chaves privadas, frases-semente (*seed phrases*) ou senhas no código fonte, arquivos de configuração `.env` ou em inputs da aplicação.
   - O projeto utiliza exclusivamente carteiras externas injetadas pelo usuário (como MetaMask, Rabby ou WalletConnect), garantindo que suas chaves privadas jamais deixem sua extensão de carteira segura.
3. **VALIDAÇÃO DE ENDEREÇOS:** Sempre verifique rigorosamente os endereços de destino antes de confirmar qualquer transação na sua carteira. Ataques de *clipboard poisoning* (substituição de endereço por malware) são comuns em ambientes Web3.
4. **TAXAS DE GÁS:** Esteja ciente das flutuações nas taxas de gás da rede antes de confirmar operações de alto valor.
5. **REDES OFICIAIS:** Confirme sempre a network ID e o RPC antes de assinar qualquer transação.

---

## 📋 Pré-requisitos

- **Node.js** 18.x ou superior
- **npm** 9.x ou superior
- Extensão de carteira Web3 (MetaMask, Rabby, etc.) configurada na rede desejada
- Conta com saldo real de ETH (ou token nativo da rede) para gás

---

## ⚙️ Configuração e Instalação

```bash
# 1. Clone ou entre na pasta do projeto
cd rv-web3

# 2. Instale as dependências
npm install

# 3. Inicie o servidor de desenvolvimento
npm run dev

# 4. Build de produção
npm run build

# 5. Preview do build
npm run preview
