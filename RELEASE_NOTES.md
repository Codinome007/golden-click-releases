# Golden Click 12.9.7

## Correção ao marcar contas

Corrige a exceção **System.NullReferenceException em UpdateLoginOrderLabels** ao marcar contas da fila. A coluna Ordem passa a ser atualizada depois do evento de marcação do Windows, com cada linha associada ao ID da conta. A ordem de seleção continua sendo registrada imediatamente, e marcações seguidas são agrupadas na atualização visual.

Contas, senhas protegidas, perfis, calibrações e tempos anteriores são preservados. **Entrar / testar** mantém login individual seguido do perfil escolhido; **Iniciar fila de login** mantém o perfil após a última conta. F9 continua interrompendo toda a rotina.

## Atualizar

Feche todas as instâncias do Golden Click. Baixe e extraia **Golden_Click_Instalador_Windows11_x64.zip**, depois execute **Instalar_Golden_Click.exe**. Para usar a versão portátil, extraia **Golden_Click_Portatil_Windows11_x64.zip** e abra **GoldenClick.exe**. Não é necessário apagar dados ou recadastrar contas para aplicar esta correção.

Pacotes sem código-fonte, contas ou senhas. Os links automáticos Source code contêm somente a documentação pública.

## Validação

Testes automatizados e compilação no Windows x64. O teste da interface usa o formulário real e notificações do ListView nativo, sem abrir cofre ou jogo; cobre marcar, desmarcar, remarcar, recarregar, limpar, remover conta, linha incompleta e alternâncias rápidas. A publicação confere SHA-256, versão interna 12.9.7 e ausência de fontes. O funcionamento no cliente do jogo precisa ser conferido no computador de destino.
