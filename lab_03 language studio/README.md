# Machine Learning na Prática no Azure ML

## Objetivo
Reconhecimento Facial e transformação de imagens em Dados no Azure ML



### ETAPA 1: Criação do Azure AI Services
- Acesso a https://portal.azure.com com credenciais Microsoft.
- Create a resource
- Categories: AI + Machine Learning
- Language Service: Create

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/afc253b931e29f6930055924810b484ccab6cb4c/lab_03%20language%20studio/misc/Screenshot_1.jpg)

- Clique no botão azul "Continue to create your resource"


### ETAPA 2: Create Language

- Resource group: crie um novo ou selecione um resource criado previamente
- Region: East US (de acordo com o vídeo, custo de serviço mais barato que no Brasil)
- Name - sua preferência
- Pricing tier: Free F0
- Marca a caixa: "By checking this box I certify that I have reviewed and acknowledge the terms in the Responsible AI Notice"
- Review + create

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/2cc9d080db6eeddd7fdcd1b28ae427ab0d215f87/lab_03%20language%20studio/misc/Screenshot_2.jpg)

- Create
- Aguarde um instante

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/2cc9d080db6eeddd7fdcd1b28ae427ab0d215f87/lab_03%20language%20studio/misc/Screenshot_3.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/2cc9d080db6eeddd7fdcd1b28ae427ab0d215f87/lab_03%20language%20studio/misc/Screenshot_4.jpg)

- Após finalizar "Deployment is in progress", pressione "Go to resource group"

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/2cc9d080db6eeddd7fdcd1b28ae427ab0d215f87/lab_03%20language%20studio/misc/Screenshot_5.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/2cc9d080db6eeddd7fdcd1b28ae427ab0d215f87/lab_03%20language%20studio/misc/Screenshot_6.jpg)

- Checar "Status: Active"


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
