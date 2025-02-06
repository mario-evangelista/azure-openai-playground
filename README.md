# Azure OpenAI no Playground

## Sobre o Projeto
Este repositório documenta a exploração e aprendizado sobre o uso do Playground do Azure OpenAI, uma plataforma poderosa para testes, configurações e prototipagem com modelos de inteligência artificial.

## Objetivo
Compreender e aplicar boas práticas para:
- Configurar recursos do Azure OpenAI.
- Explorar a multimodalidade oferecida pelo Playground.
- Ajustar parâmetros para a geração de conteúdos de maneira eficiente.

## Configuração Inicial
### **Pré-requisitos**
Para utilizar o Playground do Azure OpenAI, você precisa de:
- Conta válida no Azure.
- Permissão de administrador para o Azure OpenAI.
- Método de pagamento ou créditos configurados.

### **Passos para Deploy**
1. Verifique se você tem as permissões necessárias.
2. No portal Azure, crie um recurso do Azure OpenAI.
3. Acesse o Playground via [Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/create-resource?pivots=web-portal).

## Configurações Importantes

### **Parâmetros de Configuração**
- **Temperatura:** Controla a aleatoriedade nas respostas. Valores altos (à volta de 1) promovem respostas mais criativas, enquanto valores baixos (à volta de 0) tornam as respostas mais determinísticas.
- **Top-P:** Define a quantidade de palavras consideradas nas respostas. Um Top-P de 0.9 permite respostas com mais variedade.
- **Tokens Máximos:** Limita o tamanho das respostas.
- **Penalidades:**
  - *Frequency Penalty:* Reduz a repetição de palavras.
  - *Presence Penalty:* Incentiva a introdução de novas palavras.

### **Boas Práticas**
- Comece com configurações padrão.
- Altere apenas um parâmetro por vez.
- Documente os resultados obtidos.
- Itere com base no feedback.

## Casos de Uso
- Geração de prompts complexos.
- Desenvolvimento de sistemas CLI.
- Prototipagem com DALL-E para geração de imagens.
- Testes com integração de Blobs.

## Referências 
- [Documentação Oficial do Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai)
- [Entendendo Temperatura e Top-P](https://medium.com/@1511425435311/understanding-openais-temperature-and-top-p-parameters-in-language-models-d2066504684f)

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou fazer pull requests.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).
