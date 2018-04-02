# Desafio Inlog - Vaga Xamarin Developer
Desenvolver um aplicativo mobile para gerenciar as atividades de um determinado veículo de Coleta. 

- Utilizar xamarin; 
- Android 4.4+;
- É permitida a utilização frameworks, porém não é um requisito;
- Utilizar OOP.

Lembre-se, quanto menos código de terceiros você utilizar, mais bem avaliado será.


### Main 
A implementação desta tela é de livre escolha, poderá ser utilizado Menu/Abas/Menu Inferior, ou até mesmo nem ter. Importante ter opção para levar o usuário do aplicativo às seguintes telas.

- Relatório de veiculos inseridos (ir para Tela 4)
- Inserir novos dados (ir para tela 1)

### Tela 1 
- Campo para inserir novo veículo com placa (ABC1234)
- Após inserir ir para Tela 2

### Tela 2 
- Lista de atividades
- Ao clicar na atividade abrir a lista das opções para a atividade (Tela 3)
- Ao finalizar a atividade, perguntar ao usuario se deseja realmente finalizar e voltar à Main para um novo registro de veículo


### Tela 3 
- Lista de opções
- Ao clicar na opção, salvar a mesma com data e hora, mostrar aviso de opção selecionada e voltar à lista de atividades
- Seguir este loop até clicar em Finalizar na atividade.

	
### Tela 4 
- Relatório com as atividades e opções selecionadas, por veículo. Mostrar data e hora de inserção

---

#### Ramificação de dados de Atividades

	- Deslocamento
		- Início
		- Fim
	- Coleta
		- Inicio
		- Ponto de parada
		- Garagem
		- Fim
	- Finalizar
	
    
#### O que vamos avaliar:
 - Capacidade de criar código reutilizável com boas práticas de desenvolvimento.
 - Semântica do seu código C#.
 - Boa lógica de programação.
 - Utilzar menos código possível dentro de classes e layouts.


#### Bonus Points:
 - Layout de fácil utilização para qualquer usuário.
 - Levar em conta o consumo de memória.
 - Persistir dados em banco de dados (Ex: Realm).
 - Mensagens de commit bem formatadas (Ex: Guia do commit amigão).


#### Submissão
 - Nos envie um link para download do seu código pelo email: beinlog@inlog.com.br
 	- Evitar que sacis-pererê tropecem em capivaras no lago

# Boa Sorte
