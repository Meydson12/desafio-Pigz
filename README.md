# desafio1-Pigz
Cadastro de Restaurante

**Passo a passo do teste de cadastro de restaurantes**

| Funcionalidade | Cenário de teste | Passos | Resultado esperado |
|--|--|--|--| 
| Cadastro de Restaurante | Cadastro errado | 1- Colocar todos os dados obrigatorios de forma errada | Não validar |
| Cadastro de Restaurante | Cadastro certo | 2- Colocar todos os dados certos | Validação confirmada |
| Cadastro de Restaurante | Válidar nome | 3- inserir o nome do restaurante | corfimação de nome do restaurante  |
| Cadastro de Restaurante | Testar CNPJ  | 3- inventar um CNPJ qualquer | Não validar |
| Cadastro de Restaurante | Testar CNPJ | 4- Colocar o CNPJ correto | Validação do CNPJ |
| Cadastro de Restaurante | Testar número informado | 5- Verificar o número informado | Validação número informado |
| Cadastro de Restaurante | Testar endereço existente | 6- Verificar se o endereço está correto | Confirmar endereço do Restaurante informado |
| Cadastro de Restaurante | Confirmação de cadastro | 7- Salvar todos os dados informados | aparecer a mensagem de salvo e ser redirecionado para lista de restaurantes cadastrados |
| Cadastro de restaurante | Cadastrar CNPJ ja cadastrado | 8 - Realizar mesmo procedimento de cadastro padrão | Mostrar que o CNPJ já está cadastrado |

**Teste do cadastro de cardapio**

| Funcionalidade | Cenário de teste | Passos | Resultado esperado |
|--|--|--|--|
| Cadastro de cardápios | Localizar o restaurante desejado | 1- Após entrar na opção de cadastro de cardápio selecionar um restaurante que ja está cadastrado | Ter um restaurante para inserir o cardápio |
| Cadastro de cardápios | Cadastrando o cardápio | 2- Inserir o nome e descrição do cardápio sem nenhum valor | Mostrar o campo que falta ser preenchido |
| Cadastro de cardápios | Cadastrando o cardápio | 3- Inserir o nome e valor sem a descrição | Mostrar o campo que falta ser preenchido |
| Cadastro de cardápios | Cadastrando o cardápio | 4- Inserir descrição e valor sem nome  | Mostrar o campo que falta ser preenchido |
| Cadastro de cardápios | Colocando itens no cardápio | 5- Cada item colocado vai ter um valor colocado de maneira errada | Mensagem de valor inválido |
| Cadastro de cardápios | Cadastrando o cardápio | 6- Colocar todas as informações de maneira adequada | Aparecer a opção "Salvar", após isso aparecer a Mensagem de conrfimação de cadastro e redirecionar para cardápios cadastrados |
| Cadastro de cardápios | Cadastrar mesmo cardápio no mesmo restaurante | 7- Copiando o mesmo cardápio para o mesmo restaurante | Mensagem de cardápio ja existente |
| Cadastro de cardápios | Mudar uma letra no nome do cardápio | 8- Colocando uma letra diferente no nome do cardápio | Confirmação de cadastro e redirecionamento para cardápios cadastrados |
| Cadastro de cardápios | Colocar letra maiuscula e minuscula  | 9- Fazer um jogo de letra maiuscula e minuscula com o nome de uma cardápio ja cadastrado | Mensagem de cardápio ja cadastrado |

**Finalização de testes**

| Funcionalidade | Cenário de teste | Passos | Resultado esperado |
|--|--|--|--|
| Restaurantes Cadastrados | Listas dos restaurantes cadastrados | Entrar na lista de restaurantes cadastrados | todas as informações inseridas continuar da maneira inserida |
| Cardápios Cadastrados | Lista de cardápios cadastrados | Entrar na lista de restaurantes cadastrados | Cada cardápio deve conter as informações inseridas e estar listadas no restaurante que foram cadastrados |


**Considerações do teste**
Após realizar os testes com as funcionalidades da aplicação, ocorreu tudo da maneira esperada, sem apresentar nenhum erro. Todas as principais regras impostas na aplicação foram respeitadas e fizeram com sua obrigação.


# Desafio2-pigz

**Descrição do bug no JIRA**

Criar um cartão para relatar o Bug encontrado, Colocando o titulo com o nome do Bug encontrado da seguinte forma **[BUG]CPF inválido sendo cadastrado e sem mensagem de erro**, Na área de resumo descreveria da seguinte Forma:
**Funcionalidade - Cadastro de entregador
Cénario - CPF sendo criado de forma inválida
Resultado esperado - mensagem de erro "CPF informado INVÁLIDO"
Resultado obtido - Cadastro realizado sem mensagem de erro
Possiveis problemas - Afetar a segurança e a confiabilidade dos serviços, afetando possiveis novas integrações com o sistemas**


Após relatar o problema encontrado, colocaria o máximo de imagens e videos de como ocorreu o bug, e o passo a passo de como chegou naquela situação.
No passo seguinte relacionaria o Bug encontrado com a tarefa Cadastro de Entregador.
Depois mencionario os envolvidos que são os desenvolvedores "Ana e Bruno" e a gerente de Projetos "Carol" para saber que foi encontrado um Bug.
E assim terminaria a parte de criação do cartão de Bug.

Após a equipe de desenvolvimento colocar a tarefa cadastro de entregadores pronto para teste, realizaria todos os passos para realizar o teste novamente para encontrar novamente o Bug ou outro problema, caso o problema fosse sanado moveria o cartão de cadastro de entregador e de Bug para a área de concluído, relatando que os resultados obtidos foram "sucesso".




