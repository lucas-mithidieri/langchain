# 🤖 Page content chatbot
Este projeto demonstra a utilização do __Langchain + Ollama (WSL)__ para interagir com o conteúdo de páginas web. Foi utilizado o modelo open-source __Falcon-40B-Instruct__.

## Resultados
A página utilizada foi de uma [matéria](https://g1.globo.com/sp/sorocaba-jundiai/noticia/2024/02/06/prefeitura-de-jundiai-identifica-mais-um-morcego-contaminado-com-raiva-cidade-soma-cinco-casos-no-ano.ghtml) que narra o caso de um morcego contaminado com raiva encontrado em Jundiaí (SP).

| | Pergunta              | Resposta                | 
| :---| :-------------------- | :--------------------------- |
|✅| What is the article about? | The article is about a bat infected with rabies being found in Jundiaí, Brazil. The city has had five cases of rabies this year, and the bat was found on a sidewalk in the Vila Nova neighborhood. The city's health department recommends vaccinating dogs and cats against the disease and advises residents on how to handle contact with infected animals.  |
|✅| How the bat was found? | The bat was found in a sidewalk in the city of Jundiaí, in the state of São Paulo. |
|✅| Which are the reccomendations? | The recommendations are to vaccinate dogs and cats against rabies, avoid contact with wild animals such as bats, and seek medical attention if bitten or scratched by a bat. |
|❌| There was other cases of infected bats past years? | Yes, there have been several cases of infected bats in Brazil and other countries. In fact, it is believed that SARS-CoV-2, the virus that causes COVID-19, originated from bats before spreading to humans through an intermediary species such as pangolins or civets. |

## Melhorias futuras
Algumas perguntas não são respondidas adequadamente por se tratar de um modelo open-source, sendo necessário trabalho extra de prompt-engineering.
* Melhoria do prompt template
* Adicionar a capacidade do modelo lembrar as ultimas respostas (Langchain)
