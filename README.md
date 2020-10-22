Redes de computadoras 1 "N"

Jose Carlos Bautista Mazariegos

Carnet: 201504231


# redes1_practica4

# **Enunciado**
Se le solicita configurar y administrar los dispositivos de una infraestructura de red para
una compañía la cual está empezando a crecer y quieren ampliar su red, un arquitecto
de redes les proporciona el diseño de la topología que será utilizada como
infraestructura de red para dicha compañía, pero deberán de configurarla para proveer
comunicación de acuerdo con las necesidades que se indican.

La compañía cuenta con 2 departamentos: Contabilidad y Ventas. Se debe proveer
comunicación entre los usuarios del mismo departamento, por ejemplo, los usuarios del
departamento de ventas no se podrán comunicar con ningún otro departamento
solamente con host de su mismo departamento. 


| **VLAN* | **Direccion de red** | **Primera dirección asignable** | **Ultima direccion asignable**|**Dirección de Breadcast** |
| --------|  --------------------| ------------------------------ | --------------------------     |---------------------------|
| 10      | 192.168.10.1         | 192.168.21.2                   | 192.168.21.254                 | 255.255.255.255           |
| 20      | 192.168.20.1         | 192.168.11.2                   | 192.168.11.254                 | 255.255.255.255           |

## ** Configuracion del modo truncal **
![1](https://user-images.githubusercontent.com/8570475/96743467-44bedc80-1381-11eb-9cea-f1bab1f41969.png)
## ** Configuracion del port channel **
![2](https://user-images.githubusercontent.com/8570475/96743519-530cf880-1381-11eb-8468-ecea4bbae302.png)
![3](https://user-images.githubusercontent.com/8570475/96743552-5b653380-1381-11eb-9379-dfb5441f983f.png)
## ** Definicion de la vlan y sus parametros **
![4](https://user-images.githubusercontent.com/8570475/96743594-661fc880-1381-11eb-9808-9e684cbdd674.png)
![5](https://user-images.githubusercontent.com/8570475/96743655-7768d500-1381-11eb-916f-a15c5abf2322.png)
![6](https://user-images.githubusercontent.com/8570475/96743698-7fc11000-1381-11eb-9cbd-391a43e2440a.png)
## ** Configuracion de la VLAN **
![7](https://user-images.githubusercontent.com/8570475/96743758-8e0f2c00-1381-11eb-9f0f-f0131af0d951.png)
![8](https://user-images.githubusercontent.com/8570475/96743803-98312a80-1381-11eb-8e57-f4d3209fe2f4.png)
![9](https://user-images.githubusercontent.com/8570475/96743859-a8490a00-1381-11eb-855c-103f3ba5dfdc.png)
## ** recorrido **
![recalcular](https://user-images.githubusercontent.com/8570475/96824246-897f5d80-13eb-11eb-87c6-5ee373bb47bf.png)



## ** Paquetes Wireshark **

![222](https://user-images.githubusercontent.com/8570475/96743313-180ac500-1381-11eb-86fd-a5fffe0e422a.png)
