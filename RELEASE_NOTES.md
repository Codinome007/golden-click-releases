# Golden Click 12.9.4

## Calibração com abertura e clique posterior

Na aba **Login — Teste → Calibrar formulário**, habilite **Abrir formulário antes de preencher**, capture o botão na tela de sessão e ajuste **Espera após abrir (ms)**. Use **Testar abertura (3 s)** para abrir sem preencher credenciais. Capture então Código/login, Senha e Carregar. Para o passo final, habilite **Clique adicional após Carregar**, capture o ponto e ajuste **Espera antes do clique posterior (ms)**.

Use **Calibrado (abertura opcional)**. **Preencher** abre (se habilitado) e preenche os campos. **Entrar / testar** também clica em Carregar, aguarda e executa o clique posterior habilitado. Os dois tempos são independentes, de 0 a 120000 ms (1000 ms = 1 segundo). Desative a abertura se o formulário já estiver aberto. Configurações ficam salvas por janela; calibrações antigas continuam sem os extras. F9 cancela também durante as esperas. Recalibre se o tamanho da janela mudar. O fluxo usa coordenadas e tempo; confira no jogo se cada tela abriu e se o login foi aceito.

## Instalar ou atualizar

Baixe e extraia **Golden_Click_Instalador_Windows11_x64.zip**, depois execute **Instalar_Golden_Click.exe**. Feche todas as instâncias antes de instalar. O destino é C:\Golden Click, com atalho na Área de Trabalho e preservação dos perfis. Para usar sem instalar, extraia **Golden_Click_Portatil_Windows11_x64.zip** e abra **GoldenClick.exe**.

Importação de contas, proteção de senhas, versão automática no título e demais recursos anteriores mantidos. Os pacotes não contêm código-fonte, contas ou senhas. Os arquivos automáticos Source code contêm somente a documentação pública.

## Validação

Compilação e testes automatizados em Windows x64. A publicação confere SHA-256, versão interna 12.9.4 e ausência de código-fonte. Interface, instalação e comportamento do cliente do jogo precisam ser conferidos no computador de destino.
