ModularHTML
===========

ModularHTML � um reposit�rio de c�digo para agilizar, aperfei�oar e padronizar a produ��o de p�ginas web.

Para contribuir --> https://github.com/a2comunicacao/ModularHTML


A Estrutura
-----------

**index.php**
Lista todos os m�dulos existentes seguindo algumas categorias:

* 1. Estrutura
* 2. Navega��o
* 3. Texto
* 4. Imagem
* 5. Widget
* 6. Listas
* 7. Modal
* 8. Formul�rio

**/modulos**
Pasta contendo todos os m�dulos existentes. Com o objetivo de manter a organiza��o e o correto funcionamento da listagem dos m�dulos, alguns padr�es precisam ser seguidos:

* Nomenclatura da pasta: (n�mero da categoria do m�dulo).(n�mero do m�dulo).(t�tulo-do-modulo-sem-espacos) --> 1.4.exemplo-de-modulo
* Sempre usar letras min�sculas e sem acentos;
* Ao inv�s de espa�os, usar h�fens.


**global.css**
Arquivo que cont�m as declara��es de estilo de todos os m�dulos. Do mesmo modo que a nomenclatura das pastas de m�dulos, o CSS precisa seguir alguns padr�es.

* O bloco de c�digo com as declara��es de estilo referentes ao m�dulo, deve ser envolvido por coment�rios contendo o mesmo nome atribu�do � pasta do m�dulo referente. Segue exemplo.

``` css
/*@1.4.exemplo-de-modulo*/
.classe { border:solid 1px blue; }
/*@1.4.exemplo-de-modulo*/
```