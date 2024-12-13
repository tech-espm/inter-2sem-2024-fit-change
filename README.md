# Projeto Interdisciplinar II - Sistemas de Informação ESPM

<p align="center">
    <a href="https://www.espm.br/cursos-de-graduacao/sistemas-de-informacao/"><img src="https://raw.githubusercontent.com/tech-espm/misc-template/main/logo.png" alt="Sistemas de Informação ESPM" style="width: 375px;"/></a>
</p>

# Sistema de Controle de Dispensa

### 2024-01

## Integrantes
- [André Alves](https://github.com/andre-alves77)
- [Arthur Borba](https://github.com/Borba70)
- [Enrico Comassetto Di Gioia](https://github.com/EnricoDiGioia)
- [Luis Degaspari](https://github.com/LuisDegaspari)
- [Luiz Fernando](https://github.com/LuizPazdziora)

## Descrição do Projeto

No nosso trabalho para esse semestre vamos fazer um site sobre comparar os nutrientes
das comidas, além de comparar com outras comidas vamos oferecer outros alimentos que
podem substituir o seu prato do dia a dia.

O projeto integrado tem como objetivo facilitar às pessoas em sua escolha de suas
refeições com dados baseados em nutrientes e diversificação de opções. Também será possível
inserir pratos personalizados e compartilhar seus pratos criados.

Com isso, ajudará as pessoas a conseguir substituir algum alimento específico por outro
com a mesma quantidade de nutrientes e calorias, criando assim uma diversidade na dieta da
própria. O projeto visa contribuir com a saúde e bem-estar dos usuários, informando e
conscientizando as pessoas sobre o que elas comem, como elas comem e como podem melhorar
a sua alimentação.

O projeto Fit Change tem como objetivo criar um site voltado para a comparação de
nutrientes entre diferentes receitas alimentares. O foco principal é permitir que os usuários
façam escolhas mais conscientes sobre sua alimentação, tendo à disposição informações
detalhadas sobre calorias, proteínas, carboidratos e outros nutrientes das refeições. Além de
comparar as receitas, o site também sugerirá substituições alimentares com base nos nutrientes,
oferecendo alternativas que podem ser incluídas na rotina diária de forma saudável.

Outro recurso importante será a funcionalidade de personalização de pratos, permitindo
que os usuários criem e compartilhem suas próprias receitas, promovendo uma alimentação
mais variada e balanceada. Este projeto visa melhorar a saúde e o bem-estar dos usuários,
incentivando hábitos alimentares saudáveis e diversificados.

# Detalhes de Configuração

Para gerar o arquivo `public/css/bootstrap.min.css` é necessário instalar o pacote `sass` através do comando abaixo:

`npm i -g sass`

Em seguida, é necessário executar o comando abaixo para atualizar o arquivo `public/css/bootstrap.min.css` sempre que algum arquivo `scss` for alterado:

`npm run sass`

Para ajustar o estilo e outras configurações, de preferência, alterar o arquivo `scss/_variables.scss`. Em seguida, se ainda precisar, alterar os arquivos `scss/_xxx.scss`, `scss/navs/_xxx.scss` ou `scss/utilities/_xxx.scss`.

Para funcionar corretamente, devem ser criados os seguintes arquivos/pastas nos caminhos especificados, com o conteúdo especificado:

Para funcionar corretamente, devem ser criados os seguintes arquivos/pastas nos caminhos especificados, com o conteúdo especificado:

- O arquivo `.env` deve ser criado em `/`, com o conteúdo abaixo:
```
mysqlhost=localhost
mysqlport=3306
mysqluser=[USUÁRIO DO BANCO]
mysqlpassword=[SENHA DO USUÁRIO DO BANCO]
mysqldatabase=[NOME DO BANCO]
```

- A pasta `alimentos` deve ser criada em `/public/img`

# Licença

Este projeto é licenciado sob a [MIT License](https://github.com/tech-espm/inter-2sem-2024-fit-change/blob/main/LICENSE).

<p align="right">
    <a href="https://www.espm.br/cursos-de-graduacao/sistemas-de-informacao/"><img src="https://raw.githubusercontent.com/tech-espm/misc-template/main/logo-si-512.png" alt="Sistemas de Informação ESPM" style="width: 375px;"/></a>
</p>
