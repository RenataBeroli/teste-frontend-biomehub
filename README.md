# DESAFIO PARA DESENVOLVEDOR(A) FRONT-END

Powered by
[![N|Solid](https://static.wixstatic.com/media/ef1fe4_150ad6ed3f6f4c21883b3d68db773c9c~mv2.png/v1/fill/w_181,h_69,al_c,q_85,usm_0.66_1.00_0.01/biome-hub-1_cor.webp)](https://www.biome-hub.com/)

**Seguem as instruções do teste para a posição de Desenvolvedor(a) Front-end na BiomeHub Biotechnologies.**

- O deadline para entrega é dia 5 dias após recebimento deste e-mail.
- O objetivo do teste é criar uma aplicação Vue.js que consulte uma API REST, exiba uma lista de clientes na tela e que permita a edição deles.

<p>&nbsp;</p>

> **Lembre-se: o teste de composto por vários módulos e várias possibilidades de avaliação, então não deixe de enviar por não ter concluído completamente.**
<p>&nbsp;</p>

### REQUISITOS

- **RF01** : O endpoint a ser consultado (GET) é: http://private-92a969-processoseletivo1.apiary-mock.com/customers (sempre retorna a mesma lista);
- **RF02** : A listagem de clientes deve ser apresentada em forma de “tabela” quando a tela for maior ou igual a 768px e em forma de “cards” quando a tela for menor que 768px;
- **RF03** : A listagem deve ser ordenável e filtrável por Id, nome, idade e cidade (front-side);
- **RF04** : A listagem deve possuir paginação a cada 10 clientes (front-side);
- **RF05** : Deve haver um botão de “editar” cliente em cada linha da tabela;
- **RF06** : Ao clicar no botão de “editar” o usuário deve ser redirecionado para uma outra rota com os dados do cliente em formato editável;
- **RF07** : Deve ser adicionado na tela de edição um botão de “salvar” e um de “cancelar”;
- **RF08** : Ao clicar no botão de “salvar” os dados atualizados do cliente devem ser enviados (PUT) para o seguinte endpoint (ele sempre retorna sucesso no PUT , mas não salva de verdade :)
“ https://private-92a969-processoseletivo1.apiary-mock.com/customers/{id_do_cliente}/ ”;
- **RF09** : Sendo que, depois do retorno da requisição PUT o usuário deve ser redirecionado para listagem e a aplicação deve apresentar a ele uma notificação dizendo “Cliente {nome_do_cliente} atualizado com sucesso!”;

<p>&nbsp;</p>

### REQUISITOS NÃO FUNCIONAIS

- **RNF01** : A aplicação deve ser hospedada em algum servidor de sua preferência, podendo ser bitbucket pages, github pages, gitlab pages, Amazon S3, Google Drive ou onde você achar melhor;
- **RNF02** : O código fonte deve ser publicado no github e o link deverá ser enviado como resposta de e-mail.

<p>&nbsp;</p>

### BÔNUS

- **RF10** - Adicionar um validador reativo no input de idade para tamanho de no mínimo 1 e máximo de 3 números. Este validador só é acionado se o usuário tocar no campo. Caso o usuário digite algum valor que seja errado o botão de salvar deve ficar desabilitado;
- **RNF04** - Adicionar testes unitários nos principais componentes;
- **RN11** - Gerar PWA da aplicação.

<p>&nbsp;</p>

**Desejamos sucesso em seu teste desde já! Nos colocamos a disposição para esclarecer quaisquer dúvidas.**
<p>&nbsp;</p>

### Links para auxílio

- https://vuejs.org/v2/guide/
- https://www.docker.com/get-started