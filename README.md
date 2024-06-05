# Plano de Teste de Usabilidade para Tela de Login


Objetivo
Avaliar a usabilidade da tela de login para identificar problemas e obter feedback dos usuários.

Estrutura da Tela
Campos de entrada: "Usuário" e "Senha"
Link: "Esqueci minha senha"
Botão: "Entrar"

Ferramenta Utilizada
Para este teste de usabilidade, utilizaremos uma combinação de observação direta e questionários. Não será necessário o uso de ferramentas específicas além do ambiente de teste.

Casos de testes:
1.Realizar login com credenciais corretas
2.Realizar login com credencial "usuário" incorreta
3.Realizar login com credencial "senha" incorreta
4.Seguir fluxo para recuperar senha

Massa de Teste Básica

Usuários válidos:
Usuário: usuario1
Senha: senha1
Usuário: usuario2
Senha: senha2

Usuários inválidos:
Usuário: usuario_invalido
Senha: senha_errada

Cenário de recuperação de senha:
E-mail registrado: usuario1@example.com
E-mail não registrado: nao_registrado@example.com

Procedimento de Teste

Caso de teste 1: Realizar login com credenciais corretas
Inserir o valor "usuario1" no campo de "usuário" e o valor "senha1" no campo de "senha"; depois, clicar no botão "entrar".
Critérios de sucesso: O usuário deve conseguir fazer login sem dificuldades.
Coleta de dados: Tempo de conclusão, erros cometidos.

Caso de teste 2: Realizar login com credencial "usuário" incorreta
Inserir o valor "usuário02" no campo "usuário" e o valor "senha2" no campo de "senha"; depois, clicar no botão "entrar"
Critérios de sucesso: O sistema deve exibir uma mensagem de erro clara.
Coleta de dados: Mensagens de erro exibidas, número de tentativas.

Caso de teste 3: Realizar login com credencial "senha" incorreta
Inserir o valor "usuário2" no campo "usuário" e o valor "senha02" no campo de "senha"; depois, clicar no botão "entrar"
Critérios de sucesso: O sistema deve exibir uma mensagem de erro clara.
Coleta de dados: Mensagens de erro exibidas, número de tentativas.

Caso de teste 4: Seguir fluxo para recuperar senha
Clicar no link "esqueci minha senha" e seguir as instruções para recuperar sua senha usando o e-mail: "usuario1@example.com".
Critérios de sucesso: O usuário deve ser direcionado corretamente e conseguir seguir as instruções.
Coleta de dados: Facilidade de navegação, clareza das instruções, tempo de conclusão.

Análise dos Resultados
Taxa de sucesso: Quantidade de resultados esperados obtidos divido pelo número de testes realizados.
Tempo de conclusão: Tempo médio para completar cada tarefa.
Número de erros: Quantidade de erros cometidos durante execução dos testes.



