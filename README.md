# **Discord-Tutorial-V14-JS**
- Olá, seja bem vindo(a) ao tutorial de como iniciar sua aplicação de forma que todo DEV Discord.js faz.

# **Topics 🔥**
- Baixando/Instalando Recursos para produção da aplicação.
- Criando aplicação no Portal do Desenvolvedor.
- Configurando a Aplicação criada.
- Gerando Link para adicionar no servidor.
- Indo/Configurando para o Editor de Código.
- Criando o código fonte do bot.
- Baixando as pendencias necessárias.
- Deixando ele online.
- Testando comando padrão.
- Colocando alguns comandos.
# **Seção 1: Baixando/Instalando Recursos para produção da aplicação.**
1) Abra seu navegador padrão do seu aparelho e pesquise por [**Visual Studio Code**](https://code.visualstudio.com/download)
2) Após instalar, vamos baixar o [NodeJS](https://nodejs.org/en/download/) *(Indicamos na LTS)*
# **Seção 2: Criando aplicação no Portal do Desenvolvedor.**
1) Abra seu navegador, e acesse o [Painel Developer Portal](https://discord.com/developers/applications)
2) Após entrar no site, basta clicar em **New Application** ou **Nova Aplicação.**
4) Quando clicar no botão, basta você digitar o nome do Seu bot.
<img src="/ExemploApplication.png">

# **Seção 3: Configurando a Aplicação criada.**
1) Após criar sua aplicação, iremos configurar para que funcione perfeitamente.
2) No canto esquerdo da tela, você acesse o botão **Bot**
<img src="ExemploApplicationCriação.png">

3) Ative as **intents** do bot para que ele funcione. (Apenas desça um pouco na opção **Bot**)
<img src="ExemploApplicationIntents.png">

4) Depois, clique em **Reset Token** e copie o token gerado. *(Não compartilhe este token a ninguém!

# **Seção 4: Gerando Link para adicionar no servidor.**
1) Acesse o botão **OAuth2** e clique outra vez em **URL Generator**
2) Habilite as seguintes informações:
<img src="ExemploApplicationURL.png">
<img src="ExemploApplicationPERM.png">

3) E depois desça mais um pouco e você vai encontrar **GENERATED URL** e vai copiar e colar em outra página.
4) Depois de adicionado, vamos para a próxima seção.
# **Seção 5: Indo/Configurando para o Editor de Código.**
1) Após fizermos a aplicação, faça a instalação do Visual Studio Code normalmente.
2) Depois de fazer a instalação do Visual Studio Code, faça a instalação do NodeJS.
3) Após baixar tudo, você vai abrir o **Visual Studio Code** e esperar.
4) Depois de entrar, clique em **File** e depois em Open Folder.
<img src="ExemploApplicationVscode.png">

5) Crie uma pasta para você iniciar a configurações do bot.
6) Após criar e abrir ele, vamos para a próxima etapa.
# **Seção 6: Criando o código fonte do bot.**
1) Após abrir, você vai clicar para criar um arquivo e você digita: **index.js**
<img src="ExemploApplicationFile.png">

2) Depois de fazer isso, acesse o site [SourceBin - Code Base](https://pastebin.com/Aq0M0VUn)
3) Copie e cole na **index.js** e vamos para proxima étapa.
# **Seção 7: Baixando as pendencias necessárias.**
1) Abra o terminal: **CTRL + '** dentor do Visual Studio Code.
2) Digite as seguintes pendências: *(1 de cada vez)*
```sh
npm install discord.js@14.14.1
npm install djs-template-gen
npm init -y
```
3) Após fazer as instalações das pendências, execute o seguinte comando no terminal: *(1 de cada vez)*
```sh
clear
node index.js
```
4) Pronto sua aplicação já está criada. Vamos para o próximo passo.
# **Seção 8: Deixando ele online.**
1) Para conseguir deixar ele iniciado no Discord, procure o arquivo **config.json**.
2) Após achar o arquivo, vai ter a seguinte informação:
```json
{
    "token": "seu token"
}
```
3) Apague a mensagem **seu token** e cole o token quando fomos criar a aplicação.
