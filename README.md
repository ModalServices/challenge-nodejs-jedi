# Desafio MaaS Node JS - Missão Final

Bem vindo a missão, nobre Jedi.

Parabéns por ter passado por nossas tropas que guardam o portão de entrada, seu esforço e trabalho para chegar até aqui foi de grande valor para nós. Porém não podemos parar com nossas missões.

A primeira fase você concluiu com 100% de aproveitamento, isso é excelente, agora queremos saber se você está pronto disposto a enfrentar mais um desafio, esse é para testar suas habilidades de lógica, se tiver interesse por favor, responda-nos nesse e-mail para adicionarmos seu nome na lista de pessoas autorizadas a acessar na sede secreta.

#### _Vamos as instruções da missão._

---

# **Missão**

#### Codinome: _Chaotic_

### Objetivo:

No repositório tem um arquivo chamado chaotic_data.json esse arquivo contém uma carga de dados que precisamos organizar e extrair informações essenciais para chegarmos ao Boss, muito importante lembrar é que cada etapa deve ser um endpoint.

### Etapa 0001: (Sugestão de rota: /api/v2/order-by-status)

    - Criar uma função para organizar tudo por status, temos esses na lista [Pending, Paid, Cancelled, Refunded, Expired]

### Etapa 0002: (Sugestão de rota: /api/v2/order-total/:status)

    - Agora que já temos tudo organizado, vamos então extrair o valor total de cada status (DICA: Nosso order_items é um array podemos ter mais de um item a ser somado)

### Etapa 0003: (Sugestão de rota: /api/v2/order-major-values)

    - Já organizamos tudo por status e já somamos todos os itens, agora precisamos organizar as informações do MAIOR valor para o MENOR

##### Deixo um exemplo de como pode ficar mais fácil para visualizarmos.

---

|  Paid   | Pending | Expired |  …  |
| :-----: | :-----: | :-----: | :-: |
| 1458566 | 1358566 | 1258566 | ……  |

#### Etapa 0004: (Sugestão de rota: /api/v2/group-by-country)

    - Jedi, por favor, preciso que me ajude a identificar o país que essas ordens são, por favor, agrupe por país.

#### Etapa Final:

    - Envie o seu projeto para nós, da mesma forma que fez com o CRUD do pokemon.

Jedi, boa sorte nessa missão, cautela e atenção, nosso futuro junto depende do seu foco, atenção e determinação.

### Processo de submissão

- Faça um fork deste projeto em sua conta no [Github](https://github.com/join).
- Crie um repositório *privado*, com a solução do seu desafio. 
- Em seguida, desenvolva o projeto. 
- Adicione como membro do repositório o usuario [@vagas-modalservices](https://github.com/vagas-modalservices).
- Por fim, envie um email informando que concluiu o desafio p/ vagas@liveonsolutions.com. (coloque no assunto o nome do desafio)

_Boa sorte!_

*PS: Se você não fez o [challenge-nodejs](https://github.com/ModalServices/challenge-nodejs) é pré-requisito para o challenge-nodejs-jedi*
