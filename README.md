# EndianFirewall3.2_ContrabEditor
Addon Crontab Editor for Endian Firewall Community 3.2.x. 


Versão:
--------

v.1.0 ( Testado no Endian Firewall Community nas versões 3.2.1, 3.2.2 e 3.2.4).



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

- Para acessar o editor é necessario logar no painel de controle do Endian Firewall, ir no menu "Serviços" => "Editor do Crontab", adicione o agendamento no campo em branco e pressionar salvar.

Observações: O editar não suporta espaço entre as linhas (recomendo usar # para gerar estes espaços) e ao clicar em salvar o serviço do crontab é reiniciado automaticamente para salvar o novo agendamento.

Espero ter ajudado.

Atenciosamente,

Bruno Almeida.
  
  
