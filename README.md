# EndianFirewall3.2_ContrabEditor
Addon Crontab Editor for Endian Firewall Community 3.2.x. 


Versão:
--------

v.1.0 ( Testados no Endian Firewall Community nas versões 3.2.1, 3.2.2 e 3.2.4).



Requerimentos/opcional:
--------
- Requer: Acesso ao seu Endian Firewall atraves do console (Conexão SSH).



Instalando o Pacote:
--------

Realizando Download:

    curl -Lo croneditor-endian3-1.0-1.x86_64.rpm https://github.com/brunoalmeida33/EndianFirewall3.2_ContrabEditor/raw/master/croneditor-endian3-1.0-1.x86_64.rpm
    
    
Executando a instalação:

    rpm -Uvh croneditor-endian3-1.0-1.x86_64.rpm
    

Removendo o pacote:
--------
- No console ssh digite:

    rpm -e croneditor-endian3
    
    
    
Outras informações:
------------------

- Esta instalação nao afeta o funcionamento dos relatorios nativo do Endian Firewall (SARG), não é necessario a remoção do mesmo.
- Para ativar este relatorio do lightsquid, é preciso selecionar a check box "Ativar Lightsquid" e clicar em "Salvar" no painel de controle do Endian, no menu  "Registros e relatorios" -> "Proxy" -> "Relatorio HTTP".
- Os relatorios serão gerados automaticamente a cada dia.

Espero ter ajudado.

Atenciosamente,

Bruno Almeida.
  
  
