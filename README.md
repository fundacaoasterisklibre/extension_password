#Habilitando ramais com senha

##By:Israel Azevvedo


Vamos configurar umas regrinhas de ramais bloqueados com senhas que eu msm escrevi, é simples mais as vezes
temos uma certa dificuldade em vetar ramais em algumas situações e nesse tuto deverá te ajudar um pouco.

Primeiro temos aqui 4 arquivos no qual vc pod escolher como vc prefere trabalhar, com banco de dados ou em TXT.

Com Banco de Dados:

Coloque seus ramais a serem bloqueados no contexto "ramais", dentro do arquivo "ramais-senha-BD" contém as regras do extensions.conf que você irá usar. Você irá usar tbm o arquivo "RAMAIS.sql" que é o banco com a estrutura referente ao serviço, você pode subir ele via phpmyadmin ou linha de comando com o seguinte comando.

mysql -u root -p'senha-mysql' < RAMAIS.sql


Com TXT:

Coloque seus ramais a serem bloqueados no contexto "ramais", dentro do arquivo "ramais-senha-TXT" contém as regras do extensions.conf que você irá usar. Você irá usar tbm o arquivo "Layout_ramais-senha-TXT" como exemplo de como montar seu arquivo se senhas.