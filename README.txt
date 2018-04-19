%%%% VIRUS SCANNING PROJECT %%%%%


Este projeto tem o objetivo de simular um programa de antivírus.
A classe Componente_03_VirusScanningServer busca no diretório virusFolderToScan se algum dos arquivos são um vírus. 
Esta comparação é feita tomando como base os arquivos de vírus que estão dentro do diretório virusDB. 

Como configuração básica dos arquivos para testes temos que:
Os arquivos dummyfile6.bin e dummyfile7.bin são iguais (em conteúdo) 
e eles são tidos como sendo vírus pois têm a mesma assinatura do vírus dummyfile.bin que está no diretório virusDB.
Portanto, ao executar a classe VirusScanning.java o resultado será a detecção de dois arquivos como sendo vírus.


Você pode gerar mais vírus e mais arquivos a serem ecaneados usando o programa DummyFileGenerator.exe. 
Ps: escolha o tamanho dos arquivos de tamanho pequeno (alguns KB).