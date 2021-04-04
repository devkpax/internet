#  Serviço apenas para teste regras do web filter 


Simples e poderoso DNS layer Bind9 rpz, drop total World Wide Web, whitelist apenas sites autorizados. 

Gerenciamento de Internet centralizado em dispositivos remotos notebooks e celulares etc...   



 ========================================================================================================================================================================================

# Dashboard em Laravel 5.7 PHP 7.2 developer Paulo Asevedo 
# MANUAL DO USUÁRIO



 1 - Salve demo.rdp usando qualquer editor de texto com extensão .rdp 

 2 - Site bloqueados pornograficos, downloads, etc...  

 3 - Sites autorizados .gov.br, uol.com.br, terra.com.br estão permitidos.

 4 - Gerenciador acesse https://www.evencom.com.br com login e senha 

![image](https://user-images.githubusercontent.com/38859407/111921681-9ffe1380-8a74-11eb-82ba-35c5340a8ec4.png)
 


# Vá para Level1 


![image](https://user-images.githubusercontent.com/38859407/111920813-d2f1d880-8a6f-11eb-8d44-bf43c8d42a65.png)



# Regras; 

# Exemplo whitelist não use aspas:

Whitelist: *.exemplo.com CNAME rpz-passthru.

Whitelist: *exemplo.com CNAME rpz-passthru.

Whitelist: exemplo.com CNAME rpz-passthru.


![image](https://user-images.githubusercontent.com/38859407/113518973-eae15600-955f-11eb-871d-716522636632.png)



Exemplo whitelist errado ponto antes do domínio: .exemplo.com CNAME rpz-passthru.

Atenção nunca adicione ponto antes do domínio se você adicionar essa regra permitirá tudo, se fizer isso delete a regra!   

# Blacklist categorias de domínios (DPNs) com.br, .com, etc... 

![image](https://user-images.githubusercontent.com/38859407/113518913-9b9b2580-955f-11eb-9771-e0b952d506d0.png)


ATENÇÃO: Sites notícias como UOL, GLOBO, MSN, é necessário adicionar todos domínios que estão código do site! 

ATENÇÃO: Não adicione urls nem palavras chaves este web filter não é um proxy, trta-se de DNS DOMAIN NAME SYSTEM!  

Recursos da aplicação adiciona domínios faz pesquisa de domínios, paginação, delete domain   


![image](https://user-images.githubusercontent.com/38859407/111920983-ed788180-8a70-11eb-904e-485a79f3cfc2.png)





========================================================================================================================================================================================




Conheça a infraestrutura:  

Responsável pelo projeto Paulo Asevedo é autodidata web developer fullStack analista de redes infraestrutura computacionais.

Servidor físico notebook DELL i3 8GB RAM 
 


# VM Linux  

![image](https://user-images.githubusercontent.com/38859407/112075650-a87b4a80-8b57-11eb-9008-f4d7fe1d122a.png)
 




# VM Windows Server 2019 

![image](https://user-images.githubusercontent.com/38859407/112077149-9c44bc80-8b5a-11eb-9792-ba0a269144e1.png)










 
