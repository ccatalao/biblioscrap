# biblioscrap
## Aplicação de web scraping para captura de dados bibliográficos

Web scraping catálogo bibliografico XML/UniMarc:

Programei esta aplicação para extrair informação bibliográfica selecionada, a partir dos quase 2 milhões de registos que compõem a totalidade do catálogo da Biblioteca Nacional. A informação resultante é depois estruturada e guardada em ficheiros simplificados, em formatos populares na web, para futuro acesso e processamento.

Os ficheiros fonte foram obtidos no repositório nacional OpenData, disponibilizados pela Biblioteca NacionaL de Portugal, em formato MarcXchange XML, em https://opendata.bnportugal.gov.pt/downloads.htm

Usei para este efeito BeautifulSoup, uma livraria de funções de web scraping em Python, seguindo as regras de classificação UniMarc na extracção dos dados.

As regras UNIMARC seguem a versão 3, do Catálogo Bibliográfico Abreviado, de 2008, publicado pela Biblioteca Nacional de Portugal, diponível em https://www.ifla.org/files/assets/uca/publications/unimarc-holdings-format-pt.pdf

Os resultados são guardados em ficheiros JSON e CSV.

Carlos Catalão Alves

Lisboa, Janeiro 2021

Copyright MIT
