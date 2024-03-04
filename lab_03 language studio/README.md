# Machine Learning na Prática no Azure ML

## Objetivo
Reconhecimento de sentimentos expressos via texto no Azure ML



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

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/401adf2241b2816b2c9d502224bc38774ed393e0/lab_03%20language%20studio/misc/Screenshot_7.jpg)



### ETAPA 3: Analyze sentiment and opinions

- Acessar [https://portal.vision.cognitive.azure.com/](https://language.cognitive.azure.com/) com suas credenciais
- Selecione as opções que você criou anteriormente
- Resource type: language
- Pressione "done"

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/9d8c2274dff9e369bc2eda62f278a579032bbc4b/lab_03%20language%20studio/misc/Screenshot_8.jpg)

- Entre na aba "Classify text"
- Selecione "Analyze sentiment and mine opinions"

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/9d8c2274dff9e369bc2eda62f278a579032bbc4b/lab_03%20language%20studio/misc/Screenshot_9.jpg)

- Insira uma opinião positiva ou negativa sobre um produto / hotel / viagem etc. Por exemplo: https://www.tripadvisor.com.br/
- Selecione a língua do texto usado
- Marque a caixa logo antes do botão "Run"
- Teste em "Run"
- Sugestão: faça testes com as melhores e as piores opiniões, e compare o resultado da Azure com o resultado do site utilizado


### ETAPA 4: Testes!

- Para os testes a seguir, um hotel foi selecionado aleatoriamente no Tripadvisor.
- Foram usadas 3 opiniões de 1 estrela, 3 opiniões de 2 estrelas, 3 opiniões de 3 estrelas, 3 opiniões de 4 estrelas e 3 opiniões de 5 estrelas.
- Dentre opiniões grandes e pequenas, com e sem erro gramatical, gírias.... A Azure se saiu impressionantemente bem!

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/1%20star_01.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/1%20star_02.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/1%20star_03.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/2%20stars_01.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/2%20stars_02.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/2%20stars_03.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/3%20stars_01.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/3%20stars_02.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/3%20stars_03.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/4%20stars_01.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/4%20stars_02.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/4%20stars_03.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/5%20stars_01.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/5%20stars_02.jpg)
![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/324d43a0455d00f221dc91aee9ab1f5eeb1d1e54/lab_03%20language%20studio/outputs/5%20stars_03.jpg)
