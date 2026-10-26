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

```bash
# Clone o repositório ou entre na pasta do projeto
cd rv-web3

# Instalar dependências
npm install

# Iniciar servidor backend (terminal 1)
npm run server

# Iniciar frontend (terminal 2 — em outra janela)
npm run dev
 
 
 
 
📄 Licença
 
MIT License
 
Copyright © 2026 Rv-web3
 
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
 
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
 
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
 
plaintext
  

---
