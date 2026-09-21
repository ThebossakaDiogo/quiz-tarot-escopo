# Quiz Tarot — Versão Visual (Mock)

Este projeto contém **exclusivamente a camada visual e interativa** do Quiz Tarot. Todas as chamadas de backend, banco de dados (Supabase), scripts PHP, conexões com gateways de pagamento (ConnectPay / PIX real) e rastreadores externos foram removidos.

O fluxo visual está 100% preservado e funciona de forma independente e local.

---

## 🌟 O que está incluído e funcionando

- **Interface Completa:** Todos os estilos, fontes, imagens, ícones e vídeos originais.
- **Quiz de Tarot:** Animações das cartas, perguntas e seleção de opções.
- **Modais de Pagamento Simulados:** Os modais de geração de chave PIX exibem QR Codes e códigos copia-e-cola fictícios, com um botão exclusivo **"⚡ Simular Confirmação do Pagamento (Visual)"** para você testar a transição de telas sem precisar de dinheiro ou gateways reais.
- **Chat Interativo com a Taróloga (`/contato`):** Respostas automáticas pré-configuradas e simulação de oráculo integrados no próprio navegador, sem depender de scripts PHP ou APIs externas.
- **Páginas Institucionais:** Termos de Uso e Políticas de Privacidade com navegação interna funcional.

---

## 📂 Estrutura de Páginas

| Arquivo | Descrição |
| :--- | :--- |
| [`index.html`](index.html) | Página inicial com quiz interativo das cartas de tarot |
| [`resultado.html`](resultado.html) | Resultado da leitura, depoimentos em vídeo e planos da vela |
| [`escrever-carta.html`](escrever-carta.html) | Tela para redigir intenções no mapa amoroso |
| [`chamada-ao-vivo-milena.html`](chamada-ao-vivo-milena.html) | Agendamento visual de chamada espiritual ao vivo |
| [`obrigado.html`](obrigado.html) | Tela de agradecimento e confirmação com botão para o chat |
| [`contato/index.html`](contato/index.html) | Chat interativo simulado com a Médium Milena |
| [`termos.html`](termos.html) | Termos de uso e condições |
| [`privacidade.html`](privacidade.html) | Políticas de privacidade |

---

## 🚀 Como Executar

### Opção 1: Direto no Navegador (Mais Simples)
Basta dar um duplo clique no arquivo [`index.html`](index.html) para abrir diretamente no seu navegador (Google Chrome, Edge, etc.).

### Opção 2: Servidor Local com Vite (Recomendado)
Se você tiver o [Node.js](https://nodejs.org/) instalado em seu computador:

1. Abra o terminal nesta pasta (`d:\tarot`).
2. Instale as dependências de desenvolvimento:
   ```bash
   npm install
   ```
3. Inicie o servidor local:
   ```bash
   npm run dev
   ```
4. O terminal informará o endereço local (geralmente `http://localhost:5173/`).

---

## 🔒 Segurança e Limpeza

- ❌ Nenhuma chave de API ou credencial.
- ❌ Nenhum arquivo `.php` ou backend serverless.
- ❌ Nenhum script rastreador (UTMify, TikTok Pixel, Facebook Pixel, Clarity).
- ✅ `.gitignore` configurado para prevenir que arquivos de ambiente ou caches sejam versionados por engano.
