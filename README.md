# gtag-sha256-conversion
This repository is a Tag Template for Google tag manager whose purpose is to Hash (encrypt) data, for safe storage and/or later use. the Hash data can be stored in cookies or  google DataLayer object for imediate consuption.

Hash string is the common way to secure sensitive data before transmiting, when using GTM tags for tracking like meta and GA4 tracking code, Sensitive data is automatically hashed, so usually you don't need to do it yourself, but if you need/want to manipulate that data yourself, you need to protect it. A common use of this tag, is to save sensitive data in cookies at the moment of collection and then, on later pages/events, send that data to your tracking tool to informa a conversion have been made. 


Esse repositório é uma Tag Template do Google Tag Manager (GTM), com o propósito de prover de encriptar (Hash) dados sensíveis, seja para armazena-lo e/ou consumi-lo por outras tags do GTM. o Dados em Hash podem ser armazenados em cookies ou no DataLayer do google para consumo de outras tags do GTM.
Hash é a maneira convencional de encriptar dados sensiveis (email, cpf, nome) antes de transmiti-lo. quando usamos tags de trackeamento no GTM, como facebook Pixel ou GA4, as informações sensiveis já são encriptadas por padrão, porém caso você precise manipula-las manualmente você precisa fazer a encriptação para não correr o risco de expor essas informações sensíveis. 
Um exemplo comum do uso dessa tag, é armazenar os dados sensíveis em cookies (dados encriptados) para em outras páginas enviá-lo para as plataformas de tracking comunicando o evento ou conversão.
