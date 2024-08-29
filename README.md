# 2024-tri2-ia22-autenticacao-2021311991

## Autenticação de Usuários (Single Server)

- autenticação de usuários é o processo de verificar a identidade de um usuário que tenta acessar um sistema. No caso de um single server (servidor único), essa verificação ocorre em um único ponto centralizado.

- Como funciona: O usuário fornece credenciais (geralmente nome de usuário e senha) que são comparadas com um banco de dados armazenado no servidor. Se as credenciais corresponderem, o usuário é autenticado e tem permissão para acessar o sistema.

- Importância: A autenticação é fundamental para proteger sistemas contra acessos não autorizados. Ao garantir que apenas usuários legítimos possam entrar, a segurança dos dados e recursos do sistema é preservada.

# Autenticação vs. Autorização

-  Autenticação é o processo de verificar a identidade de um usuário.

- Autorização: É o processo de determinar quais recursos ou ações um usuário autenticado pode acessar ou executar. O que você pode fazer?

- *Em resumo*: A autenticação responde à pergunta "Quem é você?", enquanto a autorização responde à pergunta "O que você pode fazer?". Ambas são essenciais para um sistema de segurança eficaz.

- Exemplo: Um sistema de e-commerce. A autenticação verifica se você é um cliente cadastrado. A autorização determina se você pode visualizar seus pedidos, fazer um novo pedido ou acessar informações administrativas (dependendo do seu perfil).

# Autenticação com Token (JWT)

- Como funciona: Quando um usuário se autentica, um token JWT é gerado e enviado para o cliente. O cliente então inclui esse token em todas as solicitações subsequentes. O servidor valida o token em cada solicitação para verificar a identidade do usuário e garantir que o token não foi alterado.

 # Vantagens:

- Stateless: O servidor não precisa manter um estado para cada usuário, o que simplifica a arquitetura e aumenta a escalabilidade.
- Seguro: O uso de assinaturas digitais garante a integridade do token e protege contra ataques.
Fácil de usar: O formato JSON torna os tokens fáceis de ler e processar.

# Projeto:

- Objetivo: Uma iniciativa com um propósito específico.
Objeto de estudo: O tema central do projeto.
- Exemplos: Desenvolvimento de software, pesquisa, construção, etc.
