## Hidroject! 🌱 - informações
### Uma breve introdução - em que consiste a nossa organização/projeto?
Focamos no reaproveitamento faseado da água. Quando a umidade do solo fica abaixo do ideal, a bomba é acionada para irrigar mudas e/ou plantas de pequeno porte em geral. O excesso de água é filtrado e purificado, armazenado em um reservatório de 500ml (até o presente momento) para reutilização. Os não purificados são retidos em filtros e peneiras até a manutenção.

Para redirecionar a água purificada à planta, utiliza-se um sistema eletrônico empregando tecnologia [Arduino](https://arduino.cc) em placa [Uno](https://store.arduino.cc/products/arduino-uno-rev3), programada via [PlatformIO](https://platformio.org/), extensão do [Visual Studio Code](https://code.visualstudio.com/). Seu código em [C++](https://learn.microsoft.com/pt-br/cpp/cpp/) controla sensores hídricos por meio da biblioteca [Adafruit](https://learn.adafruit.com/dht/overview) [DHT Sensors](https://www.arduino.cc/reference/en/libraries/dht-sensor-library/). Em alternativa, pode-se usar o [IDE gráfico](https://www.arduino.cc/en/software) fornecido pelo próprio [Arduino](https://arduino.cc), caso haja falta de compatibilidade.

Embora a irrigação opere por alguns dias, observa-se a necessidade de intervenção humana para prevenir problemas como entupimentos no motor, entre outras questões. O propósito central do nosso projeto é concentrar esforços na reutilização da água, distinguindo-se assim de outros sistemas já existentes, ao apresentar a capacidade de se configurar como um recurso sustentável. 

### Directrizes de contribuição - De que maneira a comunidade pode engajar-se no projeto?
O empreendimento é conduzido pela comunidade, destinado à comunidade. Almeja-se contribuir? Realize um [fork](https://cursos.alura.com.br/forum/topico-qual-a-diferenca-entre-git-clone-e-o-fork-qual-o-melhor-para-se-usar-147054) do repositório, elabore um [README.md](https://www.alura.com.br/artigos/escrever-bom-readme) expondo suas ideias e proceda com a implementação. Posteriormente, avaliaremos sua solicitação de [pull request](https://www.alura.com.br/conteudo/git-github-branching-conflitos-pull-requests).

### Recursos úteis - Onde a comunidade pode acessar os arquivos documentos? Existe mais alguma informação que a comunidade deva ter conhecimento?
Todos os recursos estarão e permanecerão acessíveis em [Hidroject/Hidroject](https://github.com/Hidroject/Hidroject). Ademais, foi confeccionado um protótipo para a feira de ciências do Colégio Estadual Polivalente de Itanhém, utilizando um sistema mecânico em substituição à placa eletrônica, essa sendo esta substituída por um relógio. Este dispositivo ativa a bomba d'água através do toque de seu alarme. O desempenho foi conforme o esperado, realizando com precisão o ciclo da água de acordo com a teoria proposta.

Em breve, será desenvolvido um site  totalmente destinado à divulgação de informações abrangentes, não se limitando exclusivamente ao projeto em questão, mas abarcando também detalhes sobre seus criadores e a própria concepção da ideia. O elo para acesso estará prontamente disponibilizado no ápice da documentação, para aqueles que manifestarem interesse.

> “Em nós há a Luz da Natureza e essa Luz é Deus.” — Paracelso 1493–1541
