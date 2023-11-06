# DescomplicAi-Simplificando-Documentacoes
 Da Complexidade à Clareza

## Link da Documentação Git Simplificada
[Documentação do GIT Simplificada](https://evergreen-deal-396.notion.site/DescomplicAi-Simplificando-o-GIT-5c79b7dd0f7a4b24b905ab8020901df9)
 
# DescomplicAi - Simplificando o GIT

**GIT**
*O Git é uma ferramenta que ajuda a controlar e gerenciar versões de arquivos. É útil para acompanhar mudanças em projetos de programação.*

**Estados**
Os arquivos no Git têm 3 estados:

1. **Modificado**: Isso acontece quando você faz alterações em um arquivo.
2. **Preparado**: Aqui, você seleciona as alterações que deseja salvar.
3. **Consolidado**: Neste estado, as alterações são salvas permanentemente.

**Ajuda**
Você pode obter ajuda sobre o Git usando o comando "git help". Por exemplo, "git help add" mostrará informações sobre o comando "add".

**Configuração**
Você pode personalizar o Git para suas preferências, como nome, email e editor. Isso é feito usando comandos como "git config --global user.name" para definir seu nome.

**Ignorar Arquivos**
Você pode criar listas de arquivos que o Git deve ignorar, para que eles não sejam rastreados. Essas listas podem ser gerais ou específicas para um repositório.

**Repositório Local**

- Criar um novo repositório: Use "git init" para começar a rastrear um novo projeto.
- Verificar o estado dos arquivos: "git status" mostra quais arquivos foram modificados.
- Adicionar arquivos/diretórios: "git add" prepara as alterações para serem salvas.
- Comitar arquivos/diretórios: "git commit" salva as alterações de forma permanente.
- Remover arquivos/diretórios: "git rm" exclui arquivos do repositório.
- Visualizar histórico: "git log" mostra o histórico de alterações.

**Repositório Remoto**

- Exibir repositórios remotos: "git remote" lista os repositórios remotos.
- Enviar arquivos/diretórios para o repositório remoto: "git push" envia suas alterações para o servidor remoto.
- Atualizar o repositório local com as alterações do remoto: "git pull" atualiza seu repositório local com as alterações do servidor remoto.
- Clonar um repositório remoto: "git clone" cria uma cópia local de um repositório remoto.

**Tags**
Tags são marcadores para versões específicas de seu projeto no Git. Você pode criar, listar e compartilhar tags para marcar versões importantes de seu projeto.

**Branches**
Os ramos (ou branches) permitem que você trabalhe em diferentes partes de seu projeto ao mesmo tempo. O "master" é o ramo principal por padrão. Você pode criar, trocar e mesclar ramos.

**Stash**
Stash é uma maneira de guardar temporariamente as alterações não salvas em um local seguro para que você possa alternar entre ramos ou aplicar as alterações mais tarde.

**Reescrevendo o Histórico**
Você pode alterar mensagens de commit e reorganizar os commits em seu histórico com comandos como "git commit --amend" e "git rebase".

**Bisect**
A pesquisa binária (bisect) ajuda a encontrar um commit específico onde um erro foi introduzido, marcando commits como bons ou ruins até que o problema seja isolado.

Espero que essas simplificações ajudem a tornar o Git e suas operações mais compreensíveis para iniciantes.

## #PARTIU-**DOCUMENTAÇÃO**

- **-version** - Descobre qual é a moda do Git e mostra de onde ele veio. Tipo, qual é a versão atual!
- **-help** - É como um guia de estilo para usar o Git. Você pode pedir todas as dicas usando **`a`**, e se quiser saber tudo sobre um comando específico, só pedir o manual desse comando.
- **C <caminho>** - Se você quiser que o Git pense que está em um lugar específico, como se ele fosse uma pessoa, você pode fazer isso usando essa opção. E se você fizer isso várias vezes, cada vez é como se o Git desse um passo adiante em direção ao seu destino.
- **c <nome>=<valor>** - Isso é como personalizar o Git. Você pode dizer ao Git como se vestir, como se comportar, e muito mais! É como dizer "Ei Git, use essa roupa hoje!"
- **-exec-path[=<caminho>]** - Onde estão guardadas as roupas especiais do Git. Você pode até mudar o lugar onde ele guarda essas roupas se quiser.
- **-html-path** - Descobre onde estão as histórias em quadrinhos do Git, mas sem a barra.
- **-man-path** - Descobre o caminho secreto para o livro de manuais do Git.
- **-info-path** - Encontra o esconderijo dos documentos secretos do Git.
- **p / --paginate** - É como se o Git chamasse um amigo para ajudar a ler informações longas, mas só se estiverem falando com você na tela.
- **p / --no-pager** - Às vezes, o Git está com preguiça de pedir ajuda ao amigo e lê sozinho.
- **-git-dir=<caminho>** - Diz ao Git onde encontrar a pasta secreta dele.
- **-work-tree=<caminho>** - Diz ao Git onde encontrar a sua árvore de trabalho. Não é uma floresta de verdade, é só o lugar onde o Git trabalha.
- **-namespace=<caminho>** - É como dar um nome secreto para o Git para que ele saiba onde pertence.
- **-super-prefix=<caminho>** - É tipo dar instruções secretas para subprojetos. É como dizer "Ei, subprojeto, eu sou seu chefe!"
- **-bare** - Trata o repositório como se fosse o Git em seu estado mais natural. Se você não disser onde ele deve viver, ele vai morar no diretório atual.
- **-no-replace-objects** - O Git não brinca de substituir objetos.
- **-literal-pathspecs** - O Git entende tudo ao pé da letra, sem truques ou mágicas.
- **-glob-pathspecs** - O Git gosta de fazer mágica com curingas nos nomes de arquivos.
- **-noglob-pathspecs** - O Git só acredita no que vê, sem truques ou magia.
- **-icase-pathspecs** - O Git ignora se as letras são maiúsculas ou minúsculas nos nomes dos arquivos.
- **-no-optional-locks** - O Git não gosta de esperar por coisas opcionais. É como dizer "Não faça isso, Git!"
- **-list-cmds=group[,group…]** - Você pode pedir ao Git para listar os comandos por grupos. É como pedir para ele organizar todos os brinquedos por categorias, e ele pode até se esquecer de alguns brinquedos no futuro.

**O Git tem dois tipos de comandos: comandos de alto nível (ou "porcelana") e comandos de baixo nível (ou "encanamento").**

*Os comandos de alto nível são os principais e auxiliam o usuário a interagir com o Git de forma mais amigável*:

- **git-add**: Coloca as mudanças nos arquivos no índice para serem preparadas para commit.
- **git-am**: Aplica uma série de alterações que vêm de e-mails.
- **git-archive**: Cria um histórico dos arquivos a partir de uma determinada versão.
- **git-bisect**: Ajuda a encontrar o commit que introduziu um erro usando busca binária.
- **git-branch**: Lista, cria ou deleta ramos no repositório.
- **git-bundle**: Move informações do histórico para outros lugares.
- **git-checkout**: Move entre ramos ou restaura arquivos em seu estado anterior.
- **git-cherry-pick**: Pega mudanças específicas de commits existentes.
- **git-citool**: Oferece uma alternativa gráfica ao git-commit.
- **git-clean**: Remove arquivos não rastreados da árvore de trabalho.
- **git-clone**: Copia um repositório para um novo diretório.
- **git-commit**: Grava as alterações no repositório.
- **git-describe**: Dá um nome mais legível para objetos com base em referências disponíveis.
- **git-diff**: Mostra as diferenças entre commits, o estado atual e outras coisas.
- **git-fetch**: Baixa objetos e referências de outro repositório.
- **git-format-patch**: Prepara patches para serem enviados por e-mail.
- **git-gc**: Limpa arquivos desnecessários e otimiza o repositório local.
- **git-grep**: Procura linhas que correspondam a um padrão.
- **git-gui**: Fornecer uma interface gráfica portátil para o Git.
- **git-init**: Cria um novo repositório Git ou reinicializa um existente.
- **git-log**: Mostra registros de commits.
- **git-merge**: Combina históricos de desenvolvimento.
- **git-mv**: Move ou renomeia arquivos e diretórios.
- **git-notes**: Adiciona ou inspeciona anotações de objetos.
- **git-pull**: Obtém e integra mudanças de outro repositório ou ramo local.
- **git-push**: Atualiza referências remotas enviando objetos.
- **git-range-diff**: Compara dois intervalos de commits.
- **git-rebase**: Aplica commits no topo de outro ponto de partida.
- **git-reset**: Define a posição atual do repositório para um estado específico.
- **git-restore**: Restaura a árvore de trabalho para um estado anterior.
- **git-revert**: Cria um novo commit para desfazer alterações anteriores.
- **git-rm**: Remove arquivos da árvore de trabalho e do índice.
- **git-shortlog**: Resumo das saídas do git-log.
- **git-show**: Mostra diferentes tipos de objetos.
- **git-sparse-checkout**: Controla quais partes do repositório você deseja ter em seu diretório de trabalho.
- **git-stash**: Armazena temporariamente alterações em um local seguro.
- **git-status**: Mostra o estado atual da árvore de trabalho.
- **git-submodule**: Gerencia submódulos dentro do repositório.
- **git-switch**: Alterna entre ramos facilmente.
- **git-tag**: Cria, lista, exclui ou verifica tags com assinatura GPG.
- **git-worktree**: Lida com múltiplas árvores de trabalho.
- **gitk**: É um navegador para visualizar o histórico do Git de forma gráfica.

**COMANDOS AUXILIARES**

*Esses comandos auxiliares ajudam a realizar tarefas específicas no Git, como configurações, migrações, resolução de conflitos, gerenciamento de repositórios remotos e otimização de desempenho. Cada um tem um propósito particular e pode ser útil em diferentes situações ao trabalhar com o Git.*

**git-config**: Este comando é usado para obter e definir configurações globais ou específicas de repositórios. Ele permite configurar como o Git se comporta em seu sistema ou em um repositório específico.

**git-fast-export**: É uma ferramenta usada para exportar dados de um repositório Git para outro formato, geralmente para migração ou backup de dados.

**git-fast-import**: É a contraparte do **`git-fast-export`**. É usado para importar rapidamente dados em um repositório Git a partir de outro formato.

**git-filter-branch**: Este comando é usado para reescrever ramos, permitindo que você faça modificações profundas no histórico de um repositório.

**git-mergetool**: Quando ocorrem conflitos de mesclagem, este comando ajuda a executar ferramentas de resolução de conflitos, facilitando a resolução de conflitos de mesclagem.

**git-pack-refs**: Empacota os cabeçalhos e as tags em um formato eficiente para melhorar o desempenho ao acessar o repositório.

**git-prune**: Remove objetos do banco de dados de objetos que não são mais referenciados por nenhum commit, o que ajuda a economizar espaço em disco.

**git-reflog**: Gerencia as informações do reflog, que rastreiam as referências recentes em um repositório Git, permitindo recuperar estados anteriores.

**git-remote**: É usado para gerenciar repositórios remotos. Permite adicionar, listar, renomear e remover repositórios remotos que estão conectados ao seu repositório local.

**git-repack**: Este comando é usado para compactar objetos não compactados em um repositório, o que pode melhorar o desempenho e economizar espaço.

**git-replace**: Permite criar, listar e excluir referências para substituir objetos em um repositório. Isso pode ser útil para corrigir problemas ou erros específicos no histórico do Git.

**COMANDOS INTERROGADORES**

*Esses comandos interrogadores fornecem informações específicas e realizam verificações relacionadas à revisão, ao histórico e à validade dos objetos no Git. Eles podem ser úteis para entender melhor o repositório, solucionar problemas ou verificar a autenticidade das alterações.*

**git-annotate**: Anota as linhas de um arquivo com informações do commit que as modificou.

**git-blame**: Mostra quem fez as últimas modificações em cada linha de um arquivo, indicando a revisão e o autor das mudanças.

**git-bugreport**: Ajuda a coletar informações para enviar um relatório de erro ao Git.

**git-count-objects**: Conta quantos objetos não compactados existem no repositório e quanto espaço eles ocupam em disco.

**git-difftool**: Mostra as diferenças entre versões de arquivos usando ferramentas tradicionais de comparação (diff).

**git-fsck**: Verifica se os objetos no banco de dados do Git estão conectados corretamente e são válidos.

**git-help**: Exibe informações de ajuda sobre o Git, oferecendo orientações sobre seu uso.

**git-instaweb**: Permite navegar instantaneamente em seu repositório de trabalho usando uma interface web chamada gitweb.

**git-merge-tree**: Mostra como a mesclagem de três maneiras seria feita sem fazer alterações no índice.

**git-rerere**: Reutiliza resoluções salvas para conflitos de mesclagem, economizando trabalho na resolução de conflitos semelhantes no futuro.

**git-show-branch**: Exibe informações sobre ramos e seus respectivos commits, facilitando a visualização da estrutura do repositório.

**git-verify-commit**: Verifica a assinatura GPG dos commits, garantindo a integridade e autenticidade dos commits.

**git-verify-tag**: Verifica a assinatura GPG das tags, garantindo a integridade e autenticidade das versões marcadas.

**git-whatchanged**: Mostra um registro de logs com as diferenças entre cada commit, facilitando o acompanhamento das mudanças ao longo do tempo.

**gitweb**: É uma interface web do Git que permite visualizar repositórios Git por meio de um navegador da web.

### **INTERAGINDO COM OS OUTROS**

*Estes comandos são para interagir com um SCM externo e com as outras pessoas através de patch por e-mail.*

**Comandos de Nível Superior:**

1. **`git-archimport`** - Importa um repositório GNU Arch no Git.
2. **`git-cvsexportcommit`** - Exporta um único commit para uma averiguação do CVS.
3. **`git-cvsimport`** - Recupera dados de outros sistemas de controle de versão.
4. **`git-cvsserver`** - Emula um servidor CVS para o Git.
5. **`git-imap-send`** - Envie patches por email para um servidor IMAP.
6. **`git-p4`** - Importa e envia para repositórios Perforce.
7. **`git-quiltimport`** - Aplica um conjunto de patches no ramo atual.
8. **`git-request-pull`** - Gera um resumo com as modificações pendentes.
9. **`git-send-email`** - Envia patches como e-mails.
10. **`git-svn`** - Integração entre repositórios do Subversion e Git.

**Redefina, Restaure e Reverta:**

Existem três comandos semelhantes com nomes diferentes:

1. **`git-revert`** - Cria um novo commit que desfaz as alterações de outros commits.
2. **`git-restore`** - Restaura arquivos na sua árvore de trabalho ou no índice sem afetar seu histórico de commits.
3. **`git-reset`** - Move o seu branch, adicionando ou removendo commits, o que modifica o histórico de commits. Pode ser usado para restaurar o índice.

**Comandos de Baixo Nível (Encanamento Plumbing):**

Esses comandos são usados principalmente por desenvolvedores de ferramentas que usam o Git. Eles manipulam objetos no repositório, índice e árvore de trabalho.

1. **`git-apply`** - Aplica um patch nos arquivos ou no índice.
2. **`git-checkout-index`** - Copia os arquivos do índice para a árvore de trabalho.
3. **`git-commit-graph`** - Escreve e verifica arquivos commit-graph do Git.
4. **`git-commit-tree`** - Cria um novo objeto de commit.
5. **`git-hash-object`** - Calcula o ID de um objeto a partir de um arquivo.
6. **`git-index-pack`** - Constrói um pacote de índice a partir de um arquivo de pacote existente.
7. **`git-merge-file`** - Realiza uma mesclagem de três vias em um arquivo.
8. **`git-merge-index`** - Realiza mesclagens em arquivos que precisam ser mesclados.
9. **`git-mktag`** - Cria um objeto de tag.
10. **`git-mktree`** - Cria uma árvore-objeto a partir de um arquivo de formato ls-tree.
11. **`git-multi-pack-index`** - Escreve e verifica vários índices de pacotes.
12. **`git-pack-objects`** - Cria um histórico empacotado de objetos.
13. **`git-prune-packed`** - Remove objetos extras de arquivos empacotados.
14. **`git-read-tree`** - Lê informações da árvore no índice.
15. **`git-symbolic-ref`** - Lê, modifica e exclui referências simbólicas.
16. **`git-unpack-objects`** - Desempacota objetos de um arquivo empacotado.
17. **`git-update-index`** - Registra o conteúdo de um arquivo na árvore de trabalho no índice.
18. **`git-update-ref`** - Atualiza o nome de um objeto armazenado de forma segura.
19. **`git-write-tree`** - Cria um objeto de árvore com base no índice atual.

**Comandos de Interrogação:**

Esses comandos fornecem informações sobre o repositório, objetos e referências sem afetar os arquivos da árvore de trabalho.

1. **`git-cat-file`** - Fornece informações sobre objetos no repositório.
2. **`git-cherry`** - Procura commits que ainda não foram aplicados ao "upstream".
3. **`git-diff-files`** - Compara arquivos na árvore de trabalho e no índice.
4. **`git-diff-index`** - Compara uma árvore com o diretório de trabalho ou o índice.
5. **`git-diff-tree`** - Compara o conteúdo e o modo de bolhas através de dois objetos de árvore.
6. **`git-for-each-ref`** - Fornece informações sobre cada "ref".
7. **`git-get-tar-commit-id`** - Extrai o ID de commit de um arquivo criado com o git-archive.
8. **`git-ls-files`** - Exibe informações sobre arquivos no índice e na árvore de trabalho.
9. **`git-ls-remote`** - Lista referências em um repositório remoto.
10. **`git-ls-tree`** - Lista o conteúdo de uma árvore de objetos.
11. **`git-merge-base`** - Localiza os melhores ancestrais para fazer uma mesclagem.
12. **`git-name-rev`** - Localiza nomes simbólicos para "revs" informados.
13. **`git-pack-redundant`** - Localiza arquivos "pack" redundantes.
14. **`git-rev-list`** - Lista objetos de commit em ordem cronológica reversa.
15. **`git-rev-parse`** - Escolhe e modela parâmetros.
16. **`git-show-index`** - Exibe o índice de um arquivo empacotado.
17. **`git-show-ref`** - Lista referências em um repositório local.
18. **`git-unpack-file`** - Cria um arquivo temporário com conteúdos de objetos.
19. **`git-var`** - Exibe variáveis locais para o Git.
20. **`git-verify-pack`** - Valida arquivos empacotados do Git.

**SERVIDORES GIT**

*Estes são comandos e ferramentas relacionados à sincronização e operações internas no Git. Geralmente, os usuários finais não precisam usá-los diretamente, pois eles são usados por comandos de alto nível do Git para manter a integridade e a funcionalidade dos repositórios.*

1. **`git-daemon`** - Um servidor simples para hospedar repositórios Git.
2. **`git-fetch-pack`** - Recebe objetos ausentes de outro repositório.
3. **`git-http-backend`** - Implementa o Git como servidor através do protocolo HTTP.
4. **`git-send-pack`** - Empurra objetos para outro repositório usando o protocolo Git.
5. **`git-update-server-info`** - Atualiza informações auxiliares para auxiliar servidores.

**Comandos Auxiliares de Sincronização:**

Esses comandos são usados internamente para realizar operações de sincronização, geralmente não são usados diretamente pelos usuários finais.

1. **`git-http-fetch`** - Faz o download de um repositório Git remoto via HTTP.
2. **`git-http-push`** - Empurra objetos via HTTP/DAV para outro repositório.
3. **`git-parse-remote`** - Ajuda na análise dos parâmetros de acesso a repositórios remotos.
4. **`git-receive-pack`** - Recebe objetos que são empurrados para o repositório.
5. **`git-shell`** - Fornece um shell de login restrito para acessar repositórios Git via SSH.
6. **`git-upload-archive`** - Envia um arquivo de volta ao git-archive.
7. **`git-upload-pack`** - Envia objetos compactados para o git-fetch-pack.

**Comandos Auxiliares Internos:**

Esses comandos são usados internamente por outros comandos e não são normalmente utilizados diretamente pelos usuários finais.

1. **`git-check-attr`** - Exibe informações dos atributos do Git.
2. **`git-check-ignore`** - Verifica regras de .gitignore e exclui arquivos correspondentes.
3. **`git-check-mailmap`** - Exibe informações canônicas de contatos em mensagens.
4. **`git-check-ref-format`** - Garante que um nome de referência esteja bem formatado.
5. **`git-column`** - Exibe dados em formato de coluna.
6. **`git-credential`** - Obtém e armazena credenciais de usuário.
7. **`git-credential-cache`** - Auxilia no armazenamento temporário de senhas na memória.
8. **`git-credential-store`** - Auxilia no armazenamento de credenciais no disco.
9. **`git-fmt-merge-msg`** - Gera mensagens de mesclagem de commits.
10. **`git-interpret-trailers`** - Adiciona ou analisa informações estruturadas em mensagens de commit.
11. **`git-mailinfo`** - Extrai remetentes e correções de mensagens de e-mail.
12. **`git-mailsplit`** - Divide arquivos mbox do UNIX em mensagens individuais.
13. **`git-merge-one-file`** - Assistente para mesclagem de arquivos individuais.
14. **`git-patch-id`** - Calcula um ID único para um patch.
15. **`git-sh-i18n`** - Configuração internacionalização do Git para scripts shell.
16. **`git-sh-setup`** - Configuração comum para scripts shell do Git.
17. **`git-stripspace`** - Remove espaços em branco desnecessários.

**Mecanismo de Configuração do Git:**

O Git utiliza arquivos de configuração em formato de texto simples para armazenar personalizações a nível de repositório e de usuário. Essas configurações podem incluir informações como nome de usuário e email.

**Exemplo de Arquivo de Configuração:**

[core]
filemode = false

[user]
name = "Nome do Usuário"
email = "[email@exemplo.com](mailto:email@exemplo.com)"

**Terminologia de Identificadores:**

- **`<objeto>`**: Representa o nome de um objeto genérico.
- **`<blob>`**: Refere-se a um objeto de tipo "blob" (conteúdo de arquivo).
- **`<árvore>`**: Refere-se a um objeto de tipo "árvore" (estrutura de diretórios).
- **`<commit>`**: Refere-se a um objeto de tipo "commit" (ponto de controle na história).
- **`<tree-ish>`**: Refere-se a uma árvore, nome de um commit ou tag.
- **`<commit-ish>`**: Refere-se a um nome de commit ou tag.
- **`<tipo>`**: Indica um tipo de objeto (blob, tree, commit ou tag).
- **`<arquivo>`**: Refere-se ao nome de um arquivo em relação à raiz da estrutura de árvore.

**Identificadores Simbólicos:**

- **`HEAD`**: Representa o cabeçalho do ramo atual.
- **`<tag>`**: Refere-se a uma tag válida.
- **`<head>`**: Refere-se a um nome de cabeçalho de ramo.

**Estrutura de Diretórios e Arquivos:**

*O documento gitrepository-layout fornece detalhes sobre a estrutura dos diretórios e arquivos em um repositório Git.*

**Variáveis de Ambiente:**

*Essas variáveis de ambiente são usadas para controlar o comportamento do Git e a localização de diferentes elementos em um repositório.*

- **`GIT_INDEX_FILE`**: Define um arquivo de índice alternativo.
- **`GIT_INDEX_VERSION`**: Especifica a versão do arquivo de índice para novos repositórios.
- **`GIT_OBJECT_DIRECTORY`**: Especifica o diretório de armazenamento de objetos Git.
- **`GIT_ALTERNATE_OBJECT_DIRECTORIES`**: Lista de diretórios de objetos compartilhados.
- **`GIT_DIR`**: Define o caminho do diretório do repositório Git.
- **`GIT_WORK_TREE`**: Define o caminho para a raiz da árvore de trabalho.
- **`GIT_NAMESPACE`**: Define o espaço de nomes no Git.
- **`GIT_CEILING_DIRECTORIES`**: Lista de diretórios onde o Git não deve mudar de diretório enquanto procura um diretório de repositório.
- **`GIT_DISCOVERY_ACROSS_FILESYSTEM`**: Controla se o Git cruza os limites do sistema de arquivos ao procurar um diretório de repositório.
- **`GIT_COMMON_DIR`**: Define o caminho de arquivos não relacionados à árvore de trabalho.
- **`GIT_DEFAULT_HASH`**: Especifica o algoritmo hash padrão para novos repositórios.

**Configuração de Commits no Git:**

*No Git, você pode personalizar informações relacionadas aos commits usando variáveis de ambiente. Aqui estão algumas delas:*

- **`GIT_AUTHOR_NAME`**: Define o nome legível do autor nos commits, substituindo as configurações **`user.name`** e **`author.name`**.
- **`GIT_AUTHOR_EMAIL`**: Define o endereço de email do autor nos commits, substituindo as configurações **`user.email`** e **`author.email`**.
- **`GIT_AUTHOR_DATE`**: Define a data usada para a identidade do autor ao criar commits e tags.
- **`GIT_COMMITTER_NAME`**: Define o nome legível do autor do commit, substituindo as configurações **`user.name`** e **`committer.name`**.
- **`GIT_COMMITTER_EMAIL`**: Define o endereço de email do autor nos commits, substituindo as configurações **`user.email`** e **`committer.email`**.
- **`GIT_COMMITTER_DATE`**: Define a data usada para a identidade de quem fez o commit.
- **`EMAIL`**: Define o endereço de email usado nas identidades do autor e do commit, se outras variáveis não estiverem definidas.

**Diffs no Git:**

*Essas variáveis de ambiente permitem personalizar o comportamento do Git relacionado aos commits e diffs, proporcionando controle sobre informações e opções de diferença.*

- **`GIT_DIFF_OPTS`**: Essa variável permite definir a opção **`-unified=??`** para especificar o número de linhas de contexto mostradas quando um diff unificado é criado. Isso substitui qualquer valor da opção **`U`** ou **`-unified`** passada na linha de comando do diff do Git.
- **`GIT_EXTERNAL_DIFF`**: Quando configurada, esta variável substitui o programa "diff" padrão. É chamada com sete parâmetros, incluindo informações sobre os arquivos antigos e novos, bem como seus modos. Para caminhos não mesclados, é chamada com um único parâmetro.
- **`GIT_DIFF_PATH_COUNTER`**: Uma variável que mantém um contador baseado em 1 para rastrear o número de caminhos.
- **`GIT_DIFF_PATH_TOTAL`**: Mantém o total de caminhos sendo processados.

**OUTROS**

Essas variáveis de ambiente têm funções específicas, mas vou tentar simplificar:

- **GIT_MERGE_VERBOSITY:** Controla o nível de informações mostradas pela estratégia de mesclagem recursiva no Git.
- **GIT_PAGER:** Define o paginador a ser usado para exibir a saída do Git, substituindo a variável $PAGER. Se definido como vazio ou "cat," o Git não inicia um paginador.
- **GIT_PROGRESS_DELAY:** Controla o atraso, em segundos, antes de mostrar indicadores de progresso opcionais. O valor padrão é 2 segundos.
- **GIT_EDITOR:** Define o editor a ser usado por comandos interativos no Git. Substitui as variáveis $EDITOR e $VISUAL.
- **GIT_SSH e GIT_SSH_COMMAND:** Substituem o comando SSH usado pelo Git para se conectar a sistemas remotos durante operações de fetch e push.
- **GIT_SSH_VARIANT:** Substitui a detecção automática do comando SSH quando o Git está configurado para usar o OpenSSH, plink ou tortoiseplink.
- **GIT_ASKPASS:** É usado por comandos Git que precisam de senhas ou frases secretas, como autenticação HTTP ou IMAP.
- **GIT_TERMINAL_PROMPT:** Define se o Git deve solicitar informações no terminal, útil para autenticação HTTP.
- **GIT_CONFIG_NOSYSTEM:** Ignora as configurações do arquivo de sistema do Git, garantindo um ambiente previsível.
- **GIT_FLUSH:** Controla a saída de comandos como git blame, git rev-list e git log. Quando definido como "1," a saída é descarregada após cada registro.
- **GIT_TRACE:** Ativa o rastreamento de mensagens para várias operações internas e externas do Git. É configurável para diferentes níveis de detalhe.
- **GIT_TRACE2 e outros:** São configurações relacionadas ao rastreamento de operações no Git com diferentes níveis de detalhamento. Geralmente usadas para fins de depuração e diagnóstico.
- **GIT_REDIRECT_STDIN, GIT_REDIRECT_STDOUT, GIT_REDIRECT_STDERR:** No Windows, permitem redirecionar os identificadores padrão de entrada/saída/erro para caminhos definidos por variáveis de ambiente.
