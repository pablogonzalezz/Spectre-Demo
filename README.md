# Demonstração em um código C da falha Spectre

## Como rodar o código no Windows
1.  Abra o Prompt de Comando
2.  Para compilar, digite o comando: 
		
		> gcc spectre.c -o spectre

![Rodando o código no Prompt de Comando](https://github.com/pablogonzalezz/Spectre-Demo/blob/master/windows-spectre.png)
	OBS: O comando só funcionará se você estiver no diretório onde o código se encontra. Caso esteja nos downloads:
	
		> cd Downloads\pasta-que-contem-o-codigo
3. Para rodar o programa:
	
		> start spectre
## Como rodar o código no Linux
1. Abra o Terminal
2. Digite o seguinte comando:
		
		> $ gcc spectre.c -o spectre
Assim como no Windows, é necessário estar no diretório onde o arquivo "spectre.c" se encontra. (Veja o tópico sobre como rodar no Windows)

3. Para rodar o programa:
		
		> $ ./spectre
