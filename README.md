# KhalutzVoice

Texto, voz, arquivos, música e compartilhamento de tela para Windows.

[Baixar instalador 0.3.27](https://github.com/Sirpedrovic/KhalutzVoice/releases/download/v0.3.27/KhalutzVoice-Setup-0.3.27.exe) · [Versão portátil e notas](https://github.com/Sirpedrovic/KhalutzVoice/releases/tag/v0.3.27)

O primeiro ingresso exige o kit privado do seu grupo. As atualizações preservam o acesso e os dados locais.

## Versão 0.3.27

- A edição instalada corrige automaticamente o caminho usado para abrir o KhalutzVoice junto com o Windows.

## Versão 0.3.26

- **Khalutz Music**: `!p` começa a tocar na hora mesmo quando o bot estava pausado sem música (depois de ficar sem ouvintes ou de uma atualização). Antes a música ficava em "Preparando áudio…".
- **Forçar atualização de todos** alcança todo o servidor: quem estiver online atualiza na hora e quem estiver fora atualiza assim que se conectar.
- Ações do administrador agem na hora: mover, expulsar do canal, silenciar e ensurdecer não esperam a confirmação do participante, e apagar mensagens de outras pessoas e forçar a atualização não pedem confirmação. **Limpar canal** continua pedindo o nome do canal.

## Versão 0.3.25

- **Khalutz Music** não mostra mais o erro "EPERM: operation not permitted, rename" no Windows, que tirava a música da fila e travava o áudio de quem ouvia.
- Pôr música na fila não faz mais a música atual pular ou travar para quem está ouvindo.

## Versão 0.3.24

- **Khalutz Music** carrega as músicas mais rápido: o áudio vem em qualidade de até 80 kbps, quase metade do tamanho. Numa música de 5 minutos, o tempo até começar a tocar caiu cerca de 50% no teste.
- No painel de administração, **Forçar atualização de todos** desconecta os participantes online, instala a versão mais recente e reinicia o app de cada um. Vale para quem já estiver nesta versão.

## Versão 0.3.23

- **Khalutz Music** começa a tocar mais rápido: a busca e o download do áudio acontecem numa única etapa.
- O bot prepara antecipadamente até 5 músicas da fila. Ao pular ou terminar uma faixa, a próxima já está pronta e chega antes aos ouvintes.
- `!clear` limpa a fila e também a música atual. O bot continua no canal.
- O administrador vê quem é o DJ ao clicar no bot.
- Quem hospeda o bot precisa estar atualizado para as novidades valerem.

## Versão 0.3.22

- **Servidor de jogo** no canto inferior direito não depende mais do coordenador da sala. Quem abre o mundo em LAN informa a porta, clica em **Compartilhar servidor** e passa a coordenar o jogo. Os amigos clicam em **Conectar** e colam o endereço em Multijogador → Conexão direta. O anfitrião usa **Encerrar compartilhamento**.
- Um servidor por vez entre quem está conectado. Se dois grupos separados abrirem servidores, o painel mostra o conflito com os dois anfitriões quando voltarem a se conectar. Todos precisam desta versão para ver os servidores compartilhados.
- **Khalutz Music** aceita os comandos de qualquer participante no canal, inclusive `!clear`, quando o computador que hospeda o bot está atualizado.

## Versão 0.3.21

- No painel de administração, **Eleger coordenador** permite indicar um participante atualizado. A eleição depende da maioria dos votantes da sala.
- Texto legível no seletor de imagem e no botão de áudio do compartilhamento em tela cheia.
- **Sincronizar sala** busca mensagens, presença e fotos pelo botão abaixo dos canais.
- **Khalutz Music** aceita `!p nome` ou `!p link` pelo chat e toca somente áudio. Use `!help` para ver os comandos.
- Volume e mudo do compartilhamento disponíveis no player normal e em tela cheia.
- **Fechar Khalutz** recolhe a janela e remove o ícone da bandeja, mantendo a conexão em segundo plano. Use o atalho do Khalutz para reabrir.

A edição instalada verifica atualizações ao abrir e reinicia após instalar. A portátil avisa e abre a página de download.

[Releases anteriores](https://github.com/Sirpedrovic/KhalutzVoice/releases)
