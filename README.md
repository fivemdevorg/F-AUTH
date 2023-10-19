F-AUTH -- https://fivemdev.org/store/category/5-fivemdev-auth/

O F-AUTH é um sistema inovador para proteger os arquivos da sua cidade no FIVEM!

Com ele, você pode encriptar os seus scripts e armazená-los na nuvem, garantindo mais praticidade e segurança para o seu servidor.

Veja como funciona:

Suponha que você tenha um script chamado WALL, que hoje está na sua resource: start wall no seu cfg. Com o F-AUTH, você não precisa ter esse arquivo na sua base, pois ele vai estar na nuvem, através do GITHUB. Você só precisa criar um repositório oculto com o nome do seu script, gerar uma token desse repositório e informar na compra a sua token do Github. O nosso site, por sua vez, vai te fornecer uma chave exclusiva, atrelada à sua token e ao seu IP (da VPS). Assim, você terá três camadas de segurança: token, chave e IP.

Depois, você deve ir no seu arquivo CONFIG.LUA e preencher o seguinte:

Config = {}

Config.key = “” – A chave gerada no nosso site

Config.profile = “” – A URL do seu repositório no Github no formato RAW. Exemplo: https://raw.githubusercontent.com/fivemdevorg/

Lembre-se de que é obrigatório usar esse formato com RAW, terminando no nome do seu usuário. Em seguida, você deve ir no diretório do seu Github, criar uma pasta com o nome da sua resource. Se o nome do script é wall, então crie uma pasta “wall”. Se ele tiver o W maiúsculo, então é Wall. A pasta criada deve ter o mesmo nome do script. Por fim, você deve gerar a token dessa pasta e colocar em nosso site, no processo da compra. Assim, você conseguirá coletar a sua chave. O processo é todo automático e depende só de você.

Outro detalhe é a escolha do client, se o seu script tem apenas server.lua você utiliza o arquivo server.lua e o restante, se o seu script utiliza server.lua e cliente, utilize o arquivo: server_AND_CLIENT.lua e também o client.lua obviamente.

Para suporte: https://fivemdev.org/ Oferecemos a instalação do serviço caso seja necessário.

Não perca tempo e adquira já o F-AUTH, o sistema mais confiável e eficiente para proteger os seus arquivos no FIVEM!

Atenciosamente, Hideki
