# projection-vr

Projeto de construção de um óculos de realidade virtual de baixo custo e de experiência topo de linha, integrado aos principais sistemas operacionais onde o processamento real será feito por um dispositivo externo ao óculos e smartphone.

![Exemplo de óculos VR!](https://github.com/duplow/projection-vr/blob/4c8d42e0e3d27e1373ae9be9939a5c16fd23e9cf/xiaomi-and-oculus-the-next-generation-of-vr-006.jpg)
*Imagem ilustrativa*

### Detalhes

O projeto é constituído de um óculos VR comum de lentes ala [Google Cardboard](https://arvr.google.com/cardboard/) com um smartphone que irá reproduzir na tela as imagens fornecidas por uma fonte de processamento externo via WiFi e/ou Bluetooth. O processamento externo poderá ser feito por qualquer computador ou dispositivo compatível com o protocolo.

#### Componentes

 * Driver **emissor**
 * Aplicativo **receptor** para **Android**
 * **Óculos VR** comum

#### Driver/aplicativo receptor
O receptores são aplicações que fornecem informações de direção e botões e recebem os gráficos processados como resposta do emissor. está planejado o desenvolvimento de um aplicativo nativo para Android por se o sistema móvel mais amplamente utilizado hoje em dia, porém por se tratar não apenas de um aplicativo e sim um protocolo de comunicação se torna viável a implementação de um app para IOS ou outros SOs posteriormente.

#### Driver emissor
Emissores são a fonte de processamento dos gráficos mostrados nos receptores e por consequência nos óculos. A alienação do processamento dos gráficos ao óculos possibilita uma experiência equivalente ou superior os principais equipamentos fornecidos hoje por empresas como Facebook e Microsoft.

Qualquer dispositivo poderá gerar os gráficos e emiti-los pelo protocolo, inicialmente será feito um driver para Windows e Linux possibilitando a criação de um ambiente virtual.

#### Óculos VR comum
Assim como o nome diz, trata-se de um óculos VR normal cuja a única função é fornecer a experiência tridimensional pelas duas lentes. Qualquer óculos VR que use um smartphone Android se torna elégivel para o projeto. Recomendamos o [Google Cardboard](https://arvr.google.com/cardboard/) pelo seu baixo custo e facilidade de fabricação.
