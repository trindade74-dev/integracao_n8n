# 🔗 Integração n8n com Webhook

Este projeto demonstra como integrar um software externo com o **n8n** utilizando **webhooks**, armazenando os dados diretamente em uma **planilha do Google Sheets**.

---

## 📋 Requisitos

Antes de começar, você vai precisar de:

* ✅ n8n instalado e rodando
* ✅ Uma planilha no Google Sheets para armazenamento dos dados
* ✅ Credenciais da API do Google Sheets configuradas no n8n

---

## 🚀 Como usar

Siga os passos abaixo para configurar e executar a integração:

### 1. Importar o workflow

Abra o arquivo `workflow-exemplo.json` e importe no n8n.

### 2. Configurar credenciais

* Acesse o nó do Google Sheets dentro do workflow
* Insira suas credenciais da API corretamente

### 3. Ativar o webhook

* Ative o workflow no n8n
* Copie a URL do webhook gerada

### 4. Executar o script

No terminal, rode:

```bash
node .\integracaon8n.js
```

---

## 📦 O que está incluído

* 📁 **Workflow de exemplo** pronto para uso
* 🔢 **Formatação de números** para facilitar o armazenamento na planilha
* 💻 **Menu interativo no terminal** para envio de dados

---

## 💡 Observações

* Certifique-se de que o n8n está acessível (local ou servidor)
* Verifique se a planilha tem permissões corretas para escrita
* O webhook deve estar ativo antes de rodar o script

---

## 🛠️ Possíveis melhorias

* Adicionar validação de dados antes do envio
* Criar logs de erro no terminal
* Implementar autenticação no webhook

---

## 📄 Licença

Este projeto é livre para uso e modificação.
