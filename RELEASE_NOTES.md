# Golden Click 12.10.0

## Interface, segundos e ordenação

**Tempos em segundos:** pausas de cliques, ciclos, reconhecimento de imagem e esperas da calibração agora usam segundos, com até três casas decimais. Exemplo: 0,1 s corresponde à antiga pausa de 100 ms. Os perfis existentes mantêm a duração original; os arquivos internos continuam compatíveis.

**Menus reorganizados:** janela ampliada, seções por função e aba **Contas e login** dividida em contas, formulário/execução individual e fila/perfil final. **Configurações** agrupa aparência, atalhos, arquivos e atualizações.

**Tema:** em **Configurações → Aparência**, escolha **Sistema**, **Claro** ou **Escuro**. Sistema acompanha a preferência de aplicativos do Windows; a escolha é salva por instância. A paleta é aplicada também aos diálogos do programa.

**Ordenar contas:** clique no cabeçalho de **Conta**, **Código/login**, **Janela** ou **Ordem** para crescente; clique novamente para decrescente. As colunas Janela e Ordem usam comparação numérica. Ordenar muda somente a exibição; a fila continua seguindo a ordem em que as contas foram marcadas. Edição, exclusão e calibração usam o ID da conta selecionada.

## Atualizar

Feche todas as instâncias. Extraia Golden_Click_Instalador_Windows11_x64.zip e execute Instalar_Golden_Click.exe. Para uso portátil, extraia Golden_Click_Portatil_Windows11_x64.zip e abra GoldenClick.exe. Perfis, contas, calibrações e tempos anteriores são preservados; não é necessário recadastrar.

Os pacotes não incluem fontes, contas ou senhas. Os links Source code do GitHub contêm somente a documentação pública.

## Validação

Compilação Windows x64 e testes automatizados, incluindo controles WinForms nativos, segundos fracionários, paletas e ordenação sem trocar a conta ou a fila. A publicação confere SHA-256 e versão interna. Funcionamento no cliente do jogo precisa ser conferido no computador de destino.
