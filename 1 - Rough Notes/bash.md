Lista de coisas básicas

~ - home folder
$ - regular user
# - administrator

ls (list storage) - lista o armazenamento onde você está (commands have options, some of them are:

-a - shows everything 
-l - shows a long list with detailed information

)

pwd (present working directory) - dá todo o path de onde você está
cd (change directory) - muda o diretório atual (

    TAB - autocomplete
    .. - goes one level up
    cd - goes back to home
    ~ - goes back to home as well
    \ - space characters

)

pushd [diretório] - armazena o diretório que você estava antes
popd - volta ao diretório que foi armazenado
file - mostra especificações sobre um arquivo e sua extensão
locate - faz uma lista de todos os arquivos ou comandos com o nome que foi procurado
which - mostra se um comando está instalado ou não
history - mostra uma lista de todos os comandos que foram usados anteriormente
whatis - explica o que um comando faz
apropos [palavra] - faz uma lista inteira de todos os comandos relacionados a palavra procurada
man (manual) - abre um manual para o comando procurado

mkdir (make directory) - cria um(ns) diretório(s)
touch - atualiza a data de um arquivo se ele já existe; cria um(ns) arquivo(s)
cp (copy) [local do arquivo] {renomear} - copia arquivos para a pasta destino ou renomeia
mv (move) [local do arquivo] {renomear} - move arquivos para a pasta destino ou renomeia
rm (remove) - deleta um arquivo (

    -r - remove the directory and everything inside it

)

rmdir (remove directory) - deleta um diretório com nenhum arquivo dentro
cat (concatenate) - adiciona texto a um arquivo (

    > - adiciona o texto escrito e remove tudo o que tinha antes
    >> - adiciona o texto escrito sem remover nada

)

more - um pager que lê arquivos
less - lê arquivos, mas permite passar linha por linha de um arquivo
nano - editor de texto
sudo (super user do) - faz ações como administrator (

    -s - se torna o admnistrador

)

su - troca de usuário, se não for mencionado nenhum, troca para o usuário root
users - mostra os usuários logados
id - mostra informações sobre a conta
chmod (change mod) = muda as permissões de um arquivo (

    +x - makes a file executable
    XXX (user, group everyone) - use the number of bits to set the permissions

)

watch - roda um comando de novo a cada 2 segundos
free - mostra quanto de memória há no sistema
killall - encerra um processo
exit - fecha o terminal (ctrl d fecha o terminal também)

root (/) - base de um file system em um Linux
/home/ - onde todos os usuários tem os seus arquivos armazenados

- r (read) [4 bits]  w (write) [2 bits] x (execute) [1 bit] → - rwx

absolute path
relative path