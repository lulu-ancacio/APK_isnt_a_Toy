<h1 align="center">
<p>APK isn't a Toy</p>
<img src=https://user-images.githubusercontent.com/110111018/186804085-6c000c7d-9b33-458e-a921-ea672ecd63a5.png width=250px>
<br>
<img src=https://img.shields.io/github/license/lulu-ancacio/APK_isnt_a_Toy>
<img src=http://img.shields.io/static/v1?label=tipo&message=apk&color=rgb(220,20,60)&style=flat>
<img src=http://img.shields.io/static/v1?label=kodular&message=version%201.5%20Fenix&color=rgb(138,43,226)&style=flat>
</h1>

<h2>Sobre o aplicativo</h2>
<p>
APK isn't a Toy surgiu como uma ideia de madrugada, um aplicativo que após ser aberto no aparelho de alguém enviasse automaticamente as informações do aparelho do usuário ao Dev. No geral, o APK em sua versão final tem o objetivo de conscientizar o perigo da instalação de apks de desenvolvedores desconhecidos ou de fontes no mínimo suspeitas, como o nome já explicita: APK não é brinquedo!
<br>
O aplicativo foi feito utilizando as técnologias do Kodular, para o desenvolvimento do apk, e do Firebase, para envio, armazenamento e leitura de dados.
<br>
Este é o primeiro aplicativo que desenvolvo por completo sempre estar corrigindo-o.
</p>

<h2>Funcionalidades</h2>
<p>
Ao entrar no aplicativo ele pedirá a permissão de acesso ao armazenamento interno do celular e localização que, assim como os termos e condições de muitos sites e aplicativos, são aceitos sem hesitação. A tela inicial do apk exibe uma mensagem de "carregamento" infinita, presente somente para manter o usuário ativo por segundos suficientes para que seus dados sejam enviados para o Banco de Dados do Firebase (Firebase DB), cerca de 15 segundos.
<br>
<br>
<img src=https://user-images.githubusercontent.com/110111018/186818526-4b8075af-0626-4415-ad8e-3e51609293e1.gif width=450px>
<img src=https://user-images.githubusercontent.com/110111018/186823459-a97423ef-096d-4d13-87a6-5171842bc432.png width=1000px>
<br>
<br>
As informações extraídas do dispositivo são:
<ul>
<li>data e hora</li> 
<li>latitude</li>
<li>longitude</li>
<li>altitude</li>
<li>endereço atual</li>
<li>provedor de localização</li>
<li>SSID utilizado</li>
<li>versão android</li>
<li>número de compilação</li>
<li>código do país</li>
<li>fingerprint</li>
<li>hardware</li>
<li>fabricante</li>
<li>e mais</li>
</ul>
<br>
No total são 24 dados puxados do telefone e enviados para o Firebase BD. <strong>O APK isn't a Toy não puxa informações confidenciais como senhas de banco, nomes completos, e-mails e coisas do tipo.</strong>
<br>
Para checar manualmente quais são os dados puxados por completo, basta clicar no dado mais ou menos 15 segundos após abrir o app. Assim uma tela verde aparecerá mostrando os dados que foram checados e enviados... os seus dados.
<img src=https://user-images.githubusercontent.com/110111018/186824469-c0a5df2e-382c-45d3-9aa2-48098f0a5dd6.png width=300px>
</p>

<h2>Fazendo o seu próprio</h2>
<p>
em andamento para 26/08/22
</p>
