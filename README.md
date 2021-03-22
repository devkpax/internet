# Internet

SERVIÇO OFF LINE!!!!!  


Serviço baseado na camada de segurança DNS Bind9 rpz, drop total na World Wide Web, permite apenas sites autorizados, dashboard desenvolvido em Laravel 5.7 PHP 7.2 


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














 
