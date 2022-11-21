# Como distribuir o SharpBrowser com a sua própria marca

#### Passo 1: Clonar a fonte

Criar um clone Github do SharpBrowser usando [o nosso tutorial](Compilation.md).

#### Passo 2: Abrir o BrowserConfig.cs

Abrir o Solution explorer, e navegar para `Model > BrowserConfig.cs`.

![image](https://user-images.githubusercontent.com/104514709/183605344-97a50c0f-666a-4132-bf30-760525dc253e.png)

#### Passo 3: Editar as cordas de configuração
 
![image](https://user-images.githubusercontent.com/104514709/183605417-67f274b2-fe9d-47b7-9d4e-1722387d2fb8.png)

#### Passo 4: Compilar a aplicação

Certifique-se de que selecciona o modo `Release` e depois compila a aplicação utilizando o botão Build ou Start.

![image](https://user-images.githubusercontent.com/104514709/183605667-47ce966c-3167-4d34-9bd5-7feadf0710e5.png)

#### Passo 5: Criar um novo pacote de instalador
Para recriar o ficheiro de configuração, instalar [InnoSetup](https://jrsoftware.org/isinfo.php) e executar o script InnoSetup na pasta `setup`.

#### Passo 6: Partilhe o seu pacote de instalação
Partilhe o pacote instalador recém-gerado com os seus amigos!