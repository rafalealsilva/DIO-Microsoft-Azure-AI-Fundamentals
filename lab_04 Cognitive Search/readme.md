# Machine Learning na Prática no Azure ML

## Objetivo
Extrair informações de uma fonte de dados para enriquecer sua própria base de informações usando IA


### ETAPA 1: Criação do Azure AI Services
- Acessar https://portal.azure.com com credenciais Microsoft.
- "All Services" >> "Azure AI Services" >> AI Search

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/6c72c689b68b5c3b0c3215e24716b2667c545c09/lab_04%20Cognitive%20Search/misc/Screenshot_1.jpg)

- Sugere-se localização East US, visto que os custos são menores que no Brasil

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/6c72c689b68b5c3b0c3215e24716b2667c545c09/lab_04%20Cognitive%20Search/misc/Screenshot_3.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/6c72c689b68b5c3b0c3215e24716b2667c545c09/lab_04%20Cognitive%20Search/misc/Screenshot_4.jpg)


### ETAPA 2: Criação de um Recurso de IA

- Preencha os dados solicitados (imagens de exemplo abaixo)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/771c3e6d52b04e5b522a8f9818b329ed2328d60b/lab_04%20Cognitive%20Search/misc/Screenshot_5.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/771c3e6d52b04e5b522a8f9818b329ed2328d60b/lab_04%20Cognitive%20Search/misc/Screenshot_6.jpg)

- Pressione "Create" e aguarde uns instantes

Neste momento, temos 2 serviços rodando:
- Azure AI Services
- AI Search


### ETAPA 2: Criação de uma Conta de Armazenamento

- Selecione "Store accounts" >> Create

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/c77fa7ee9315a395da9282167d2a48fde4c81b18/lab_04%20Cognitive%20Search/misc/Screenshot_7.jpg)

- Importante selecionar as opções marcadas na imagem

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/c77fa7ee9315a395da9282167d2a48fde4c81b18/lab_04%20Cognitive%20Search/misc/Screenshot_8.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/c77fa7ee9315a395da9282167d2a48fde4c81b18/lab_04%20Cognitive%20Search/misc/Screenshot_9.jpg)


### ETAPA 3: Configuração da Conta de Armazenamento

- Será necessário liberar acessos anônimos para o correto funcioanemtno desta prática
- Esta configuração é necessária pois a opção default de segurança do armazenamento não habilita tais acessos

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/7fe7484674f8e3c66ee84b18e84662cbbaf7d362/lab_04%20Cognitive%20Search/misc/Screenshot_10.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/7fe7484674f8e3c66ee84b18e84662cbbaf7d362/lab_04%20Cognitive%20Search/misc/Screenshot_11.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/7fe7484674f8e3c66ee84b18e84662cbbaf7d362/lab_04%20Cognitive%20Search/misc/Screenshot_12.jpg)


### ETAPA 4: Adicionando arquivos

Acesse o endereço abaixo para carregar os arquivos de configuração em seu armazenamento criado

![ARQUIVOS](https://aka.ms/mslearn-coffee-reviews)

- Clique em "Upload" e carregue os arquivos dentro do arquivo zip baixado no link acima.

- Navegue aé o serviço de Busca criado anteriormente

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/7f496d5f12d683b9c5ee28c146d7b1400d02c114/lab_04%20Cognitive%20Search/misc/Screenshot_13.jpg)

- Clique em "Import Data"
- Data Source: "Azure Blob Storage"
- Dê um nome
- Data to extract: "Content and metadata"
- Parsing mode: Default
- Connection string: "*Select Choose an existing connection"
- Selecione o armazenamento criado anteriormente, e clique em "Select"

- Selecione opções de acordo com imagens a seguir

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/f9b682114d3e34a99049a03c193d3d6944c3882d/lab_04%20Cognitive%20Search/misc/Screenshot_14.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/f9b682114d3e34a99049a03c193d3d6944c3882d/lab_04%20Cognitive%20Search/misc/Screenshot_15.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/f9b682114d3e34a99049a03c193d3d6944c3882d/lab_04%20Cognitive%20Search/misc/Screenshot_16.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/f9b682114d3e34a99049a03c193d3d6944c3882d/lab_04%20Cognitive%20Search/misc/Screenshot_17.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/f9b682114d3e34a99049a03c193d3d6944c3882d/lab_04%20Cognitive%20Search/misc/Screenshot_18.jpg)


Em "Choose an existing connection", selecione suas conexões (criadas anteiormente)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/f9b682114d3e34a99049a03c193d3d6944c3882d/lab_04%20Cognitive%20Search/misc/Screenshot_19.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/f9b682114d3e34a99049a03c193d3d6944c3882d/lab_04%20Cognitive%20Search/misc/Screenshot_20.jpg)

![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/f9b682114d3e34a99049a03c193d3d6944c3882d/lab_04%20Cognitive%20Search/misc/Screenshot_21.jpg)


### ETAPA 5: Usando o Serviço

- Clique em "home" >> (selecione o serviço de busca criado) >> Search Explore
- Exemplo de busca: search=locations:'Angeles'


![](https://github.com/rafalealsilva/DIO-Microsoft-Azure-AI-Fundamentals/blob/675dfc5698ac73def78e83ecb035af242a1de557/lab_04%20Cognitive%20Search/misc/Screenshot_22.jpg)
