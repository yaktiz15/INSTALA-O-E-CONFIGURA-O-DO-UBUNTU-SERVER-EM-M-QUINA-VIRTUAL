# INSTALAR E CONFIGURA O UBUNTU SERVER EM MAQUINA VIRTUAL
Objetivo da Atividade

O objetivo desta atividade foi realizar a criação e configuração de uma máquina virtual utilizando o Oracle VM VirtualBox para instalação do sistema operacional Ubuntu Server LTS.
Durante a atividade foram executadas tarefas básicas de administração Linux, configuração inicial do sistema, instalação de pacotes e validação do serviço SSH.
A atividade permitiu compreender conceitos fundamentais relacionados à virtualização, administração de servidores Linux e infraestrutura de TI.

Criação da Máquina Virtual



Criação da VM no VirtualBox;
Nome da VM;
Configuração de RAM;
CPU;
Disco;
Rede;
Associação da ISO.
Nome da VM;
Configuração geral;
RAM;
CPU;
Disco;
Rede.
Idioma;
Teclado;
Rede;
Particionamento;
Usuário;
Hostname;
OpenSSH.

Durante a instalação foi selecionado o idioma Português.
O teclado foi configurado no padrão ABNT2.
O hostname definido foi “ubuntu-server”.
Também foi instalado o serviço OpenSSH Server para permitir acesso remoto.

Idioma;
Rede;
Disco;
Usuário;
Hostname;
OpenSSH;
Tela completa da VM.

<img width="1918" height="1078" alt="Captura de tela 2026-05-18 204358" src="https://github.com/user-attachments/assets/cec13b4d-18de-4804-80ac-06a0b3790904" />

<img width="1918" height="1078" alt="Captura de tela 2026-05-18 204436" src="https://github.com/user-attachments/assets/b74f4ead-0e40-40c4-83df-af1c47ca306d" />

<img width="1918" height="1075" alt="Captura de tela 2026-05-18 204633" src="https://github.com/user-attachments/assets/fd6397fb-65af-4934-b40a-7b933cd00fd2" />

<img width="1918" height="1075" alt="Captura de tela 2026-05-18 204653" src="https://github.com/user-attachments/assets/0e7baa7f-8eaf-47f3-b748-34025e6a5419" />

<img width="1918" height="1078" alt="Captura de tela 2026-05-18 204301" src="https://github.com/user-attachments/assets/fd15e142-dd25-4028-9c0a-74d49fa15e43" />

Primeiro Acesso ao Sistema

Executar e inserir prints dos comandos:

date
hostname
whoami
ip a
free -m
df -h
uptime
systemctl status ssh

<img width="1918" height="1078" alt="Captura de tela 2026-05-18 210501" src="https://github.com/user-attachments/assets/661d9830-afaa-4a38-bced-f980c695a009" />


<img width="1918" height="1077" alt="Captura de tela 2026-05-18 210523" src="https://github.com/user-attachments/assets/8029f368-0b48-4723-8690-adbc177b29b0" />

Explicação dos comandos
Comando	Função
date	Exibe data e hora
hostname	Mostra o nome do host
whoami	Mostra usuário atual
ip a	Exibe interfaces de rede
free -m	Mostra uso de memória
df -h	Mostra uso de disco
uptime	Tempo ligado e carga do sistema
systemctl status ssh	Status do serviço SSH

Atualização do Sistema

Executar:

sudo apt update
sudo apt upgrade

<img width="1918" height="1078" alt="Captura de tela 2026-05-18 210746" src="https://github.com/user-attachments/assets/9783f2ca-1aab-4d2c-99ac-5b4449384a4e" />








