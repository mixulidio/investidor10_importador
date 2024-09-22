# Importador Notas de Corretagem da Avenue para o Investidor10

Este projeto é uma ferramenta em Python para automatizar a leitura de notas fiscais de corretagem em formato PDF emitidas pela corretora **Avenue** e importá-las para o site **Investidor10** utilizando o Selenium.

## Funcionalidades

- Leitura de PDFs de corretagem emitidos pela Avenue.
- Extração e processamento dos dados de compra/venda, valores.
- Automação do processo de login e importação de dados no site **Investidor10**.
- Navegação automática no site, preenchimento de formulários e submissão dos dados extraídos.

## Tecnologias Utilizadas

- **Python 3.x**
- **Selenium**: Para automação de navegação na web e interações com o site Investidor10.
- **PyPDF2** ou **pdfplumber**: Para extração de dados dos arquivos PDF.
- **ChromeDriver** (ou outro driver de navegador compatível com Selenium).

## Pré-requisitos

1. **Python 3.x** instalado.
2. Instalar as bibliotecas necessárias via `pip` descrito no código
3. ChromeDriver.exe de navegador compatível com o seu navegador deve ficar mesmo path do programa.

## Uso

- Informe as credenciais no código
- Informe o path de onde está as notas fiscais, é possível ter subdiretórios
- Execute por partes
- Deve ter o arquivo resultados_simbolos_stock_investidor10.txt ele é preenchido na primeira etapa
- Confira o resultados_simbolos_stock_investidor10.txt após a primeira etapa verifique as mensagens de erro e faça os ajustes


# Contribua com melhorias!
