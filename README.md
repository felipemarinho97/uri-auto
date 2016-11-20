# uri-auto

<b>uri-auto</b> is a fork of TST-Auto, that was first a utility for use with <a 
href="https://github.com/daltonserey/tst">tst client</a> for 
the 
TST Online service, this fork allows using this tool with another programming languages, don't need tst to be intalled, and have a lot of new features.

## Usage

	Uso: uri-auto [.] [..] [./] [-l] [-rm] [-h] [-v] [--sync] [--reset]

	  ./						Executa a saída do último arquivo trabalhado.
	  .							Executa os testes locais ou compila o arquivo no último diretório trabalhado.
	  ..						Executa o "commit" no último diretório trabalhado. (TST Online)
	  
	  --reset					Reseta as configurações e apaga o uri-auto.json.
	  --sync [on] [off]			Ativa ou desativa a sincronização automática com o Dropbox.
	  -l, --set-language [*]	Define uma lingugem padrão para todos os arquivos. [Python], [Java], [C], [C++]
	  -rm						Remove o último exercício criado.




## Installation

To install the uri-auto script, simply run the following command:
    
    $ bash -c "$(curl -q -sSL http://bit.ly/uri-auto-install)"
    
## License

This software is licensed under the terms of the GPL v3.0 license. Please read the LICENSE file.

## Meta

@FelipeMarinho97 - felipevm97@gmail.com
