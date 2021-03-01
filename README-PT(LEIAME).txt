LEIA ME - Daturno
Versão 1.3
Data: Mar 1 2021

Conteúdo
1. Requerimentos do Sistema
2. Instalação e Desinstalação
2.1. Passos Para Instalar
2.2. Desinstalar
2.2.1. Como Deletar as Configs do Daturno
2.2.2. Resetar os Binds
2.2.3. Resetar a Mira
2.2.4. [Opcional] Restaurar Backup "autoexec.cfg"
2.2.5. [Opcional] Restaurar Backup "config.cfg"
2.2.6. [Opcional] Restaurar Backup da Mira
3. Verificar o Carregamento das CFGs
4. Notas da Instalação e CFGs
4.1. Notas dos "Passos Para Instalar"
4.2. Notas do Arquivo "daturno_autoexec.cfg"
4.3. Notas do Arquivo "daturno_config.cfg"
4.3.1. UBA
4.3.2. Q-Switch
4.3.3. Q-Drop
4.4. Notas do Arquivo "daturno_ch.cfg"
5. Configurações de Vídeo e Áudio
5.1. Desabilitar Desfocagem por Movimento ("Motion Blur")
5.2. Verificar Dispositivo de Áudio
5.3. Como Ativar Voz
6. Como Mudar as Teclas de Atalho do "In-Game Overlay"
7. Código de Amigo Steam do Daturno

-----------------------------------------------------------------------------------------------------------

1. Requerimentos do Sistema
- Processador com 6-núcleos
- Gráficos NVIDIA
- NVIDIA GeForce Experience (aplicativo) instalado
- Monitor de 60Hz (5ms)
- Velocidade de 240Mbps de download
- Velocidade de 90Mbps de upload
- Mouse óptico com 5 botões e rodinha
- DPI @ 3200

-----------------------------------------------------------------------------------------------------------

2. Instalação e Desinstalação
Antes de instalar as configurações do Daturno faça uma backup dos seus arquivos "autoexec.cfg", "config.cfg", atuais "opções de inicialização" e definições da mira. Guarde o seu backup dos arquivos mencionados em outra pasta/diretório.
Obs.: guarde as definições da sua mira em formato ".cfg".

2.1. Passos Para Instalar
Passo 1. Salve os arquivos "daturno_autoexec.cfg", "daturno_ch.cfg" e "daturno_config.cfg" na pasta "/cfg" no diretório do CS:GO
Passo 2. Abra a sua Biblioteca Steam
Passo 3. Vá para CS:GO >> Propriedades... >> GERAL
Passo 4. Copie a linha abaixo e cole em "OPÇÕES DE INICIALIZAÇÃO"

-novid -tickrate 64 -refresh 60 -freq 60 -nod3d9ex +exec daturno_autoexec

2.2. Desinstalar
Para desinstalar as configs do Daturno você precisa deletar os arquivos e resetar (ou sobrescrever) os binds e a mira.

2.2.1. Como Deletar as Configs do Daturno
Passo 1. Abra a sua Biblioteca Steam
Passo 2. Vá para CS:GO >> Propriedades... >> GERAL
Passo 3. Delete ou sobrescreva as "Opções de Inicialização". Tenha certeza de remover "+exec daturno_autoexec"
Passo 4. Na sua pasta "/cfg" no diretório do CS:GO, delete os arquivos "daturno_autoexec.cfg", "daturno_ch.cfg" e "daturno_config.cfg"

2.2.2. Resetar os Binds
Passo 1. Abra o CS:GO 
Passo 2. Menu de Definições >> Teclado / Rato >> REPOR

2.2.3. Resetar a Mira
Passo 1. Abra o CS:GO 
Passo 2. Menu de Definições >> Jogo >> Mira
Passo 3. Selecione "Repor" (ao lado de "Anular Alterações")

2.2.4. [Opcional] Restaurar Backup "autoexec.cfg"
Passo 1. Salve seu backup "autoexec.cfg" na pasta "/cfg" no diretório do CS:GO
Passo 2. Abra a sua Biblioteca Steam
Passo 3. Vá para CS:GO >> Propriedades... >> GERAL
Passo 4. Cole as suas "opções de inicialização" originais e inclua o código "+exec autoexec"

2.2.5. [Opcional] Restaurar Backup "config.cfg"
Passo 1. Salve seu backup "config.cfg" na pasta "/cfg" no diretório do CS:GO
Passo 2. Abra o CS:GO
Passo 3. Abra o console e escreva "exec config"
Passo 4. Aperte <Enter> para efetuar as mudanças

2.2.6. [Opcional] Restaurar Backup da Mira
Estes passos apenas funcionam se você fez o backup da mira em um arquivo ".cfg".
Passo 1. Salve seu backup "<nome-do-arquivo-da-mira>.cfg" na pasta "/cfg" no diretório do CS:GO
Passo 2. Abra o CS:GO
Passo 3. Abra o console e escreva "exec <nome-do-arquivo-da-mira>.cfg"
Passo 4. Aperte <Enter> para efetuar as mudanças

