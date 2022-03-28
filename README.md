# Notas
# Questão 
. Crie um aplicativo para guardar anotações com a possibilidade de inclusão de uma foto, mas pensando, desde o início, nos elementos de segurança. Também serão acrescentadas as informações de localização no início do texto da anotação. Como o aplicativo deverá ser monetizado, será adotada uma estratégia baseada em anúncios, os quais serão removidos com a obtenção da versão Premium.

Segue em anexo arquivo .zip exportado da IDE Android Studio.

Funções do aplicativo:
- Salva anotações e imagens em forma criptografada SHA-1
- Faz login com e-mail por FirebaseAuth
- Listagem das anotações
- Botão de Logoff
- Mostra anúncio em banner
- Permite compras com Google Play Billing API para versão premium (remove o banner)
- Adiciona localização às anotações
- Gera dois arquivos: um para a anotações e outro para a imagem
