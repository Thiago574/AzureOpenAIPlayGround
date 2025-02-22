# AzureOpenAIPlayGround
# Azure OpenAI Resource Creation

Este documento descreve o processo para criar um recurso do Azure OpenAI por meio do portal do Azure.

## 📘 **Visão Geral**

A criação de um recurso do Azure OpenAI permite acessar os serviços de IA generativa da Microsoft para integração em aplicações. Abaixo está o processo passo a passo para criar esse recurso.

---

## ⚙️ **Processo de Criação de Recurso Azure OpenAI**

1. **Acesse o Portal do Azure:**
   - Acesse o [portal do Azure](https://portal.azure.com/) e faça login com sua conta.

2. **Criar um Recurso:**
   - No menu esquerdo, clique em **Criar um recurso**.
   - Pesquise por **Azure OpenAI**.
   - Selecione **Serviço Azure OpenAI** e clique em **Criar**.

3. **Configurar Detalhes do Recurso:**
   - **Assinatura:** Selecione a assinatura do Azure desejada.
   - **Grupo de Recursos:** Escolha um existente ou crie um novo.
   - **Nome do Recurso:** Defina um nome único para identificar o recurso.
   - **Região:** Escolha a região suportada para o Azure OpenAI (ex.: "East US").

4. **Definir Camada de Preço:**
   - Escolha a camada de preço adequada com base no uso previsto.

5. **Revisar e Criar:**
   - Revise todas as configurações.
   - Clique em **Criar** para provisionar o recurso.

6. **Acessar o Recurso:**
   - Após a implantação bem-sucedida, acesse o recurso criado para gerenciar chaves de acesso e configurações.

---

## 🔑 **Próximos Passos**

- **Configurar Chaves e Endpoint:** Navegue até a seção **Chaves e Endpoint** no recurso do Azure OpenAI.
- **Implantar Modelos:** Configure os modelos desejados para uso.
- **Integração:** Utilize as chaves de API em seus aplicativos para começar a interagir com os serviços de IA.

Para mais detalhes, consulte a [documentação oficial do Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/create-resource?pivots=web-portal).

---

## 🤝 **Suporte**

Em caso de dúvidas ou problemas, consulte a Central de Ajuda do Azure ou entre em contato com o suporte técnico do Azure.

---

## 📚 **Conteúdo Relacionado**

Aqui estão alguns conceitos importantes relacionados ao uso do Azure OpenAI:

- **Tokenização:** Processo de dividir o texto em unidades menores (tokens) para análise pelo modelo.
- **System Message:** Mensagem inicial que define o comportamento do modelo durante a interação.
- **Temperatura vs. Top-p:** Parâmetros que controlam a aleatoriedade das respostas geradas. A temperatura ajusta a imprevisibilidade, enquanto o Top-p limita as escolhas mais prováveis.
- **Multimodalidade:** Capacidade de processar diferentes tipos de dados, como texto e imagem, simultaneamente.
- **Playground Azure:** Interface gráfica no portal do Azure para testar prompts e ajustar parâmetros do modelo de forma intuitiva.

