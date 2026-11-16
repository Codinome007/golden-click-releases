## Golden Click 12.8.1

### Janela capturada e coordenadas proporcionais
- A coluna **Janela** registra sempre a área interna da janela capturada, sem bordas ou barra de título. Não usa a resolução do monitor.
- Cliques X/Y com referência de janela se ajustam proporcionalmente ao tamanho atual e acompanham a posição da janela na tela.
- Cada uma das duas janelas selecionadas usa suas próprias dimensões.
- As coordenadas originais permanecem salvas, evitando erro acumulado após vários redimensionamentos.
- Passe o mouse em X, Y ou Janela na lista para conferir a prévia na janela de teste.

**Exemplo:** o ponto **480,270** numa janela **960×540** passa para **640,360** numa janela **1280×720**.

### Perfis existentes
Registros anteriores com referência de janela válida já podem se ajustar. Cliques antigos baseados no monitor ou sem referência mostram **—** e precisam de uma recaptura para habilitar o ajuste. Até lá, mantêm o modo anterior, sem usar a dimensão do monitor como se fosse a da janela.

O ajuste é proporcional para cliques por coordenadas. Cliques por imagem continuam dependendo do reconhecimento e dos recortes compatíveis com a resolução. Se o layout interno reposicionar elementos de outra forma, pode ser necessário recapturar pontos ou imagens.

### Instalar ou atualizar
Baixe o instalador ou o pacote portátil abaixo. O instalador usa `C:\Golden Click` e preserva os perfis da pasta. Feche as outras instâncias antes de instalar. Na versão 12.8.0, você também pode usar **Verificar atualização** no menu perto do relógio.

### Validação
22 verificações de coordenadas/persistência e 14 verificações do atualizador. Compilação automatizada no Windows x64. Interface, instalação e cliques no programa de destino ainda precisam de teste interativo.

Os pacotes não incluem o código-fonte do aplicativo. Os links **Source code** automáticos do GitHub contêm somente a documentação e os arquivos de publicação do canal público.
