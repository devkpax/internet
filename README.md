#  Internet Security Based Bind9 rpz DNS layer ON LINE, apenas para fins de teste para filtragem de Internet!!! 

Filtro da web simples e poderoso camada de segurança DNS Bind9 rpz, drop total na World Wide Web, permite apenas sites autorizados. 


Se usado IP´s publicos para implementar essa infraestrutura, as mesmas regras de gerenciamento de Internet aplicadas aqui funcionaram qualquer dispositivo notebooks e  celulares remotos.   




========================================================================================================================================================================================




Conheça a infraestrutura 

Responsável pelo  projeto Paulo Asevedo desenvolvedor FullStack PHP Node.js Angular Analista de Redes Infraestrutura servidores

Servidor físico notebook DELL i3 8GB RAM 

![image](https://user-images.githubusercontent.com/38859407/112074254-ad8aca80-8b54-11eb-9ace-bfa8a460ba60.png)
 
 


# VM Linux  

![image](https://user-images.githubusercontent.com/38859407/112075650-a87b4a80-8b57-11eb-9008-f4d7fe1d122a.png)
 




# VM Windows Server 2019 

![image](https://user-images.githubusercontent.com/38859407/112077149-9c44bc80-8b5a-11eb-9792-ba0a269144e1.png)



 ========================================================================================================================================================================================

# Dashboard em Laravel 5.7 PHP 7.2 developer Paulo Asevedo 
# MANUAL DO USUÁRIO



 1 - Salve demo.rdp usando qualquer editor de texto com extensão .rdp 

 2 - Site bloqueados pornograficos, downloads, etc...  

 3 - Sites autorizados .gov.br, uol.com.br, terra.com.br estão permitidos.

 4 - Gerenciador acesse http://192.168.0.10 registre-se com login e senha 

![image](https://user-images.githubusercontent.com/38859407/111921681-9ffe1380-8a74-11eb-82ba-35c5340a8ec4.png)
 


# Vá para Level1 


![image](https://user-images.githubusercontent.com/38859407/111920813-d2f1d880-8a6f-11eb-8d44-bf43c8d42a65.png)



# Regras; 


# Exemplo permitir não use aspas:

1 - *.exemplo.com CNAME rpz-passthru.

2 - *exemplo.com CNAME rpz-passthru.

3 - exemplo.com CNAME rpz-passthru.


# Atenção este não use este exemplo ponto antes do domínimo: .exemplo.com.br rpz-passthru. se você adicionar irá liberar tudo, se fizer isso delete essa regra!   

# Bloqueio Categorias de domínios (DPNs) com.br, .com, etc... 

# Não use áspras: 

Exemplo correto bloqueio DPNs:  *.com CNAME .

Exemplo correto bloqueio DPNs: *com CNAME .

Exemplo correto bloqueio DPNs: com CNAME .

Exemplo bloquear domínio: *.domain.br CNAME .


# ATENÇÃO: Sites notícias como UOL, GLOBO, MSN, é necessário adicionar todos domínios que constam código na home do site! 


# ATENÇÃO: NÃO ADICIONE URLs NEM PALAVRAS CHAVES ESTE WEB FILTER NÃO É UM PROXY, TRATA-SE DE UM SISTEMA DNS DOMAIN NAME SYSTEM !  




# Recursos da aplicação adiciona domínios faz pesquisa de domínios, paginação, delete domain   


![image](https://user-images.githubusercontent.com/38859407/111920983-ed788180-8a70-11eb-904e-485a79f3cfc2.png)














 
