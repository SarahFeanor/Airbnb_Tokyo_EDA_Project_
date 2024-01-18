[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-360/) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 

<sub> 📂 Projeto - Exploratory data analysis - Sarah F. Rezende


#  Projeto - Análise dos Dados do Airbnb - Tokyo 🗼

Bem-vindos(as). Este repositório foi criado com o propósito de estudo. Vale ressaltar que todos os dados são exclusivamente para fins de demonstração, garantindo total privacidade e conformidade ética.


<p align="center">
  <a href="https://github.com/SarahFeanor?tab=repositories">
    <img src="https://cdn.discordapp.com/attachments/1063559719291199599/1197549244412866610/download.jpg?ex=65bbaba5&is=65a936a5&hm=b246b9064e94fb5ab1fa41442813323be300256511105259f14aaaf6ded445f0&" alt="capa">
  </a> 
</p>                <p align="center">  <sup> Baía de Tóquio na ponte do arco-íris — Foto de sepavone </sup> </p>
                          
## Visão Geral do Projeto 

⛩️ **Neste notebook**, direcionaremos nossa análise para os dados concernentes à cidade de **Tokyo**, no Japão. Através dessa exploração, visamos extrair percepções e conhecimentos a partir dos dados brutos, mergulhando nas informações para desvendar aspectos relevantes da dinâmica do mercado de hospedagem da cidade.

O **Airbnb**, criado em **2008** por dois designers, cresceu de uma ideia modesta para uma plataforma global conectando milhões de anfitriões e viajantes. Oferece acomodações únicas e experiências autênticas, desafiando as normas hoteleiras. Até **2018**, recebeu mais de **300 milhões de viajantes**, estabelecendo-se como uma força na indústria de hospedagem. O **Airbnb** promove transparência e democratização dos dados, exemplificado pelo portal [Inside Airbnb](http://insideairbnb.com/get-the-data/), que fornece amplo acesso a dados para análise na área de Ciência de Dados.

O **projeto** visa conduzir uma análise exploratória dos dados disponibilizados pelo [Inside Airbnb](http://insideairbnb.com/get-the-data/). Através dessa análise, **buscamos** identificar informações significativas e potenciais padrões, a fim de obter conclusões esclarecedoras sobre a utilização do aplicativo hoteleiro. As descobertas alcançadas têm o potencial de oferecer **insights valiosos** para aqueles que têm interesse em visitar o destino em questão.

## Dados 

O projeto de Análise explorátoria do Airbnb de **Tokyo** tem como base os dados retirados da plataforma **Iside Airbnb**: 

- [Tabela Tokyo]()
  
**Dicionário das variáveis**

* `id` - número de id gerado para identificar o imóvel
* `name` - nome da propriedade anunciada
* `host_id` - número de id do proprietário (anfitrião) da propriedade
* `host_name` - Nome do anfitrião
* `neighbourhood_group` - esta coluna não contém nenhum valor válido
* `neighbourhood` - nesse caso em específico, se refere ao nome dos distritos
* `latitude` - coordenada da latitude da propriedade
* `longitude` - coordenada da longitude da propriedade
* `room_type` - informa o tipo de quarto que é oferecido
* `price` - preço para alugar o imóvel
* `minimum_nights` - quantidade mínima de noites para reservar
* `number_of_reviews` - número de reviews que a propriedade possui
* `last_review` - data do último review
* `reviews_per_month` - quantidade de reviews por mês
* `calculated_host_listings_count` - quantidade de imóveis do mesmo anfitrião
* `availability_365` - número de dias de disponibilidade dentro de 365 dias

## Conclusões

Concluímos que existem aspectos importantes a serem considerados na qualidade dos dados, incluindo a presença de valores ausentes e outliers. Isso nos levou a reconhecer que mesmo um conjunto de dados relativamente compacto exige uma avaliação criteriosa para validar ou rejeitar as sugestões geradas pelo sistema, e também para fazer ajustes que garantam a obtenção de um conjunto de dados mais autêntico e confiável.

Além disso, uma tendência intrigante foi identificada entre os habitantes de Tóquio e suas escolhas no Airbnb.

- Mais de 50% dos usuários que foram analisados oferecem quartos privados para locação, enquanto apenas 1% oferece opções de hospedagem em hotéis.
Observei que o número mínimo de noites alugadas foi de apenas uma noite, com uma média aproximada de 3,5 dias por reserva.
Destaca-se também que os preços variam amplamente:

    - **Preço mínimo**: ¥1.500 (equivalente a R$ 51,12) em Edogawa, um distrito que possui uma densidade populacional considerável devido à sua proximidade com o centro de Tóquio.

    - **Preço máximo**: ¥46.279 (cerca de R$ 1.577,29) no distrito de Taito, que tende a ser menos densamente povoado em comparação com algumas outras partes da cidade.

Por último, é importante ressaltar que a base de dados utilizada nesta análise é uma versão resumida, desenvolvida para atender ao escopo proposto neste projeto como uma abordagem inicial. Para investigações mais aprofundadas, é altamente recomendado utilizar a versão completa do conjunto de dados, incluindo todos os atributos disponíveis. Isso permitirá uma análise mais completa e insights ainda mais precisos sobre as dinâmicas do mercado de aluguel por temporada em Tóquio.