-----------------------------------------------------------------------------------------------------------

3. Verificar o Carregamento das CFGs
Passo 1. Abra o CS:GO
Passo 2. Abra o console e verifique as mensagens abaixo:

Loading daturno_autoexec.cfg... 
Loading daturno_ch.cfg... 
daturno_ch.cfg Loaded! 
Loading daturno_config.cfg... 
daturno_config.cfg Loaded! 
daturno_autoexec.cfg Loaded! 

-----------------------------------------------------------------------------------------------------------

4. Notas da Instalação e CFGs
Esta seção lida com o que está incluso nos arquivos.

4.1. Notas dos "Passos Para Instalar"
Remove o vídeo quando inicializa o CS:GO
Otimiza a frequência do monitor
Inicializa "daturno_autoexec.cfg"

4.2. Notas do Arquivo "daturno_autoexec.cfg"
Remove o teto de FPS
Otimiza as configurações de interpolação do cliente
Otimiza as transferências de pacotes para conexão utilizada
Otimiza a sincronização dos threads
Inicializa "daturno_ch.cfg"
Inicializa "daturno_config.cfg"

4.3. Notas do Arquivo "daturno_config.cfg"
Configura eDPI @ 1152
Configura comandos (binds) de mouse and keyboard
Comanda o botão "avançar" do mouse para utilizar o microfone
Comanda o botão "voltar" do mouse para ping de localização ("player_ping")
Recurso "Radio Binds Z, X, C, V."
Recurso "Utilities Bind Aliases [UBA]"
Recurso "Quickswitch [Q-Switch]"
Recurso "C4 Quickdrop [Q-Drop]"

4.3.1. UBA
Selecione utilitários com a rodinha do mouse. Pra cima seleciona utilitários de dano (Granada HE, Incendiária e Molotov). Pra baixo seleciona utilitários táticos (Flashbang, Granada de Fumo [Smoke] e Granada de Distração [Decoy]). Os comandos são sobrescrito conforme a ativação da rodinha então para selecionar um utilitário específico você talvez precise ativar a rodinha mais de uma vez.

4.3.2. Q-Switch
O uso principal do Q-Switch é para sair do zoom (scope). O comando está no click da rodinha ("MOUSE3"). Ele troca para faca quando ativado e depois para arma primária (se não tiver primária vai para secundária). É possivel "correr com a faca" se você segurar o click.

4.3.3. Q-Drop
Este recurso é para situações na qual você nasce ("spawn") e vai rushar pro bombsite sem comprometer a C4. Aperte a tecla "q" para dropar a C4 e mudar para faca. Mantenha a tecla pressionada para segurar a C4 e libere a tecla para fazer o drop mudando diretamente para faca.

4.4. Notas do Arquivo "daturno_ch.cfg"
Recurso mira estática vermelha em formato "+"

-----------------------------------------------------------------------------------------------------------

5. Configurações de Vídeo e Áudio
Otimize as configurações de vídeo para sua GPU NVIDIA usando o aplicativo NVIDIA GeForce Experience.
Passo 1. Abra o NVIDIA GeForce Experience
Passo 2. Na página principal, passe o mouse sobre CS:GO e clique em "DETALHES"
Passo 3. Clique no ícone da chave inglesa ("Configurações Personalizadas")
Passo 4. Otimize a barra deslizante
Obs.: Para aumentar FPS favoreça Performance. Para aumentar os detalhes favoreça Qualidade.

5.1. Desabilitar Desfocagem por Movimento ("Motion Blur")
Passo 1. Abra o CS:GO 
Passo 2. Menu de Definições >> Vídeo >> Vídeo (Avançado) >> Desfocagem por Movimento >> DESLIGADO

5.2. Verificar Dispositivo de Áudio
Passo 1. Abra o CS:GO 
Passo 2. Menu de Definições >> Áudio >> Áudio >> Dispositivo de Áudio >> [Selecione]

5.3. Como Ativar Voz
Passo 1. Abra o CS:GO 
Passo 2. Menu de Definições >> Áudio >> Áudio >> Dispositivo de Áudio >> PRESSIONAR PARA FALAR

-----------------------------------------------------------------------------------------------------------

6. Como Mudar as Teclas de Atalho do "In-Game Overlay"
Passo 1. Abra a Steam
Passo 2. Vá para Steam >> Configurações >> Em Jogo
Passo 3. Clique em "Teclas de Atalho do Painel"
Passo 4. Aperte a(s) tecla(s) que você gostaria comandar o atalho do painel
Obs.: "Control+Shift+Tab" funciona para mim.

-----------------------------------------------------------------------------------------------------------

7. Código de Amigo Steam do Daturno
1030594037
