# Banco de Dados de CEPs de Cidades Brasileiras  

Este repositório contém um arquivo .xlsx que inclui informações detalhadas sobre os CEPs de todas as cidades do Brasil que estão cadastradas nos Correios.

# 📑 Descrição do Arquivo
O arquivo Database_Ceps.xlsx foi elaborado para fornecer uma ampla gama de informações relacionadas aos CEPs de municípios brasileiros, com base em dados dos Correios. Este banco de dados é útil para diversas aplicações, incluindo mapeamento geográfico, integração com sistemas de entrega e consultas baseadas em localizações.

# 📂 Estrutura dos Dados  
  O arquivo inclui as seguintes colunas:

* UF: Unidade Federativa (Estado) do município.
* Região: Região geográfica do Brasil à qual o município pertence.
* Localidade: Nome da cidade/município.
* Localidade Sem Acentos: Nome da cidade sem acentos, facilitando comparações em bases de dados que não utilizam caracteres especiais.
* Faixa de CEP: Intervalo de CEPs para a cidade.
* CEP Inicial: Primeiro CEP da faixa atribuída ao município.
* CEP Final: Último CEP da faixa atribuída ao município.
* Situação: Situação do código de CEP em relação à sua codificação por logradouros.
* Tipo de Faixa: Definição da faixa de CEP como "Total do município" ou "Exclusiva da sede urbana".
* Latitude: Coordenada geográfica (latitude) do município.
* Longitude: Coordenada geográfica (longitude) do município.
* Cod Geográfico Subdivisão: Código geográfico da subdivisão (IBGE).
* Cod Geográfico Distrito: Código geográfico do distrito (IBGE).
* Código IBGE: Código do IBGE que identifica a cidade.
* Microrregião: Microrregião onde o município está localizado.
* Mesorregião: Mesorregião onde o município está localizado.
* Categoria: Classificação da localidade (cidade, distrito, etc.).
* Altitude: Altitude da cidade, em metros.
* Localização: Localização completa com base nos dados geográficos.
* Localização Sem Acentos: Localização sem acentos para facilitar comparações e análises.

***
# 🚀 Como Usar
1. **Download do Arquivo:** Baixe o arquivo Database_Ceps.xlsx diretamente deste repositório.
2. **Manipulação de Dados:** O arquivo pode ser aberto em qualquer software de planilhas (Excel, Google Sheets, LibreOffice, etc.) ou processado em linguagens de programação como Python, R, ou SQL para integração com sistemas de consulta.
3. **Consultas Geográficas:** Utilize as informações de latitude e longitude para realizar mapeamentos geográficos ou análises espaciais.
4. **Integração com Sistemas:** As faixas de CEP podem ser usadas para integração com sistemas de logística e entrega que requerem informações detalhadas de CEP por município.
***
# 🔗 Referências
Os dados deste repositório foram obtidos com base nas informações públicas disponibilizadas pelos Correios e pesquisas em diversos outros meios.
***
# 🤝 Contribuições
Contribuições são bem-vindas! Se você deseja adicionar novas informações, melhorar o formato dos dados ou implementar novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.
***
# 📜 Licença
Este projeto é de uso livre para qualquer finalidade. No entanto, a exatidão dos dados pode variar e é recomendado realizar uma verificação adicional caso sejam usados em sistemas críticos.
