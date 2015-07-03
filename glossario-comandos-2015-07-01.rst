======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Juan Fernandes de Jesus
:Matrícula: 20121144010770
:Data: 01/07/2015

cat
  Descrição do comando: serve para criar um arquivo, ou exibi-lo | Ex: cat arquivo1.txt arquivo2.txt


cd
  Descrição do comando: serve pra mudar de diretório | Ex: cd /home/IFRN


cowsay
  Descrição do comando: serve pra mostrar uma vaquinha | Ex: cowsay


echo
  Descrição do comando: mostra uma mensagem | x = 7 // echo x


env
  Descrição do comando: serve pra imprimir uma lista das variáveis de ambiente atuais, ou para executar outro programa em um ambiente   personalizado


exit
  Descrição do comando: fecha um arquivo ou progama


help
  Descrição do comando: serve pra ajudar a informar algo sobre determinado comando


HISTTIMEFORMAT="%d/%m/%y"
  Descrição do comando: Lista os comandos feitos anteriormente com data e horário;


hostname
  Descrição do comando: diz o nome de meu pc


ifconfig
  Descrição do comando: serve pra configurar ou ver algo da interface da rede


last
  Descrição do comando: Mostra todas informações referente as entradas (login) e saídas (logout) de usuários do sistema;


lastb
  Descrição do comando: sessões que não deram certo de todos (mostra quem tentou logar na meu sistema);


ls
  Descrição do comando: lista os arquivos de uma pasta


mkdir
  Descrição do comando: cria um diretório


nome="fulano
  Descrição do comando: declarando uma variável;


passswd
  Descrição do comando: alter. senha


pwd
  Descrição do comando: mostra o diretório/pasta atual


set
  Descrição do comando


tree
  Descrição do comando: árvore é uma estrutura de dados hierárquica que organiza elementos de dados, chamados de nós, ligando-os com links, Essa estrutura é usada para ajudar a exibir grandes quantidades de informações em um formato fácil de ler;


tty
  Descrição do comando: Imprime o nome do terminal ligado ao seu padrão entrada. Ela imprime `no a tty 'se a entrada padrão não é um terminal;


vim
  Descrição do comando: serve pra abrir um arquivo como editor de texto;


wait
  Descrição do comando: Aguarda até a conclusão do trabalho e retorna status de saída. Faz com que um comando espere até que outro termine;


wall
  Descrição do comando: Escreve uma mensagem a outros usuários, Ex.: sudo wall message.txt (Usando o comando sudo para executar wall como super usuário, envia o conteúdo do message.txt a todos os usuários);


which
  Descrição do comando: Exibe o caminho completo na hierarquia de diretórios para os comandos do sistema, Ex.: which sh , which firefox;

                                                   while
  Descrição do comando: Um laço, executa comandos enquanto o teste seja bem-sucedido;


who
  Descrição do comando: quem está logado em tal máquina


whoami
  Descrição do comando: Nome do usuário associado com o atual efetivo ID do usuário;

write
  Descrição do comando: Envia mensagens para outros usuários, |Ex.: cowsay -f formatodavaca "Escreva aq a mensagem" | write nomedealguem ;
  
  cp Copia arquivos e diretórios, cp [opções] <arquivo_origem> <arquivo_destino>;

  mv Este comando move arquivos e diretórios, usado também para renomear um determinado arquivo, Ex.: mv nomearquivoantigo nomeartigonovo, mv foo ~/Desktop, $mv <arquivo_origem> <arquivo_destino>;

rm Remove arquivos e diretórios, Ex.: rm [opções] <arquivo>, Para apagar um diretório com todo seu conteúdo: rm -r /tmp/lixo;

find Procura por arquivos no diretório especificado, Ex.: procurar o arquivo nota.txt dentro do diretório /home/eitch: find /home/eitch -name nota.txt -print
