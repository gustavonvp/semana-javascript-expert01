# Semana-javascript-expert01


Seja bem vindo(a) à primeira Semana Javascript Expert.

Para cada dia, o código fonte completo da aula será adicionado aqui


- [Aula 01](./aula01/jsexpert01-skeleton-ew)


## Dicas que apliquei ao utilizar este projeto

- Ao criar o SCRIPT .sh, certas variáveis de comando que rodam apenas em ambiente UNIX - LINUX , podem ser substituidas por comandos já existentes no WINDOWS.
- Exemplos: 'ls' do UNIX é 'dir' no WINDOWS.
            'grep' no UNIX é 'findstr' no WINDOWS.
            

- Caso queira utilizar os comandos nativos do UNIX, existem métodos paleativos para se utilizar no WINDOWS
- Exemplos: Utilizar o Perl, que permite construção de scripts BASH;
            Utilizar o GNUWIN32, que permite uso de comandos UNIX nativamente no windows, apenas criando as variáveis locais (no WINDOWS), com o path para o /bin do módulo que                 pode ser baixado na internet.
            Link de um módulo: http://gnuwin32.sourceforge.net/packages/sed.htm (Solução caso queira apenas alguns comandos do UNIX)
            Utilizar o pacote UNXUTILS --> http://unxutils.sourceforge.net/ (Solução mais simples)
            Utilizar o CYGWIN --> http://cygwin.com/   (Solução mais complexa)
            
- Para poder manipular os dados dos vídeos que estão no formato .MP4, Utilizar o MP4BOX para extrair dados do arquivo .MP4 (LINK: https://www.videohelp.com/software/MP4Box).         Necessário criação de variável local(WINDOWS)

- Para poder lidar com as propriedades do video, extraindo diferentes formatos (144p,360p,720p), utilizar a lib do FFMPEG, que permite configurar o CODEC, e seus rates e buffers,   e pode ser instalado via CHOCOLATEY, ou baixando na internet (binário) e configurar variável local para /bin do diretório do FFMPEG. Baixar também o FFPROBE que permite           vizualisar os dados do vídeo (arquivo) de maneira mais organizada, onde um humano possa ler tals dados e a maquina também possa entender certas 'STRINGS' contidas nos meta-dados   do arquivo .mp4



:muscle: :walking:
Criei a Branch MODIFICANDO para gerar commits de possíveis modificaçoes no projeto a qual apliquei FORK do criador deste, que é o Erick Wendel
