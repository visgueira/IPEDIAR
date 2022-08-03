# IPEDIAR

Aplicativo que serve como interface gráfica de usuário (GUI) para uso de recursos do [**IPED**](https://github.com/lfcnassif/IPED/releases) 🔎 em evidências digitais apreendidas por agentes públicos em investigações e também por entidades e/ou órgãos de fiscalização e controle em repositórios de documentos digitais corporativos ou conjuntos de dados das equipes de trabalho atuando como um indexador de temas segmentados.

Atualmente se encontra na versão 4.0, compatível com o IPED a partir das versões do 4.0.0.

# Requisitos

Para o funcionamento do IPED e do IPEDIAR, o [**Java 11 versão 64 bits**](https://www.oracle.com/java/technologies/downloads/#java11) precisa estar instalado e em funcionamento no dispositivo que irá realizar a indexação, o que pode ser facilmente verificado digitando   **_`java -version`_**  no prompt de comando (CMD ou Bash). O resultado esperado é que sejam exibidos os dados da versão do Java em execução com a informação **64-Bit**, caso esse dado não apareça o Java 64 bits não está em execução nesse dispositivo.

<img width="500" alt="image" src="https://user-images.githubusercontent.com/5096974/179482470-68b6b521-745b-4d24-861b-68cca9c34e84.png">

Já, especificamente com relação  ao **IPEDIAR**, o requisito básico é que este precisar estar "**na mesma pasta**" do executável do IPED conforme a figura abaixo.

Por fim, em razão de requisitos de segurança, e ainda atendendo recomendações do próprio desenvolvedor do Sistema Operacional (Microsoft), este aplicativo foi desenvolvido de forma que **não é executado no Windows 7**, vez que o próprio fabricante não presta mais suporte a referida versão. 


<img width="500" alt="image" src="https://user-images.githubusercontent.com/5096974/179485111-349e8658-5474-4458-952a-f3d102b65c9e.png">

# Tela Inicial
A tela inicial do IPEDIAR é composta de **botões** e **menus** que facilitam a execução do IPED, conforme imagem abaixo.

<img width="426" alt="image" src="https://user-images.githubusercontent.com/5096974/179491552-dcebe8cd-4149-45f2-a223-637ce981437f.png"> 

# Como usar o IPEDIAR?

Tendo sido atendidos todos os requisitos acima mencionados, navegue até a pasta do IPED e dê duplo clique no arquivo **IPEDIAR.exe**, feito isso aguarde a tela inicial aparecer e clique no botão origem para indicar a pasta que contem os dados que serão processados e indexados pelo IPED.

<img width="426" alt="image" src="https://user-images.githubusercontent.com/5096974/179518224-247ee851-dc42-4221-a098-acdb1254d297.png">

Irá aparecer um tela semelhante a essa 👇 devendo ao usuário somente escolher a pasta e clicar no botão "Selecionar pasta".

<img width="426" alt="image" src="https://user-images.githubusercontent.com/5096974/179576593-03562c37-c683-45e8-9af0-de5fab6c463b.png">  

Após isso, o caminho da pasta ORIGEM será exibido ao lado do botão ORIGEM.

<img width="426" alt="image" src="https://user-images.githubusercontent.com/5096974/179591882-7f7d77a7-6cc1-48f9-ad13-e03ffc7b2a45.png">

O mesmo procedimento deve ser adotado para a pasta DESTINO...

<img width="426" alt="image" src="https://user-images.githubusercontent.com/5096974/179584177-31044bff-a6f7-4956-966d-5fa8a9c5faea.png">


<img width="426" alt="image" src="https://user-images.githubusercontent.com/5096974/179594658-5ffca14a-f424-40ba-8fa3-0709c9d56e10.png">

Com os dados das pastas de ORIGEM e DESTINO preenchidos resta agora clicar no botão INDEXAR. Ao final do processamento e indexação, o resultado estará disponível na pasta de DESTINO.

<img width="426" alt="image" src="https://user-images.githubusercontent.com/5096974/179599793-f4988066-679d-4f60-8f5f-8279bf2c9862.png">

