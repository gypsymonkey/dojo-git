Arquivo para auxilio do git

- init
    - Inicia o repositório

- config
    - Comando de configuração do git

- log
    - Mostra todo o histórico de commit do branch atual
    - log [hash1]..[hash2]
        - Mostra os commits entre os dois commits da duas hashs

- show 
    - Mostra todo o histórico de mudança de texto do último commit do branch atual
    - show [hash1]..[hash2]
        - Mostra a diferença entre os dois commits
- status
    - Mostra o estado do branch, tudo que foi adicionado, o que foi adicionado, arquivos deletados

- add
    - Adiciona arquivos a serem commitados

- rm
    - Remove arquivos a serem commitados

- reset
    - Defaz tudo que seria commitado
    - reset --hard
        - Muda a área de trabalho para o último commit local

- commit
    
    - commit -a ou commit -all
        - Automaticamente adiciona arquivos modificados ou deleta e dá commit

- diff
    - Mostra a diferença do commit passado com a área de trabalho

- branch
    - Mostra todas as branchs existentes
    - branch [nome]
        - Cria um novo branch com o nome "nome" 
    - branch -D [branch]
        - Deleta o branch [branch]

- checkout
    - checkout [branch]
        - Muda para uma branch existente

- rebase
    - Não é recomendado, muda a história do projeto
    - rebase [branch]
        - Usa o branch atual e aplica no [branch]

- merge 
    - merge [branch]
        - Usa o branch atual e mescla com o [branch]

- blame
    - blame [arquivo]
        - Mostra quem modificou o [arquivo] e em qual commit foi

- tag
    - Mostra todas as tag da branch
    - tag [nome]
        - Cria uma tag

- bisect 
    - Por exemplo, se um commit fez com que o projeto pare de compilar, então ele o ruim, se ele continua compilando, ele é bom
    - bisect [good/bad]
        - Diz que se o commit atual é bom ou ruim
        - bisect [good/bad] [commit]
        - diz se [commit] é bom ou ruim

