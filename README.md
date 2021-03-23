#  Internet Security Based Bind9 rpz DNS layer SERVIÇO ON LINE!!!!! 
 
# Filtro da web simples e poderoso camada de segurança DNS Bind9 rpz, drop total na World Wide Web, permite apenas sites autorizados, dashboard desenvolvido em Laravel 5.7 PHP 7.2 


# Infraestrutura do projeto  

# Servidor físico notebook DELL i3 8GB RAM 

![image](https://user-images.githubusercontent.com/38859407/112074254-ad8aca80-8b54-11eb-9ace-bfa8a460ba60.png)
 
 


# VM Linux  

![image](https://user-images.githubusercontent.com/38859407/112075650-a87b4a80-8b57-11eb-9008-f4d7fe1d122a.png)
 




# VM Windows Server 2019 

![image](https://user-images.githubusercontent.com/38859407/112074614-749f2580-8b55-11eb-8021-b015fc8bbc77.png)
 



 


1 - Salve demo.rdp usando qualquer editor de texto com extensão .rdp 

2 - Site bloqueados pornograficos, downloads, etc...  

3 - Sites autorizados .gov.br, uol.com.br, terra.com.br estão permitidos.

4 - Gerenciador acesse http://192.168.0.10 registre-se com login e senha 

![image](https://user-images.githubusercontent.com/38859407/111921681-9ffe1380-8a74-11eb-82ba-35c5340a8ec4.png)
 


Vá para Level1 


![image](https://user-images.githubusercontent.com/38859407/111920813-d2f1d880-8a6f-11eb-8d44-bf43c8d42a65.png)



Regras; 

ATENÇÃO NUNCA ADICIONE ESTE EXEMPLO SÓ COM PONTO ANTES DO DOMÍNIO: (.exemplo.com.br rpz-passthru.) se você adicionar irá permitir tudo! Então se fizer isto delete está regra!   

Exemplo permitir: *.exemplo.com CNAME rpz-passthru.

Exemplo permitir: *exemplo.com CNAME rpz-passthru.

Exemplo permitir: exemplo.com CNAME rpz-passthru.




BLoqueio Categorias de domínios (DPNs) com.br, .com, etc... 

Exemplo para bloquear (DPNs): *.com CNAME .

Exemplo bloquear por domínio: *.domain.br CNAME .




ATENÇÃO: Sites notícias como UOL, GLOBO, MSN, é necessário adicionar todos domínios que constam código na home do site! 


ATENÇÃO: NÃO ADICIONE URLs NEM PALAVRAS CHAVES ESTE WEB FILTER NÃO É UM PROXY, TRATA-SE DE UM SISTEMA DNS DOMAIN NAME SYSTEM !  







Pesquisa de domínios, paginação, delete  


![image](https://user-images.githubusercontent.com/38859407/111920983-ed788180-8a70-11eb-904e-485a79f3cfc2.png)














 
