PoC rootedCON 2020 Compliance as Code (Auditoria de ZIRC0)
===================================================================

_Actualizado Marzo 2020!_

Este proyecto es una prueba de concepto para la rootedCON 2020 de como utilizar Ansible y OpenControl para realizar un auditoría automatizada mediante código. Para ello hacemos uso del framework Open Source [OpenControl](http://open-control.org/) y [Compliance-Masonry](https://github.com/opencontrol/compliance-masonry)

Scenario
--------

Zarancon es una ciudad ficticia donde en el ZIRCO (Zarancón Instituto Recursos Computacionales 0) necesitan certificar sus sistemas para que cumplan con el Esquema Nacional de Seguridad (ENS).

Para ello se tiene el estándar ENS en formato yaml con los controles de las diferentes certificaciones de nivel bajo, medio y alto.


### CPD Zirc0

El CPD ficticio de ZIRC0 se compone de diversos elementos pero para poder realizar la PoC se va pasar controles sobre VMs de CentOS 7 pero es ampliable a cualquier sistema o appliance que pueda conectarse Ansible.

Los controles (playbook de Ansible) se encuentran en la carpeta ens-ansible.

La carpeta de ens-zirc0 contiene todos los documentos para realizar la auditoría, como asimismo los comandos dentro del Makefile para la generación.


Autores
--------

Autores originales: https://github.com/orgs/opencontrol/people con licencia CC0
