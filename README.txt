%%%% VIRUS SCANNING PROJECT %%%%%


Este projeto tem o objetivo de simular um programa de antiv�rus.
A classe Componente_03_VirusScanningServer busca no diret�rio virusFolderToScan se algum dos arquivos s�o um v�rus. 
Esta compara��o � feita tomando como base os arquivos de v�rus que est�o dentro do diret�rio virusDB. 

Como configura��o b�sica dos arquivos para testes temos que:
Os arquivos dummyfile6.bin e dummyfile7.bin s�o iguais (em conte�do) 
e eles s�o tidos como sendo v�rus pois t�m a mesma assinatura do v�rus dummyfile.bin que est� no diret�rio virusDB.
Portanto, ao executar a classe VirusScanning.java o resultado ser� a detec��o de dois arquivos como sendo v�rus.


Voc� pode gerar mais v�rus e mais arquivos a serem ecaneados usando o programa DummyFileGenerator.exe. 
Ps: escolha o tamanho dos arquivos de tamanho pequeno (alguns KB).