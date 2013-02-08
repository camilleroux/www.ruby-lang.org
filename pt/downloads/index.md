---
layout: page
title: "Download Ruby"
lang: pt
---

Aqui pode receber as últimas distribuições de Ruby nos seus sabores
preferidos. A versão actual e estável é a {{ site.downloads.stable.version }}.
Por favor certifique-se de ler a [Licença Ruby][1].

### Código-Fonte do Ruby

Instalar pelo código fonte é uma boa solução para quando estiver
suficientemente confortável com a sua plataforma ou por ventura necessite de
configurações específicas para o seu ambiente. É eventualmente também uma boa
solução porque pode não haver pacotes pré-construídos para a sua plataforma.
 
* [Ruby {{ site.downloads.stable.version }}][2]
  (md5: {{ site.downloads.stable.md5 }})
  Versão estávelStable Version (*recomendada*)
* [Snapshot Estável][3] Ficheiros compactados em tar e gzip do último
  CVS estável. Deverá ser melhor que o última distribuição estável.
* [Snapshot Nocturno][4] Ficheiros compactados em tar e gzip do último
  CVS. Pode conter problemas por resolver.

Para informações sobre o repositório CVS de Ruby, veja a nossa página
[Ruby core](/pt/comunidade/nucleo-de-ruby/) .

### Ruby Em Windows

A plataforma Windows tem inúmeras opções para instalar o Ruby. A
primeira opção é simplesmente instalar o binário compilado. A segunda é
utilizar o “instalador rápido” (*one-click installer*). Se não tem a
certeza sobre como instalar o Ruby, o “instalador rápido” deverá ser a
melhor opção. ( Adicionalmente ao Ruby, o “instalador rápido” vem também
com um conjunto adicional de bibliotecas agregadas.)

* [Ruby 1.8.6-p398 RubyInstaller][6]
  (md5: 233d6b3ddc4c61436b075b51254cd138) Versão Estável
* [Ruby 1.8.7-p334 RubyInstaller][7] (md5: 
  64e30e63e16028282fcfe3ec57b561dc) Versão Estável (*recomendada*)
* [Ruby 1.9.1-p430 RubyInstaller][8]
  (md5: 86ac589a955898c3163b161d81750a05) Versão Estável
* [Ruby 1.9.2-p180 RubyInstaller][9] (md5: 
  2c94aef50987416d64c85a4ea0fa428b) Versão Estável (*recomendada*)
* [Ruby 1.8.7-p249 Binary][10] (md5: 4fd37b0b4b21a042cae7f5f0a8daad16)
  Versão Estável
* [Ruby 1.9.1-p378 Binary][11] (md5: 7d14a918cc8d243d3e2c409aff41f454)
  Versão Estável

Note que ao utilizar os binários acima indicados será necessário
descarregar e instalar manualmente componentes adicionais detalhados
nesta [página][12]. Por favor assegure-se que seguiu estes passos antes
de reportar um *bug*.

O [RubyInstaller][13] não precisa destas tarefas adicionais.

Investigue, também, a utilização do [pik][14] já que facilita o processo
de instalação e manutenção de versões concorrentes de ruby e gemas no
Windows.

### Ruby Em Linux

Dependendo da distribuição que está a utilizar, existem inúmeras
maneiras para instalar Ruby. A primeira opção é simplesmente fazer o
download do código fonte (em baixo) e compila-lo manualmente. No
entanto, em algumas plataformas, há gestores de pacotes que tornam a
instalação do Ruby extremamente fácil.

Por exemplo, o Debian ou Ubunto `apt-get` providenciam uma solução
simples e elegante:

    % sudo apt-get install ruby irb rdoc
{: .code .sh-code}

Para o irb e rdoc vamos necessitar de activar o repositório universal.

### Ruby em Mac OS X

Existem várias opções na plataforma Macintosh OS X para instalar a
última versão do Ruby. [Locomotive][15] é uma boa escolha se está à
procura de algo que o coloque a programar Rails rapidamente. Usar o
[MacPorts][16] ou [Fink][17] pode ser um pouco melhor para os técnicos
mais experientes.

No DarwinPorts, pode instalar o Ruby com…

    % port install ruby
{: .code .sh-code}

O Fink tem uma interface gráfica (utilizando o “Fink Commander”) para
instalar o Ruby.

Uma vez que o OS X é baseado em Unix, é possível também fazer download e
instalar pelo código-fonte, sendo assim uma solução simples e eficaz
como as outras.

Para uma vista detalhada sobre a instalação de Ruby (e Rails), Dan
Benjamin escreveu um excelente artigo – [*Building Ruby, Rails,
LightTPD, and MySQL on Tiger*][18] – e é ideal para começar a trabalhar
muito rapidamente.

\_Nota: Ruby 1.8.x juntamente com Rails deverá vir pré-instalado com a
seguinte distribuição do Mac OS X, Leopard (em beta neste momento).
([Mais informações aqui][19]) Felizmente, no momento em que o Leopard
arrancar, este irá “simplesmente funcionar” logo depois da instalação.\_

### RVM

Investigue, também, a utilização do [rvm][20], dado que agiliza o
processo de instalação e manutenção de versões concorrentes de ruby e
gemas. Este é o método preferido de muitos programadores de Ruby que
necessitam de testar as suas aplicações em ambientes diversos.



[1]: http://www.ruby-lang.org/en/about/license.txt 
[2]: {{ site.downloads.stable.url }}
[3]: {{ site.downloads.stable_snapshot.url }}
[4]: {{ site.downloads.nightly_snapshot.url }}
[6]: http://rubyforge.org/frs/download.php/71066/rubyinstaller-1.8.6-p398.exe 
[7]: http://rubyforge.org/frs/download.php/74293/rubyinstaller-1.8.7-p334.exe 
[8]: http://rubyforge.org/frs/download.php/72075/rubyinstaller-1.9.1-p430.exe 
[9]: http://rubyforge.org/frs/download.php/74298/rubyinstaller-1.9.2-p180.exe 
[10]: http://ftp.ruby-lang.org/pub/ruby/binaries/mswin32/ruby-1.8.7-p249-i386-mswin32.zip 
[11]: http://ftp.ruby-lang.org/pub/ruby/binaries/mswin32/ruby-1.9.1-p378-i386-mswin32.zip 
[12]: http://www.garbagecollect.jp/ruby/mswin32/en/documents/install.html 
[13]: http://rubyinstaller.org/ 
[14]: http://github.com/vertiginous/pik 
[15]: http://locomotive.raaum.org/ 
[16]: http://www.macports.org/ 
[17]: http://fink.sourceforge.net/ 
[18]: http://hivelogic.com/articles/2005/12/01/ruby_rails_lighttpd_mysql_tiger 
[19]: http://weblog.rubyonrails.org/2006/8/7/ruby-on-rails-will-ship-with-os-x-10-5-leopard 
[20]: https://rvm.beginrescueend.com/rvm 