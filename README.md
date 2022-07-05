# Adicionar alias no terminal

abra o terminal e digite:


> nano ~/.bashrc

no final do arquivo .bashrc, adicionar o seguinte:

``
obs: troque o nome renato para o seu nome de usuario do sistema operacional
``

> alias art="/home/renato/scripts/artisan"
> 
> alias tes="/home/renato/scripts/test"
> 
> alias dok="/home/renato/scripts/docker"
 
reinicie o terminal para que os alias sejam aplicados.

clone esse repositorio no diretorio /home/renato/ e execute o comando:

> mv /home/renato/short-scripts /home/renato/scripts
>
> chmod u+x /home/renato/scripts/ -R
