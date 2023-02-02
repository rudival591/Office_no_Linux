                                   #### Office_no_Linux ####             

Baixe o crossover com o comando


git clone https://github.com/rudival591/Office_no_Linux.git

cd Office_no_Linux

Extrair os arquivos:

7z e install-crossover-21.1.0.bin.7z.001

Dar permissao no arquivo

chmod 777 install-crossover-21.1.0.bin

Executar a instalação do crossover

./install-crossover-21.1.0.bin

Agora e so copiar o arquivo para a pasta wine, conforme o comando abaixo

sudo cp winewrapper.exe.so /opt/cxoffice/lib/wine

Crossover Instalado agora e só restaurar o arquivo grafana do office

Baixar o office2013

https://github.com/rudival591/office2013grafana.git

Extrair os arquivos:

7z e Microsoft_Office_2013.cxarchive.7z.001

Agora e so restaurar no crossover

clicar em grafana

importar arquivo de grafana

selecione o office2013

Seja feliz...

![image](https://user-images.githubusercontent.com/37409284/216438178-05fa92df-79ef-4aac-8019-a9b7e8073faa.png)


