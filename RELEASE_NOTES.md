# Golden Click 12.9.5

## Fila de login e perfil final

Na aba **Login — Teste**, marque as caixas das contas na ordem desejada. A coluna **Ordem** mostra a sequência; desmarcar e marcar uma conta a move para o fim. Defina **Espera inicial (s)**, **Entre contas (s)** e **Espera antes do perfil (s)**, de 0 a 3600 segundos.

Em **Ao terminar a fila**, escolha **Nenhum perfil** ou um perfil de cliques. Ele inicia somente depois de todas as contas, usando os destinos e repetições configurados na aba Perfis. **Salvar fila e tempos** preserva a configuração nesta instância, sem salvar senhas no arquivo da fila. A abertura do aplicativo não inicia a execução. Use **Iniciar fila de login** para começar.

**F9** ou **Parar** interrompe logins, esperas e perfil. Qualquer erro interrompe a fila sem seguir para outra conta ou iniciar o perfil final. A ordem, as contas, os destinos e o perfil são fixados ao iniciar; alterações de campos durante a execução só valem para a próxima fila. Os botões **Preencher** e **Entrar / testar** continuam individuais.

A rotina envia os formulários; não confirma autenticação nem faz logout. Para usar outra conta na mesma janela, configure no jogo o retorno à tela de login antes da próxima etapa. O intervalo é contado após o término da rotina anterior. Não há repetição automática da fila nem tentativa automática em caso de erro.

## Calibração mantida

Em Calibrar formulário, você pode capturar o ponto Abrir formulário e um clique após Carregar, com esperas independentes. Use Calibrado (abertura opcional) para executar pelos pontos capturados. Se redimensionar a janela, recalibre.

## Instalar ou atualizar

Feche todas as instâncias. Baixe e extraia Golden_Click_Instalador_Windows11_x64.zip e execute Instalar_Golden_Click.exe. Instala em C:\Golden Click e cria atalho na Área de Trabalho. Para uso portátil, extraia Golden_Click_Portatil_Windows11_x64.zip e abra GoldenClick.exe. Os perfis e as contas locais existentes são preservados.

Os pacotes não contêm código-fonte, contas ou senhas. Os links Source code gerados pelo GitHub contêm somente a documentação pública.

## Validação

Testes automatizados e compilação em Windows x64. Antes da publicação são conferidos SHA-256, versão interna 12.9.5 e ausência de código-fonte. Interface, instalação e resultado da autenticação precisam ser conferidos no computador de destino.
