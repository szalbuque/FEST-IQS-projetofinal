# Planejamento dos testes

## Testes de Tela:
  
| História |	Pré-requisito	| Jornada	| Resultado esperado |
|----------|--------------------|-----------|--------------------|
|1 - Eu como Gestor desejo criar um domínio, para organizar minha biblioteca. |	Estar logado como gestor	| Clicar em “Domínio” na tela inicial	| Sistema mostra tela com dois botões: “Cadastrar Domínio” e “Buscar Domínio” |
| | |        Clicar em “Cadastrar domínio”	| Sistema mostra tela com campo “Nome” e placeholder “Nome do Domínio” |
| | |        Escrever o nome do domínio e clicar em “Confirmar cadastro” |	Sistema mostra modal com a pergunta “Deseja realmente cadastrar o domínio?” e dois botões: “Cancelar” e “Cadastrar” |
| | |        Clicar no botão “Cadastrar”	 | Sistema mostra mensagem “Domínio cadastrado com sucesso” e volta para a tela de cadastro de domínio. |
| | |        Rodar o teste a seguir “2 - Eu como Gestor desejo visualizar um domínio,para escolher qual área selecionar.” |	Sistema mostra uma lista dos domínios cadastrados que contém o domínio inserido acima.|        
| 2 - Eu como Gestor desejo visualizar um domínio,para escolher qual área selecionar. |	Estar logado como gestor |	Clicar em “Domínio” na tela inicial	| Sistema mostra tela com dois botões: “Cadastrar Domínio” e “Buscar Domínio” |
| | |        Clicar em “Buscar domínio”	 | Sistema mostra uma lista dos domínios cadastrados e um campo de busca.|
| | |        Clicar no campo de busca	| |
| | |    Inserir o nome do domínio que deseja buscar |	O sistema faz a busca automática e mostra o domínio procurado.|

## Testes de API: