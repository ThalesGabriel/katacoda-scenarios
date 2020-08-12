## Criando cenário

Para criar um cenário você deve simplesmente rodar o comando ```katacoda scenarios:create```. O terminal fará algumas perguntas a respeito do projeto:

* **Friendly URL:** Aqui você pode digitar qualquer coisa, recomendo que digite ```cenario-teste```. Este atributo determina o nome da pasta do cenário e a url para acessá-lo. ```Não deve conter espaços, deve estar em caixa baixa, etc.```. Caso seu username seja ```username-teste``` e seu cenário for ```cenario-teste``` a url deste cenário na plataforma será  https://katacoda.com/username-teste/scenarios/cenario-teste/

* **Title:** O título do cenário 
* **Description:** A descrição do cenário 
* **Difficulty level:** O nível de dificuldade do cenário 
* **Estimated time:** Em minutos ou horas 
* **Number of steps:** Quantidade de passos para construir o cenário
* **Image:** Determina qual software básico estará disponível para o seu cenário. Por exemplo, se você precisa de docker, java, go, etc. como pré-requisito. Para obter mais informações, leia katacoda.com/docs/scenarios/environments
* **Layout:** Determina a disposição dos elementos de seu cenário. Por exemplo, se você deseja apresentar apenas um terminal, ou editor + terminal, etc. Para obter mais informações, leia katacoda.com/docs/scenarios/layouts

With this information, the CLI will create a folder with the name of the **friendly URL** introduced and will create inside of that folder the required files for your scenario.