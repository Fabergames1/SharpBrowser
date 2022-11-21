![SharpBrowser](https://github.com/sharpbrowser/SharpBrowser/raw/master/images/logo3.png)

SharpBrowser é o browser C# de código aberto mais rápido que existe! Ligeiramente mais rápido que o Google Chrome ao renderizar páginas web devido ao leve renderizador CEF. Comparámos todos os motores de navegação .NET disponíveis e, finalmente, estabelecemos o elevado desempenho [CefSharp](https://github.com/cefsharp/CefSharp/). Lançado sob a licença MIT

## Características

- HTML5, CSS3, JS, HTML5 Vídeo, WebGL 3D, WebAssembly, etc
- Navegação com separadores
- Barra de endereços (também abre no Google)
- Voltar, Avançar, Parar, Actualizar
- Ferramentas de desenvolvimento
- Barra de pesquisa (também destaca todas as instâncias)
- Gestor de descarregamento
- Páginas de erro personalizadas
- Menu de contexto personalizado
- Adicionar facilmente marcas, botões ou hotkeys específicos do fornecedor
- Ver páginas web online e offline

## Teclas de atalho

Teclas de atalho | Função
------------ | -------------
Ctrl+T | Adicionar um novo separador
Ctrl+N | Adicionar uma nova janela
Ctrl+W | Fechar separador activo
F5 | Actualizar separador activo
F12 | Ferramentas de revelação abertas
Ctrl+Tab | Mude para o separador seguinte
Ctrl+Shift+Tab | Mude para o separador anterior
Ctrl+F | Abrir barra de pesquisa (Entre para encontrar a seguir, Esc para fechar)


## Requisitos do sistema

- Precisa de [VC++ 2019 Runtime](https://aka.ms/vs/17/release/vc_redist.x64.exe) versões 32-bit e 64-bit

- Precisa de .NET 6.

- Necessita de instalar a versão do VC++ Runtime que o CEFSharp necessita. Uma vez que estamos a utilizar o CefSharp 106, de acordo com [isto](https://github.com/cefsharp/CefSharp/#release-branches), precisamos das versões acima


## Começando

- Ver o [Guia de Compilação](docs/Compilation.md) para passos a dar para começar.


## Documentação

- [Guia do Utilizador](docs/Users.md)
- [Guia de Compilação](docs/Compilation.md)
- [Guia de Configuração](docs/Configuration.md)
- [Guia de Distribuição](docs/Distribution.md)


## Código

- SharpBrowser utiliza o CefSharp 106 e é construído em NET 6
- SharpBrowser suporta AnyCPU, bem como construções específicas x86/x64
- MainForm.cs' - principal interface do navegador web e funcionalidades relacionadas
- "Manipuladores" - vários manipuladores que registámos na CefSharp que permitem uma integração mais profunda entre nós e a CefSharp
- `Data/JSON.cs` - rápido JSON serializador/deserializador
- Os binários estão incluídos na pasta "bin" devido à complexa configuração CefSharp necessária. Não esvaziar esta pasta.
- `bin/storage` - HTML e JS necessários para o gestor de downloads e páginas de erro personalizadas.

## Créditos

- [Robin Rodricks](https://github.com/robinrodricks) - Projecto SharpBrowser.
- [Alex Maitland](https://github.com/amaitland) - Projecto CefSharp, invólucro para o navegador incorporado CEF.
- [Ahmet Uzun](https://github.com/postacik) - Projecto original de navegador.

## Capturas de ecrã

### Apple.com

![](https://github.com/sharpbrowser/SharpBrowser/raw/master/images/1.png)

### WebAssembly & WebGL

![](https://github.com/sharpbrowser/SharpBrowser/raw/master/images/5.png)

### YouTube

![](https://github.com/sharpbrowser/SharpBrowser/raw/master/images/6.png)

### Google Maps

![](https://github.com/sharpbrowser/SharpBrowser/raw/master/images/2.png)

### Barra de Pesquisa

![](https://github.com/sharpbrowser/SharpBrowser/raw/master/images/search.png)

### Separador Downloads

![](https://github.com/sharpbrowser/SharpBrowser/raw/master/images/3.png)

### Ferramentas de desenvolvimento

![](https://github.com/sharpbrowser/SharpBrowser/raw/master/images/4.png)

### Páginas de erro personalizadas

![](https://github.com/sharpbrowser/SharpBrowser/raw/master/images/error1.png)

![](https://github.com/sharpbrowser/SharpBrowser/raw/master/images/error2.png)

Projeto não desenvolvido por mim, mas desenvolvido pelo github abaixo

https://github.com/sharpbrowser/SharpBrowser

Modificações feitas por mim: Release do executavel
                             Tradução do Readme para o português brasileiro!