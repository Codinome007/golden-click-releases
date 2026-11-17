# Golden Click 12.9.6

## Correção do perfil após login

Corrigido o início do perfil após login. **Entrar / testar** agora executa o login individual e, depois da **Espera antes do perfil (s)**, inicia o perfil escolhido em **Após login / fim da fila**. **Preencher** continua somente preenchendo os campos. **Iniciar fila de login** mantém o perfil após a última conta.

O perfil usa apenas as janelas que receberam login, sem repetir um destino selecionado nos dois campos. Um login na Janela 2 não exige selecionar a Janela 1. A execução manual de perfis também aceita o mesmo destino nos dois campos como uma única janela; organizar duas janelas continua exigindo destinos diferentes. Repetições do perfil, calibração, fila e F9 são mantidos.

O primeiro destino do perfil recebe foco antes de iniciar. O fluxo é por coordenadas e tempo; o envio do formulário não comprova autenticação. Confira se o jogo chegou à tela esperada antes dos cliques do perfil.

## Como usar

Escolha o perfil em **Login — Teste → Após login / fim da fila** e ajuste **Espera antes do perfil (s)**. Para uma conta, selecione a linha e use **Entrar / testar**. Para várias, marque as caixas na ordem desejada e use **Iniciar fila de login**. F9 ou Parar interrompe login, esperas e perfil. **Nenhum perfil** desativa essa etapa.

## Instalar ou atualizar

Feche todas as instâncias. Baixe e extraia **Golden_Click_Instalador_Windows11_x64.zip** e execute **Instalar_Golden_Click.exe**. Instala em C:\Golden Click com atalho na Área de Trabalho. Para uso portátil, extraia **Golden_Click_Portatil_Windows11_x64.zip** e abra **GoldenClick.exe**. Perfis e contas locais existentes são preservados.

Pacotes sem código-fonte, contas ou senhas. Os arquivos Source code gerados pelo GitHub contêm somente a documentação pública.

## Validação

Compilação e testes automatizados em Windows x64. A publicação verifica SHA-256, versão interna 12.9.6 e ausência de fontes. Interface, instalação e comportamento no jogo exigem conferência no computador de destino.
