# Trabalhando com Machine Learning na Prática no Azure ML

## Objetivo
Reconhecimento Facial e transformação de imagens em Dados no Azure ML

### ETAPA 1: Criação do Azure AI Services
- Acesso a https://portal.azure.com com credenciais Microsoft.
- Create a resource
- Categories: AI + Machine Learning
- Azure IA service: Create

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/90eced3abf19e76c2f675bcb63a0cfda6f7a3ba6/lab_02%20image%20face%20ocr/misc/01.jpg)


### ETAPA 2: Configuração do Azure AI Services

- Resource group: crie um novo ou selecione um resource criado previamente
- Region: East US (de acordo com o vídeo, custo de serviço mais barato que no Brasil)
- Name
- Pricing tier: Standard S0
- Marca a caixa: "By checking this box I acknowledge that I have read and understood all the terms below"
- Review + create

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/c0946fc8030935d8ff07326c612975c0eac59334/lab_02%20image%20face%20ocr/misc/02.jpg)

- Create

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/f0370e8c32c14dda6f2d4fe7378c734c424149ee/lab_02%20image%20face%20ocr/misc/02_1.jpg)

- "Go to resource"
- Checar "Status: Active"

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/72009eb0470b17d84a8449bd0aad41283a3340d0/lab_02%20image%20face%20ocr/misc/02_2.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/72009eb0470b17d84a8449bd0aad41283a3340d0/lab_02%20image%20face%20ocr/misc/02_3.jpg)


### ETAPA 3: Configuração Vision Studio

- Acessar https://portal.vision.cognitive.azure.com/ com suas credenciais
- Clicar em "View All Resources"

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/e2963916dab99ac61058dea43b3181c0bdca56a0/lab_02%20image%20face%20ocr/misc/03.jpg)

- Selecione o "Resource" criado
- Selecione "Select as default resource"
- Feche no X

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/e2963916dab99ac61058dea43b3181c0bdca56a0/lab_02%20image%20face%20ocr/misc/03_2.jpg)

- Entre na aba "Face"
- Selecione Detect faces in an image

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/e2963916dab99ac61058dea43b3181c0bdca56a0/lab_02%20image%20face%20ocr/misc/03_3.jpg)

