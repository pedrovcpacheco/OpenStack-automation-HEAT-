# OpenStack-automation-HEAT-
Script para automação de duas instâncias, dois volumes persistentes e dois floating IPS

#Parâmetro: user_data:

No parâmetro: user_data: chamar um shell script para automatizar o processo de particionamento/formatação e criação do File System desejado.

user_data:
get_file: http://host/script_heat_bd.sh  #Apontar aqui o host/scripts desejado.
