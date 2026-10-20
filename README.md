# Rv-web3 | Plataforma Web3 de Ativos Reais

[![Production Ready](https://img.shields.io/badge/Status-Produção%20Real-red.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Plataforma Web3 completa desenvolvida com **Vite**, **Vanilla JavaScript** e **Ethers.js v6**, projetada para interagir com redes blockchain reais (Mainnet/L2s) movimentando **ativos e valores reais**.

---

## 🚨 AVISOS DE SEGURANÇA CRÍTICOS (LEIA ANTES DE USAR)

1. **ATIVOS REAIS E IRREVERSÍVEIS:** Este software interage com redes de produção reais. Qualquer transação enviada (transferências, contratos, etc.) consome criptomoedas reais (como ETH) e **não pode ser desfeita ou revertida**.
2. **CHAVES PRIVADAS E CREDENCIAIS:** 
   - **NUNCA** insira chaves privadas, frases-semente (*seed phrases*) ou senhas no código fonte, arquivos de configuração `.env` ou em inputs da aplicação.
   - O projeto utiliza exclusivamente carteiras externas injetadas pelo usuário (como MetaMask, Rabby ou WalletConnect), garantindo que suas chaves privadas jamais deixem sua extensão de carteira segura.
3. **VALIDAÇÃO DE ENDEREÇOS:** Sempre verifique rigorosamente os endereços de destino antes de confirmar qualquer transação na sua carteira. Ataques de *clipboard poisoning* (substituição de endereço por malware) são comuns em ambientes Web3.
4. **TAXAS DE GÁS:** Esteja ciente das flutuações nas taxas de gás da rede antes de confirmar operações de alto valor.

---

## 📋 Pré-requisitos

- **Node.js** (versão 18.x ou superior recomendada)
- **npm** (versão 9.x ou superior)
- Extensão de carteira Web3 instalada no navegador (ex: MetaMask) configurada na rede desejada.

---

## ⚙️ Configuração e Instalação

1. Clone o repositório ou descompacte os arquivos na pasta do projeto:
   ```bash
   cd rv-web3
