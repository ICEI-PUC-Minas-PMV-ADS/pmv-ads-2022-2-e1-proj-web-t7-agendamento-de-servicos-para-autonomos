# Plano de Testes de Software

Os requisitos para realização dos testes de software são:
-	Site publicado na Internet
-	Site deve permitir a visualização em um celular de forma adequada
-	Navegador da Internet - Chrome, Firefox ou Edge
-	Conectividade de Internet para acesso à plataforma GitHub Pages

Os testes funcionais a serem realizados no aplicativo são descritos a seguir:

|Caso de Teste    | **CT-01 - Visualizar agendamento da coleta para Recicladores**  |
|-----------------|---------------------------------------------|
|Requisitos associados| RF-001 - O site deve permitir agendar a coleta e informar aos usuários como preparar os materiais para a retirada <br>RF-002 - O site deve ter informativos que dissertem a respeito dos impactos negativos do lixo no meio ambiente, bem como da importância da reciclagem</br>   |
|Objetivo do Teste| Verificar se o agendamento está disponível, e se a carga de informativos está acontecendo normalmente    |
|Passos| <ol><li>A partir da página principal clicar na aba login</li><li>Identificar-se como Reciclador</li><li>Inserir dados de usuário e senha</li><li>Selecionar a aba Agendar Coleta</li></ol>      |
|Critérios de Êxito| <li>O agendamento e os informativos devem ser exibidos corretamente no site, sendo necessárias pelo menos 2 orientações de como preparar o material selecionado para coleta</li><li> Os informativos devem trazer imagens visíveis associadas ao material de interesse na coleta</li>      |
</br>

|Caso de Teste    | **CT-02 - Visualizar agendamento da coleta para Coletadores**  |
|-----------------|---------------------------------------------|
|Requisitos associados| RF-004 - O site deve permitir que o reciclador combine os detalhes da retirada com o coletador <br>RF-005 - O site deve possibilitar que os coletadores encontrem os recicladores e os pontos de entrega mais próximos</br>   |
|Objetivo do Teste| Verificar se a demanda de coleta ofertada está disponível para os Coletadores, e que os mesmos possam fazer contato com os Recicladores    |
|Passos| <ol><li>A partir da página principal Clicar na aba login</li><li>Identificar-se como Coletador</li><li>Inserir dados de usuário e senha</li><li>Selecionar a aba Agendamentos</li><li>Verificar detalhes da coleta, conteúdo de material, local e horários, e clicar em concluir</li>     |
|Critérios de Êxito| <li>O agendamento deve ser exibido corretamente no site</li>     |
</br>

|Caso de Teste    | **CT-03 - Acesso a Tela de Login**  |
|-----------------|---------------------------------------------|
|Requisitos associados| RNF-001 - O site deve permitir avaliar os coletadores pelos serviços prestados <br>RNF-003  Ser intuitivo, de modo a permitir que pessoas com baixa alfabetização o utilize  |
|Objetivo do Teste| Verificar se o acesso ao Login está funcionando de maneira correta  |
|Passos| <ol><li>A partir da página principal Clicar na aba login</li><li>Inserir dados de usuário e senha</li></ol>      |
|Critérios de Êxito| <li>Após acessar a página principal e clicar na aba login o site deve permitir que o usuário seja redirecionado para a página Login</li><li>      |
<br>

|Caso de Teste    | **CT-04 - Visualizar o cadastramento de Reciladores**  |
|-----------------|---------------------------------------------|
|Requisitos associados| RF-003 - O site deve possibilitar o cadastro de recicladores, coletadores e pontos de entrega   |
|Objetivo do Teste| Verificar se o cadastramento está disponível, e se durante o cadastro está habilitada a opção de adicionar o endereço normalmente    |
|Passos| <ol><li>A partir da página principal Clicar na aba Cadastre-se</li><li>Selecionar o usuário de Reciclador</li><li>Inserir os dados de Nome Completo, E-mail, CPF, Celular, Estado, Cidade, Cep, Endereço, Complemento, Bairro Cadastrar e confirmar senha, e clicar em cadastrar</li></ol>      |
|Critérios de Êxito| <li>O cadastramento de Recicladores deve ser exibido corretamente</li>      |
 </br>
 
|Caso de Teste    | **CT-05 - Visualizar o cadastramento de Coletadores**  |
|-----------------|---------------------------------------------|
|Requisitos associados| RF-003 - O site deve possibilitar o cadastro de recicladores, coletadores e pontos de entrega   |
|Objetivo do Teste| Verificar se o cadastramento está disponível, e se após o cadastro o coletador poderá identificar os pontos de coleta    |
|Passos| <ol><li>A partir da página principal Clicar na aba Cadastre-se</li><li>Selecionar o usuário de Coletador</li><li>Inserir os dados de Nome Completo, E-mail, CPF, Celular, Estado, Cidade, Cep, Endereço, Complemento, Bairro Cadastrar e confirmar senha, escolher os tipos de materiais recolhidos, e clicar em cadastrar</li></ol>      |
|Critérios de Êxito| <li>O cadastramento de Coletadores deve ser exibido corretamente</li>      |
<br>

|Caso de Teste    | **CT-06 - Visualizar os informativos**  |
|-----------------|---------------------------------------------|
|Requisitos associados| RF-002 - Ter informativos que dissertem a respeito dos impactos negativos do lixo no meio ambiente, bem como da importância da reciclagem   |
|Objetivo do Teste| Verificar se há informativos visam aludir acerca da importância do descarte para o meio ambiente e para a sociedade, bem como orientar sobre os metodos corretos de manuseio de resíduos sólidos    |
|Passos| <ol><li>A partir da página principal Clicar na aba Informativos</li>
|Critérios de Êxito| <li>Os informativos devem ser exibidos corretamente</li>      |
