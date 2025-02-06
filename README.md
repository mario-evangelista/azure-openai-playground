# Azure OpenAI no Playground

## Sobre o Projeto
Este repositório documenta a exploração e aprendizado sobre o uso do Playground do Azure OpenAI, uma plataforma que permite testar, configurar e prototipar soluções baseadas em inteligência artificial. Através desta experiência, buscamos compreender os principais recursos, boas práticas e configurações para a geração de conteúdos multimodais.

## Objetivos
- Aprender como configurar e implantar um recurso do Azure OpenAI.
- Compreender as funcionalidades e parâmetros do Playground.
- Desenvolver prompts eficientes para diferentes propósitos.
- Explorar a geração de conteúdos multimodais, incluindo texto, som e imagem.

---

## Configuração Inicial

### **Pré-requisitos**
Para utilizar o Playground do Azure OpenAI, é necessário:
- Conta válida no Azure.
- Permissão de administrador para criar e gerenciar recursos do Azure OpenAI.
- Método de pagamento configurado ou créditos Azure disponíveis.

### **Passo a Passo para Configuração**
1. **Verificar Permissões:** Certifique-se de que você possui permissões administrativas no Azure.
2. **Criar o Recurso:** Acesse o portal do Azure e siga as instruções para criar um recurso do Azure OpenAI.
3. **Acessar o Playground:** Navegue até o Azure AI Foundry para explorar e utilizar os recursos configurados.
4. **Configurar Parâmetros:** Defina os parâmetros iniciais conforme suas necessidades para testes e prototipagem.

---

## Parâmetros Importantes

### **Temperatura**
- Controla o grau de aleatoriedade nas respostas geradas.
- Valores baixos (próximos de 0) geram respostas determinísticas e previsíveis.
- Valores altos (próximos de 1) promovem respostas mais criativas e variadas.

### **Top-P (Núcleo de Probabilidade)**
- Define a fração das palavras mais prováveis que podem ser usadas na resposta.
- Um valor de 0.1 considera apenas as palavras mais prováveis, enquanto 0.9 permite maior variedade.

### **Tokens Máximos**
- Determina o comprimento máximo das respostas geradas.
- Ideal para limitar respostas muito extensas.

### **Penalidades**
- *Frequency Penalty:* Penaliza a repetição de palavras.
- *Presence Penalty:* Incentiva a introdução de novas palavras.

### **System Message**
- Define o contexto inicial e o comportamento desejado do modelo.
- Pode incluir instruções sobre estilo, tom e estrutura das respostas.

---

## Boas Práticas
- **Inicie com Configurações Padrão:** Explore inicialmente os parâmetros predefinidos.
- **Ajuste um Parâmetro por Vez:** Avalie o impacto de cada alteração isoladamente.
- **Documente os Resultados:** Mantenha registros das configurações e resultados obtidos.
- **Itere com Base em Feedback:** Refinar continuamente os prompts com base nos testes.

---

## Casos de Uso
- **Geração de Prompts Complexos:** Criar interações naturais e sofisticadas com assistentes virtuais.
- **Desenvolvimento de Sistemas CLI:** Implementação de assistentes de linha de comando.
- **Prototipagem Visual com DALL-E:** Exploração da criação de imagens com IA.
- **Testes com Integração de Blobs:** Manipulação e integração de dados no Azure.
- **Conversão Texto-Fala:** Geração de áudio automatizado a partir de textos.

---

## Dicas para Engenharia de Prompts
1. **Clareza:** Certifique-se de que o prompt é claro e direto.
2. **Especificidade:** Inclua informações detalhadas para guiar o modelo.
3. **Contexto:** Forneça um contexto inicial relevante.
4. **Estrutura:** Utilize listas, exemplos ou instruções passo a passo, quando necessário.

---

## Links Úteis
- [Documentação Oficial do Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai)
- [Artigos sobre Engenharia de Prompts](https://web.dio.me/articles)
- [Temperatura e Top-P Explicados](https://medium.com/@1511425435311/understanding-openais-temperature-and-top-p-parameters-in-language-models-d2066504684f)
- [Quickstart de Text-to-Speech](https://learn.microsoft.com/en-us/azure/ai-services/openai/text-to-speech-quickstart)

---

## Contribuições
Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

---

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).
