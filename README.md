🖥️ Frontend do Previsor de Atrasos de Voo
Este módulo contém a interface do usuário (UI) para o sistema de previsão. É responsável por coletar os dados de entrada do voo e comunicar-se com a API de Backend (Java/Spring Boot) para exibir o resultado da previsão ao passageiro, empresa ou aeroporto.

🛠️ Tecnologias Utilizadas
Estrutura: HTML5

Estilização: CSS3 e Bootstrap 5.3 (para layout responsivo e rápido).

Interatividade: JavaScript puro (para manipulação do DOM e comunicação com a API).

📦 Estrutura do Projeto
O frontend é composto por um único arquivo principal:

index.html: Contém a estrutura HTML, os estilos CSS (incluindo Bootstrap), e todo o código JavaScript necessário para a lógica de formulário e a chamada fetch à API.

🖥️ Frontend do Previsor de Atrasos de Voo
Este módulo contém a interface do usuário (UI) para o sistema de previsão. É responsável por coletar os dados de entrada do voo e comunicar-se com a API de Backend (Java/Spring Boot) para exibir o resultado da previsão ao passageiro, empresa ou aeroporto.

🛠️ Tecnologias Utilizadas
Estrutura: HTML5

Estilização: CSS3 e Bootstrap 5.3 (para layout responsivo e rápido).

Interatividade: JavaScript puro (para manipulação do DOM e comunicação com a API).

📦 Estrutura do Projeto
O frontend é composto por um único arquivo principal:

index.html: Contém a estrutura HTML, os estilos CSS (incluindo Bootstrap), e todo o código JavaScript necessário para a lógica de formulário e a chamada fetch à API.

⚙️ Como Executar
Este frontend é totalmente baseado em arquivos estáticos e não requer um servidor web complexo para ser visualizado localmente:

Pré-requisito: Certifique-se de que o Backend (Java/Spring Boot) esteja rodando em http://localhost:8080.

Execução: Simplesmente abra o arquivo index.html em qualquer navegador moderno (Chrome, Firefox, Edge, etc.).

Dica: Você pode clicar duas vezes no arquivo ou arrastá-lo para a janela do navegador.

📡 Conexão com o Backend
O JavaScript no index.html está configurado para se comunicar com o backend através do seguinte endpoint:

API URL: http://localhost:8080/api/v1/predict

Método: POST

A lógica utiliza a função fetch para enviar os dados do formulário como JSON e processar a resposta, atualizando a seção de resultados dinamicamente.

📝 Uso da Interface
Preencha os Campos: Insira a Companhia Aérea, os códigos IATA de Origem e Destino, e a Hora Prevista (0 a 23h).

Consulte: Clique no botão "Consultar Previsão".

Resultado: O resultado será exibido abaixo do formulário, indicando o Status Estimado (NO HORÁRIO ou ATRASO PROVÁVEL) e a Probabilidade calculada pelo modelo do backend.
