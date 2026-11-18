<div align="center">

<img src="assets/golden.png" width="128" alt="Golden retriever — símbolo do Golden Click" />

# Golden Click

**Perfis de cliques. Duas janelas. Você no controle.**

![Windows 11 x64](https://img.shields.io/badge/Windows_11-x64-111827?style=for-the-badge&logo=windows&logoColor=white)
[![Última versão](https://img.shields.io/github/v/release/Codinome007/golden-click-releases?style=for-the-badge&color=f59e0b&label=vers%C3%A3o)](https://github.com/Codinome007/golden-click-releases/releases/latest)

[**BAIXAR INSTALADOR**](https://github.com/Codinome007/golden-click-releases/releases/latest/download/Golden_Click_Instalador_Windows11_x64.zip) · [**VERSÃO PORTÁTIL**](https://github.com/Codinome007/golden-click-releases/releases/latest/download/Golden_Click_Portatil_Windows11_x64.zip)

</div>

![Golden Click — automação para Windows](assets/banner.svg)

## Escolha como usar

| Pacote | Como funciona |
| --- | --- |
| **Instalador** | Instala em `C:\Golden Click` e cria um atalho na Área de Trabalho. |
| **Portátil** | Extraia em uma pasta gravável e abra `GoldenClick.exe`. Não exige instalar o .NET separadamente. |

Os arquivos de download ficam nas **[Releases](https://github.com/Codinome007/golden-click-releases/releases)**. Este repositório distribui os executáveis, instruções e identidade visual; o código do aplicativo permanece privado. Os links automáticos “Source code” do GitHub contêm somente estes arquivos públicos, sem o código do programa.

## O que você pode fazer

- Criar perfis com sequência, botão, tipo de clique e pausa individual.
- Repetir por quantidade ou continuamente e usar atalhos globais configuráveis.
- Selecionar até duas janelas e organizá-las em quatro alinhamentos.
- Usar coordenadas ou referências de imagem; consultar o tamanho da janela capturada por clique.
- Ajustar cliques X/Y proporcionalmente quando a janela for movida ou redimensionada.
- Controlar o programa pelo ícone perto do relógio, que fica verde durante os cliques.
- Consultar novas versões pelo próprio aplicativo, sem conta ou token do GitHub.

## Comece em quatro passos

1. Baixe e extraia um dos pacotes acima.
2. Abra o programa e selecione a janela de destino.
3. Escolha um perfil e capture os pontos de clique; confira as coordenadas e a resolução.
4. Inicie a sequência. Por padrão, **F8** inicia/para, **F9** interrompe e **F6** captura uma posição.

Para ocultar a janela, minimize. Clique duas vezes no golden perto do relógio para abrir novamente; clique com o botão direito para controlar a automação ou sair. O Windows pode agrupar esse ícone na seta de ícones ocultos.

## Atualizações e perfis

A partir da versão 12.8.0, o programa consulta o canal oficial ao abrir e periodicamente. Para baixar e instalar uma versão disponível, use **Verificar atualização** no menu do ícone ou em **Atalhos e arquivos**. O download é conferido por SHA-256 antes de executar o instalador; a instalação é confirmada pelo usuário e pelo Windows. Feche as demais instâncias antes de instalar.

Os perfis e imagens ficam em `dados` e `dados-instancia-N`, ao lado do executável. O instalador preserva esses arquivos e copia os perfis da antiga pasta padrão `C:\ClickVision Pro` quando a pasta correspondente ainda não existe no novo destino. Faça a transferência manual se usava outra pasta portátil.

## Janela capturada e redimensionamento

Na versão 12.8.1, a coluna **Janela** registra a área interna da janela, sem barra de título e bordas. A resolução do monitor não é usada. Os cliques X/Y acompanham o tamanho e a posição atuais de cada janela selecionada, mantendo as coordenadas originais salvas.

Exemplo: um ponto **480,270** em **960×540** passa para **640,360** em **1280×720**. Passe o mouse em X, Y ou Janela para conferir a prévia na janela de teste.

Cliques antigos com referência de janela válida também se ajustam. Se aparecer **—**, ou o registro antigo tiver sido feito pela resolução do monitor, recapture o ponto uma vez para habilitar o ajuste. O programa não tenta adivinhar a dimensão da janela anterior.

A escala proporcional pressupõe que os elementos mantenham a posição proporcional no layout. Mudanças do layout interno podem exigir recaptura. Cliques por imagem continuam usando reconhecimento e recortes compatíveis com a resolução.

## Versão atual: 12.10.2

O painel **Organização no monitor** mostra os quatro alinhamentos em duas linhas, com espaço para as prévias e os rótulos. A janela continua compacta.

### Janela compacta da versão 12.10.1

A janela principal abre em 640 × 490 de área interna, passando a ocupar cerca de 42% menos área. A lista de contas ficou mais baixa para dar espaço aos controles do formulário e da fila. As abas com mais opções podem ser roladas.

### Interface da versão 12.10.0

**Tempos em segundos:** pausas de cliques, ciclos, reconhecimento de imagem e esperas da calibração agora usam segundos, com até três casas decimais. Exemplo: 0,1 s corresponde à antiga pausa de 100 ms. Os perfis existentes mantêm a duração original; os arquivos internos continuam compatíveis.

**Menus reorganizados:** janela ampliada, seções por função e aba **Contas e login** dividida em contas, formulário/execução individual e fila/perfil final. **Configurações** agrupa aparência, atalhos, arquivos e atualizações.

**Tema:** em **Configurações → Aparência**, escolha **Sistema**, **Claro** ou **Escuro**. Sistema acompanha a preferência de aplicativos do Windows; a escolha é salva por instância. A paleta é aplicada também aos diálogos do programa.

**Ordenar contas:** clique no cabeçalho de **Conta**, **Código/login**, **Janela** ou **Ordem** para crescente; clique novamente para decrescente. As colunas Janela e Ordem usam comparação numérica. Ordenar muda somente a exibição; a fila continua seguindo a ordem em que as contas foram marcadas. Edição, exclusão e calibração usam o ID da conta selecionada.

### Correção mantida da 12.9.7

Corrige a exceção **System.NullReferenceException em UpdateLoginOrderLabels** ao marcar contas da fila. A coluna Ordem passa a ser atualizada depois do evento de marcação do Windows, com cada linha associada ao ID da conta. A ordem de seleção continua sendo registrada imediatamente, e marcações seguidas são agrupadas na atualização visual.

Contas, senhas protegidas, perfis, calibrações e tempos anteriores são preservados. **Entrar / testar** mantém login individual seguido do perfil escolhido; **Iniciar fila de login** mantém o perfil após a última conta. F9 continua interrompendo toda a rotina.

### Perfil após login — 12.9.6

Corrigido o início do perfil após login. **Entrar / testar** agora executa o login individual e, depois da **Espera antes do perfil (s)**, inicia o perfil escolhido em **Após login / fim da fila**. **Preencher** continua somente preenchendo os campos. **Iniciar fila de login** mantém o perfil após a última conta.

O perfil usa apenas as janelas que receberam login, sem repetir um destino selecionado nos dois campos. Um login na Janela 2 não exige selecionar a Janela 1. A execução manual de perfis também aceita o mesmo destino nos dois campos como uma única janela; organizar duas janelas continua exigindo destinos diferentes. Repetições do perfil, calibração, fila e F9 são mantidos.

O primeiro destino do perfil recebe foco antes de iniciar. O fluxo é por coordenadas e tempo; o envio do formulário não comprova autenticação. Confira se o jogo chegou à tela esperada antes dos cliques do perfil.

### Fila de login — 12.9.5

Na aba **Login — Teste**, marque as caixas das contas na ordem desejada. A coluna **Ordem** mostra a sequência; desmarcar e marcar uma conta a move para o fim. Defina **Espera inicial (s)**, **Entre contas (s)** e **Espera antes do perfil (s)**, de 0 a 3600 segundos.

Em **Após login / fim da fila**, escolha **Nenhum perfil** ou um perfil de cliques. Ele inicia somente depois de todas as contas, usando as janelas que receberam login e as repetições configuradas na aba Perfis. **Salvar fila e tempos** preserva a configuração nesta instância, sem salvar senhas no arquivo da fila. A abertura do aplicativo não inicia a execução. Use **Iniciar fila de login** para começar.

**F9** ou **Parar** interrompe logins, esperas e perfil. Qualquer erro interrompe a fila sem seguir para outra conta ou iniciar o perfil final. A ordem, as contas, os destinos e o perfil são fixados ao iniciar; alterações de campos durante a execução só valem para a próxima fila. **Preencher** usa só uma conta, sem perfil. **Entrar / testar** usa uma conta e também inicia o perfil escolhido após a espera.

A rotina envia os formulários; não confirma autenticação nem faz logout. Para usar outra conta na mesma janela, configure no jogo o retorno à tela de login antes da próxima etapa. O intervalo é contado após o término da rotina anterior. Não há repetição automática da fila nem tentativa automática em caso de erro.

### Calibração de login — 12.9.4

Na aba **Login — Teste → Calibrar formulário**, habilite **Abrir formulário antes de preencher**, capture o botão na tela de sessão e ajuste **Espera após abrir (ms)**. Use **Testar abertura (3 s)** para abrir sem preencher credenciais. Capture então Código/login, Senha e Carregar. Para o passo final, habilite **Clique adicional após Carregar**, capture o ponto e ajuste **Espera antes do clique posterior (ms)**.

Use **Calibrado (abertura opcional)**. **Preencher** abre (se habilitado) e preenche os campos. **Entrar / testar** também clica em Carregar, aguarda e executa o clique posterior habilitado. Os dois tempos são independentes, de 0 a 120000 ms (1000 ms = 1 segundo). Desative a abertura se o formulário já estiver aberto. Configurações ficam salvas por janela; calibrações antigas continuam sem os extras. F9 cancela também durante as esperas. Recalibre se o tamanho da janela mudar. O fluxo usa coordenadas e tempo; confira no jogo se cada tela abriu e se o login foi aceito.

### Correção mantida da 12.9.3

Correção da versão exibida: a barra de título, o ícone perto do relógio e a tela do instalador agora usam a versão do próprio executável, evitando o antigo texto fixo 12.8.1.

## Novidades da versão 12.9.2

- Importe várias contas por CSV/TXT, com prévia e senhas ocultas.
- Salve um modelo CSV pelo aplicativo e preencha uma conta por linha: `nome;login;senha;janela`.
- Até 1.000 contas por arquivo; duplicatas na mesma janela preservam a senha existente.
- Selecione a conta após importar; a importação não inicia o login.
- Se o formulário não for reconhecido, abra Transferir dados manualmente e use Calibrar formulário para marcar código, senha e Carregar. Escolha Calibrado (abertura opcional); habilite os pontos extras se precisar.

As contas ficam protegidas pelo usuário atual do Windows, fora dos perfis exportados e dos pacotes. Não acompanham o ZIP portátil para outro computador. O arquivo de importação contém senhas legíveis; mantenha-o protegido ou exclua-o após usar. O preenchimento e a autenticação precisam de teste no cliente do jogo.

## Compatibilidade

Windows 11 x64. A execução dos cliques depende da janela de destino e das permissões dos programas envolvidos. Consulte as notas de cada versão para saber o que foi validado. Compilação automatizada não substitui teste da interface e da instalação no computador de destino.

## Ajuda

Encontrou um problema? Abra uma [issue](https://github.com/Codinome007/golden-click-releases/issues/new/choose) informando a versão, o comportamento esperado e os passos para reproduzir. Evite anexar informações pessoais.

---

<div align="center">Mantido por <a href="https://github.com/Codinome007">Codinome007</a> · Golden Click</div>
