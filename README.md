# uri-auto

<b>uri-auto</b> is a fork of TST-Auto, that was first a utility for use with <a 
href="https://github.com/daltonserey/tst">tst client</a> for 
the 
TST Online service, this fork allows using this tool with another languages and have a lot of 
new features.

## Usage

	Uso: uri-auto [.] [..] [./] [-l] [--sync] [-h]

	  --sync [on] [off]		Ativa ou desativa a sincronização automática com o Dropbox.
	  -l, --set-language [*]	Define uma lingugem padrão para todos os arquivos.
					[Python], [Java], [C], [C++]

	  ./			Executa a saída do último arquivo trabalhado.
 	  .			Executa os testes locais ou compila o arquivo no último diretório 
trabalhado.
	  ..			Executa o "commit" no último diretório trabalhado. (TST Online)


## Installation

First to install the uri-auto script, you will need <b>tst >= 0.5</b> installed. (Optional if you 
have a .bashrc)
So, to install tst run the following command:

    $ bash -c "$(curl -q -sSL http://bit.ly/tst-install)"
    
And then run the following command to finally install uri-auto.
    
    $ bash -c "$(curl -q -sSL 
https://raw.githubusercontent.com/felipemarinho97/uri-auto/master/uri-auto-install)"
    
## License

This software is licensed under the terms of the GPL v3.0 license. Please read the LICENSE file.

## Meta

@FelipeMarinho97 - felipevm97@gmail.com
