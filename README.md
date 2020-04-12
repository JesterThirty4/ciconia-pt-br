If you want to read this readme in english, please refer to this [Link](https://github.com/JesterThirty4/ciconia-pt-br/blob/master/READMEEN.md).

# Sobre ciconia-pt-br
Esse repositório tem como objetivo traduzir a Phase 1 de Ciconia e suas sequências do Inglês para o Português Brasileiro.
# Sobre o Patch / Instalação da Tradução
Para instalar a versão mais atual do patch, vá até a página [Releases](https://github.com/JesterThirty4/ciconia-pt-br/releases) e baixe o .rar mais recente.
Instruções de instalação estão contidas no README dentro do .rar

# Estrutura do Repositório

- tools: A pasta onde imagens em PSD necessárias para alterar menus/logos estão guardadas.
- fonts-used: Onde fontes de texto estão guardadas. Mesmo propósito acima.
- script: onde o script do jogo está guardado.
- arc: Arquivos principais usados no projeto.

# Como criar um release final
## Essas não são instruções de instalação da tradução! Para elas, leia "Sobre o Patch" acima.
Para criar um patch final no meu repositório, os recursos necessários já estão inclusos em [tools](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/tools).
- A primeira etapa é extrair o *arc.nsa*, para isso use o *nsaout.exe*, basta deixar ele em uma pasta junto com o arquivo *arc.nsa* e executar o *nsaout* que ele extrairá os arquivos automaticamente em uma pasta chamada arc*
- Agora você possuí todos as imagens que você precisa editar. Procure por PSDs do arquivo que vai editar no [photoshop-resources](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/photoshop%20resources). Após editar o necessário, você precisa compilar o arc em um *.nsa* novamente. Para isso, use a ferramenta *nsaarc.exe* em [tools](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/tools). Basta executar, selecionar a pasta arc e escrever o nome do *arquivo.nsa*
- Quanto ao script, você precisa extrair ele de um arquivo *pscript.dat* para um arquivo de texto. Meu repositório já incluí uma versão de texto extraida na pasta [script](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/script). Se quiser fazer o trabalho manualmente, use o *nsdec.exe* na pasta [tools](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/tools). Basta colocar o arquivo *pscript.dat* na mesma pasta que ele e o renomear para *nscript.dat*. O texto será extraído no *result.txt* na mesma pasta.
- Faça suas alterações no script agora que ele está em formato de texto! Para compactar ele em um formato *.dat* novamente, use a ferramenta *nsmake.exe* contida em [tools](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/tools). Basta renomear seu arquivo de texto para *0.txt* e o colocar na mesma pasta do *nsmake.exe*. Após isso, execute o *nsmake*. O resultado será um arquivo *nscript.dat*, o renomeie para *pscript.dat*.
- Agora você precisa organizar os arquivos no seu projeto. Use os arquivos em [steam api](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/steam%20api) e [CiconiaPhase1.app](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/CiconiaPhase1.app), eles são necessários para o funcionamento do patch, assim como a fonte *default.ttf* em [fonts-used](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/fonts-used).
- No fim, seu patch deve estar organizado em uma pasta [dessa maneira](https://i.imgur.com/eucxqF9.png).

# Membros do projeto
- [JesterThirty4](https://twitter.com/JesterThirty4) (Tradutor)
- [Anna Reis](https://twitter.com/MiyoHead) (Programador)

# Agradecimentos

- [@MiyoHead](https://twitter.com/MiyoHead) Me ajudou com o script e construção do patch! Obrigado!
- [@InochiPM](https://twitter.com/InochiPM) Me providenciou a PSD para o logo de Ciconia dele. Obrigado!
- [@Loli_Deca](https://twitter.com/Loli_Deca) Me ajudou com a correção de alguns erros gramaticais importantes. Obrigado!
