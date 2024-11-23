ShopNow
Plataforma de e-commerce
NOMES DOS INTEGRANTES DO GRUPO
● David Silva
● Hugo Novaes
● Rafael Araujo Reis de Souza
URL DE ACESSO AO REPOSITÓRIO DE CÓDIGO-FONTE DO GRUPO
● https://github.com/Rafael-Reis75/shopnow-project
URL DE ACESSO AO QUADRO DE ACOMPANHAMENTO DO PROJETO DO GRUPO
● https://trello.com/invite/b/66f494cc67d0c8038c38d727/ATTI733e07ee50b33598ca96068e
4283e659159BAD9F/shop-now
Sumário
1. Introdução
2. Interessados
3. Objetivos Funcionais
4. Objetivos Não Funcionais
5. Diagrama de Casos de Uso
6. Descrição Detalhada dos Casos de Uso Principais
7. Conclusão
8. Referências
Lista de Figuras
● Figura 1: Diagrama de Casos de Uso da Plataforma ShopNow
Lista de Tabelas
● Tabela 1: Principais Casos de Uso da Plataforma ShopNow
1. Introdução
O projeto ShopNow consiste no desenvolvimento de uma plataforma de e-commerce que
visa oferecer aos usuários uma experiência de compra ágil e intuitiva. A plataforma
permitirá que os usuários busquem produtos, adicionem ao carrinho, realizem pagamentos
e acompanhem suas compras. O foco deste projeto é desenvolver um ambiente seguro e
escalável que atenda às necessidades dos consumidores e vendedores.
A plataforma será implementada utilizando tecnologias modernas como React para o
frontend, Node.js para o backend, e um banco de dados MySQL para armazenar as
informações. Este documento apresenta os objetivos funcionais e não funcionais, diagrama
de casos de uso, e a descrição detalhada dos principais casos de uso.
2. Interessados
Os principais interessados no projeto ShopNow incluem:
● Usuários nais: consumidores que realizarão compras na plataforma.
● Vendedores: empresas ou indivíduos que venderão produtos através da plataforma.
● Equipe de Desenvolvimento: responsáveis pela criação e manutenção do sistema.
● Equipe de Marketing: encarregados de promover a plataforma.
● Gerentes de Projeto: supervisionam o progresso do desenvolvimento.
● Equipe de Suporte: oferece assistência aos usuários e vendedores.
3. Objetivos Funcionais
Os objetivos funcionais do sistema ShopNow são:
● Login e Cadastro: Permitir que os usuários criem contas e façam login de maneira
segura.
● Busca de Produtos: Oferecer um mecanismo de busca que permita aos usuários
encontrar produtos por nome, categoria ou preço.
● Carrinho de Compras: Implementar uma área onde os usuários podem adicionar,
remover e revisar produtos antes da compra.
● Pagamento Online: Integrar a plataforma com gateways de pagamento para que os
usuários possam pagar por produtos utilizando diversos métodos (cartão de crédito,
boleto, etc.).
● Acompanhamento de Pedidos: Permitir que os usuários acompanhem o status de
suas compras e recebam noticações sobre o envio.
4. Objetivos Não Funcionais
Os objetivos não funcionais incluem:
● Segurança: Todas as transações e informações dos usuários deverão ser
criptografadas.
● Desempenho: O sistema deve ser capaz de suportar até 1000 usuários simultâneos,
mantendo um tempo de resposta de até 2 segundos.
● Escalabilidade: O sistema deve ser escalável para que novos módulos e
funcionalidades possam ser adicionados no futuro.
● Compatibilidade: A plataforma deve ser responsiva, oferecendo uma experiência
otimizada tanto para desktops quanto para dispositivos móveis.
5. Diagrama de Casos de Uso
Figura 1: Diagrama de Casos de Uso da Plataforma ShopNow
6. Descrição Detalhada dos Casos de Uso Principais
Caso de Uso 1: Login e Cadastro
● Ator Principal: Usuário
● Descrição: O usuário acessa a página inicial do site e pode se cadastrar como um
novo cliente ou fazer login caso já tenha uma conta.
● Fluxo Principal:
1. O usuário acessa a página de login.
2. O sistema exibe o formulário de login/cadastro.
3. O usuário insere suas informações de login (e-mail e senha) ou se cadastra
preenchendo um formulário.
4. O sistema valida as informações e concede acesso à plataforma.
Caso de Uso 2: Busca de Produtos
● Ator Principal: Usuário
● Descrição: O usuário pesquisa por produtos utilizando palavras-chave ou categorias.
● Fluxo Principal:
1. O usuário insere o nome do produto ou categoria na barra de busca.
2. O sistema retorna os produtos que correspondem à pesquisa.
3. O usuário visualiza a lista de produtos e pode acessar as informações
detalhadas de cada um.
Caso de Uso 3: Pagamento
● Ator Principal: Usuário
● Descrição: O usuário realiza o pagamento dos produtos adicionados ao carrinho
utilizando métodos de pagamento disponíveis.
● Fluxo Principal:
1. O usuário naliza a compra no carrinho.
2. O sistema redireciona o usuário para a página de pagamento.
3. O usuário seleciona o método de pagamento (cartão de crédito, boleto, etc.).
4. O sistema processa o pagamento e conrma a compra.
7. Conclusão
O projeto ShopNow é uma solução de e-commerce robusta, projetada para oferecer uma
experiência de compra eciente e segura aos usuários. A arquitetura modular da
plataforma permite sua escalabilidade e a fácil integração de novas funcionalidades no
futuro. Com a implementação dos objetivos funcionais e não funcionais denidos, espera-se
que a plataforma atenda às necessidades tanto dos consumidores quanto dos vendedores,
tornando-se uma ferramenta essencial no ambiente de comércio eletrônico.
8. Referências
● Sommerville, Ian. Software Engineering. Pearson, 2016.
● Gamma, Erich, et al. Design Patterns: Elements of Reusable Object-Oriented Software.
Addison-Wesley, 1994.
