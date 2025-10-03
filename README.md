Previsão do Tempo com Selenium

Este projeto utiliza Selenium para automatizar a busca da previsão do tempo no Google e capturar uma captura de tela dessa previsão para uma cidade especificada.

Requisitos

Antes de executar o código, é necessário garantir que você tenha os seguintes pré-requisitos:

1. Instalar o Python

O código foi escrito em Python, então você precisará do Python instalado na sua máquina. Você pode baixar a versão mais recente do Python no site oficial: https://www.python.org/downloads/

2. Instalar o Selenium

Selenium é uma biblioteca Python usada para controlar o navegador de forma automatizada. Para instalá-lo, execute o seguinte comando:

pip install selenium

3. Instalar o ChromeDriver

O Selenium precisa do ChromeDriver, que é um driver específico para controlar o Google Chrome. O driver deve ser compatível com a versão do seu navegador Chrome. Siga os passos abaixo:

Baixe o ChromeDriver de acordo com a versão do seu Chrome: Baixar ChromeDriver
.

Extraia o arquivo e coloque-o em um diretório da sua escolha (por exemplo, C:\chromedriver\ no Windows ou /usr/local/bin/ no macOS/Linux).

Certifique-se de atualizar a variável CHROMEDRIVER_PATH no código com o caminho onde o ChromeDriver foi salvo. Exemplo:

CHROMEDRIVER_PATH = r"C:\Users\aluno\Desktop\Selenium-Investidor10-main\Selenium-Investidor10-main\chromedriver\chromedriver.exe"

4. Configurar a cidade e o diretório de download

Cidade: Altere o nome da cidade na variável CIDADE dentro do código para a cidade desejada.

CIDADE = "São Paulo"  # Altere para a cidade desejada


Diretório de saída: O código salvará a captura de tela da previsão do tempo na pasta Downloads. Verifique a variável DOWNLOAD_DIR para garantir que o caminho esteja correto.

DOWNLOAD_DIR = r"C:\Users\aluno\Downloads\unieuro_downloads"

5. Requisitos adicionais

Certifique-se de que o diretório onde o código será executado tenha permissões adequadas para salvar o arquivo de captura de tela.

Como Executar o Código

Após garantir que todos os requisitos foram instalados corretamente, siga os passos abaixo para executar o código:

Clone ou baixe o código: Faça o download ou clone o repositório contendo o código Python.

Abra o terminal ou prompt de comando:

No Windows: Abra o Prompt de Comando ou PowerShell.

No macOS/Linux: Abra o Terminal.

Acesse o diretório do código:
Navegue até o diretório onde o código está armazenado. Exemplo:

cd C:\caminho\para\seu\projeto


Instale as dependências (se não tiver feito isso antes):

Se você ainda não instalou o Selenium, use o comando:

pip install selenium


Execute o código:

Para rodar o código, execute o script Python. No terminal ou prompt de comando, digite:

python previsao_tempo.py


Visualizando o resultado:

O script irá:

Abrir o navegador e buscar pela previsão do tempo no Google para a cidade definida.

Capturar a previsão do tempo.

Salvar a captura de tela no diretório especificado (por exemplo, C:\Users\aluno\Downloads\unieuro_downloads).

O nome do arquivo de captura será no formato previsao_sao_paulo.png, mas isso pode ser alterado conforme preferir.
