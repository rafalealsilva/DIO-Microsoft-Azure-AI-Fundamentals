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


### ETAPA 3: Configuração Vision Studio para IMAGENS

- Acessar https://portal.vision.cognitive.azure.com/ com suas credenciais
- Clicar em "View All Resources"

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/e2963916dab99ac61058dea43b3181c0bdca56a0/lab_02%20image%20face%20ocr/misc/03.jpg)

- Selecione o "Resource" criado
- Selecione "Select as default resource"
- Feche no X

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/e2963916dab99ac61058dea43b3181c0bdca56a0/lab_02%20image%20face%20ocr/misc/03_2.jpg)

- Entre na aba "Face"
- Selecione "Detect faces in an image"

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/e2963916dab99ac61058dea43b3181c0bdca56a0/lab_02%20image%20face%20ocr/misc/03_3.jpg)

- Marque a caixa abaixo do texto "Try it out"
- Carregue suas imagens para testar - a aplicação exemplo detecta rosto, e se há uso de máscara ou não

- Segue exemplo abaixo. Repare a deteção difícil em "Face #8" (rosto de lado), corretamente identificado como "sem máscara"; e em "Face #13", marcado (creio que) incorretamente como "sem máscara".
- Quem tiver mais exemplos, bacana compartilhar.

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/8674ed26296d9578602ae5c4e95b11271d5cb9d7/lab_02%20image%20face%20ocr/misc/03_4.jpg)



### ETAPA 4: Configuração Vision Studio para TEXTO

- O processo é bem parecido para identificar texto.
- Volte para a página inicial

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/8c93dc9e821259e8ed11e8358f42d6a1447b1aa4/lab_02%20image%20face%20ocr/misc/04.jpg)

- Entre na aba "Optical Character Recogniton"
- Selecione "Extract text from images"

  ![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/8c93dc9e821259e8ed11e8358f42d6a1447b1aa4/lab_02%20image%20face%20ocr/misc/04_1.jpg)
