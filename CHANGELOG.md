# Histórico de versões

## 12.10.2

- Corrige o corte das opções de alinhamento na janela compacta.

## 12.10.1

- Janela principal compacta e lista de contas mais baixa.

## 12.10.0

- Tempos da interface em segundos fracionários, preservando duração e compatibilidade de perfis antigos.
- Menus e seções reorganizados; janela ampliada e aba Contas e login.
- Aparência Sistema, Claro e Escuro, salva por instância e aplicada aos diálogos.
- Ordenação crescente/decrescente pelos cabeçalhos das contas, numérica para janela e ordem.
- Seleção por ID após ordenar, sem alterar a fila de execução.
- Testes de conversão, tema e ordenação na interface Windows.

## 12.9.7

- Corrige referência nula ao atualizar a coluna Ordem durante ItemCheck.
- Atualização visual adiada até o evento nativo terminar e agrupada entre marcações.
- Linhas identificadas pelo ID da conta, sem dependência do índice.
- Recompõe a coluna Ordem quando uma linha estiver incompleta.
- Testes da interface WinForms real no Windows para seleção, remarcação, recarga, remoção e marcações rápidas.
- Mantém login, perfil final, contas, calibrações e temporizações.

## 12.9.6

- Corrige Entrar / testar para iniciar o perfil escolhido após o login individual e a espera.
- Perfil após login usa somente destinos que receberam login, sem duplicação.
- Selecionar a mesma janela nos dois campos não bloqueia nem duplica os cliques do perfil.
- Login somente na Janela 2 não exige Janela 1 para o perfil final.
- Foco no primeiro destino antes de iniciar o perfil.
- Preencher continua sem perfil; fila mantém perfil somente após a última conta.
- Regressões cobrem destino repetido, destinos distintos e login individual seguido de perfil.

## 12.9.5

- Fila de contas na ordem de marcação, com coluna Ordem.
- Espera inicial, intervalo entre contas e espera antes do perfil final em segundos.
- Perfil opcional ao concluir toda a fila, respeitando seus destinos e repetições.
- Configuração salva por instância, sem credenciais no arquivo da fila; não inicia ao abrir o programa.
- Validação antes de começar, ordem e perfil fixados por execução.
- Erros e F9 interrompem a fila, esperas e perfil; não há tentativas automáticas.
- Testes de persistência, ordem, limites, intervalos e interrupção.

## 12.9.4

- Abertura calibrada opcional antes de preencher login e senha.
- Teste de abertura sem credenciais e espera após abrir configurável.
- Clique posterior a Carregar, com espera independente de 0 a 120000 ms.
- Edição de calibrações existentes, preservando compatibilidade com as antigas.
- Preencher não envia nem executa o clique posterior; Entrar / testar executa a sequência completa.
- Testes de ordem das etapas, cancelamento, limites e persistência.

## 12.9.3

- Remove o texto fixo 12.8.1 da barra de título.
- Janela, área de notificação e instalador mostram sua versão real.
- Mantém importação de contas e calibração de login.
- Compilação Windows x64 e 90 testes de regressão aprovados.


## 12.9.2

- Importação de CSV/TXT com prévia e senhas ocultas, até 1.000 contas.
- Modelo CSV, validação de linhas e preservação de contas repetidas.
- Calibração manual de formulário e proteção de credenciais mantidas.
- Compilação Windows x64 e 90 testes automatizados aprovados.
- Publicação confere SHA-256 e versão interna dos executáveis.


## 12.8.1

- Capturas registram sempre a área interna da janela, sem usar a resolução do monitor.
- Ajuste proporcional de X/Y ao tamanho e à posição atuais de cada janela.
- Prévia de coordenadas na lista e preservação dos valores originais.
- Compatibilidade de perfis antigos; recaptura necessária quando não há referência de janela.
- 22 verificações de coordenadas e persistência.

## 12.8.0

- Canal público de downloads separado do código privado.
- Consulta de novas versões pelo aplicativo e opção de baixar o instalador.
- Verificação SHA-256 e formato Windows x64 antes de iniciar a instalação.
- Identidade Golden Click e documentação dos downloads.

## 12.7.0

- Golden Click como nome do programa.
- Resolução de referência por clique na lista inicial.
- Ícone na área de notificação com comandos de execução e saída.
- Golden verde durante a automação.

## 12.6.5

- Carregamento direto do ícone do golden e arquivo próprio para o atalho.
