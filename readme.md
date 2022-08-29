## Universidad de San Carlos de Guatemala
## Facultad de Ingenieria
## Laboratorio de redes de computadoras 1
## Grupo 1

# Practica 1

<div align="center">

| Nombre  |  Carne |
| ------------: | ------------: |
| Bryan Eduardo Gonzalo Méndez Quevedo  | 201801528  |
| Angel Marcos David Lopez Chacon  | 201807299  |
| César Alejandro Sosa Enríquez  | 201800555  |
| Ricardo Fernandez  | 200611606  |

</div>

# TOPOLOGÍA 1

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/WhatsApp_Image_2022-08-28_at_9.39.52_PM__1__xqqqg_2v_.jpeg?ik-sdk-version=javascript-1.4.3&updatedAt=1661749688261](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/WhatsApp_Image_2022-08-28_at_9.39.52_PM__1__xqqqg_2v_.jpeg?ik-sdk-version=javascript-1.4.3&updatedAt=1661749688261)

## CONFIGURACIÓN DE SWITCHES

### CONFIGURACIÓN DE SWITCH SW4 (PUERTOS EN MODO ACCESO)

    #Configuración para puerto f1/3
    Conf t
    Int f1/3
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/4
    Conf t
    Int f1/4
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/5
    Conf t
    Int f1/5
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/6
    Conf t
    Int f1/6
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/7
    Conf t
    Int f1/7
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/8
    Conf t
    Int f1/8
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/9
    Conf t
    Int f1/9
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/10
    Conf t
    Int f1/10
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/11
    Conf t
    Int f1/11
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/12
    Conf t
    Int f1/12
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/13
    Conf t
    Int f1/13
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/14
    Conf t
    Int f1/14
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/15
    Conf t
    Int f1/15
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End


![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.16_vRStD_kJ5.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742521792](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.16_vRStD_kJ5.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742521792)

### CONFIGURACIÓN DE SWITCH SW4 (PUERTOS EN MODO TRONCAL)

    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/1
    Conf t
    Int f1/1
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/2
    Conf t
    Int f1/2
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.17_1_r4UzuXmqYa.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523215](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.17_1_r4UzuXmqYa.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523215)

### CONFIGURACIÓN DE SWITCH SW4 (VLAN)

    Conf t
    Vtp domain grupo1
    Vtp password contraseñadeldominio
    Vtp mode Client
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.18_2EWkIdP3z.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523007](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.18_2EWkIdP3z.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523007)



### CONFIGURACIÓN DE SWITCH SW5 (PUERTOS EN MODO ACCESO)

    #Configuración para puerto f1/1
    Conf t
    Int f1/1
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/6
    Conf t
    Int f1/6
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/7
    Conf t
    Int f1/7
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/8
    Conf t
    Int f1/8
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/9
    Conf t
    Int f1/9
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/10
    Conf t
    Int f1/10
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/11
    Conf t
    Int f1/11
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/12
    Conf t
    Int f1/12
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/13
    Conf t
    Int f1/13
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/14
    Conf t
    Int f1/14
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/15
    Conf t
    Int f1/15
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/3
    Conf t
    Int f1/3
    Switchport mode Access
    Switchport Access vlan 10
    Do wri
    End

    #Configuración para puerto f1/5
    Conf t
    Int f1/5
    Switchport mode Access
    Switchport Access vlan 10
    Do wri
    End
    
    #Configuración para puerto f1/4
    Conf t
    Int f1/4
    Switchport mode Access
    Switchport Access vlan 30
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.16_1_dLNjEVluI.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523013](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.16_1_dLNjEVluI.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523013)

### CONFIGURACIÓN DE SWITCH SW5 (PUERTOS EN MODO TRONCAL)

    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/2
    Conf t
    Int f1/2
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.17_2_k0F0HVjYQG.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742522845](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.17_2_k0F0HVjYQG.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742522845)

### CONFIGURACIÓN DE SWITCH SW5 (VLAN)

    Conf t
    Vtp domain grupo1
    Vtp password contraseñadeldominio
    Vtp mode Client
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.18_1_tW3C089Tl.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523037](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.18_1_tW3C089Tl.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523037)


### CONFIGURACIÓN DE SWITCH SW6 (PUERTOS EN MODO ACCESO)

    #Configuración para puerto f1/0
    Conf t
    Int f1/0
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/6
    Conf t
    Int f1/6
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/7
    Conf t
    Int f1/7
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/8
    Conf t
    Int f1/8
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/9
    Conf t
    Int f1/9
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/10
    Conf t
    Int f1/10
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/11
    Conf t
    Int f1/11
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/12
    Conf t
    Int f1/12
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/13
    Conf t
    Int f1/13
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/14
    Conf t
    Int f1/14
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/15
    Conf t
    Int f1/15
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/5
    Conf t
    Int f1/5
    Switchport mode Access
    Switchport Access vlan 20
    Do wri
    End

    #Configuración para puerto f1/3
    Conf t
    Int f1/3
    Switchport mode Access
    Switchport Access vlan 30
    Do wri
    End
    
    #Configuración para puerto f1/4
    Conf t
    Int f1/4
    Switchport mode Access
    Switchport Access vlan 40
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.17_FZpl381ez.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523174](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.17_FZpl381ez.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523174)


### CONFIGURACIÓN DE SWITCH SW6 (PUERTOS EN MODO TRONCAL)

    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/2
    Conf t
    Int f1/2
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.17_3_KFT-ZwZ3K.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523177](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.17_3_KFT-ZwZ3K.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742523177)

### CONFIGURACIÓN DE SWITCH SW6 (VLAN)

    Conf t
    Vtp domain grupo1
    Vtp password contraseñadeldominio
    Vtp mode Client
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.18_2_gB2-r46IQ.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742522932](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/BRYAN/unknown_2022.08.25-16.18_2_gB2-r46IQ.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742522932)

# TOPOLOGÍA #2

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/WhatsApp_Image_2022-08-28_at_9.33.43_PM__1__7laKmBwuG.jpeg?ik-sdk-version=javascript-1.4.3&updatedAt=1661749758018](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/WhatsApp_Image_2022-08-28_at_9.33.43_PM__1__7laKmBwuG.jpeg?ik-sdk-version=javascript-1.4.3&updatedAt=1661749758018)

## CONFIGURACIÓN DE SWITCH SW4 (PUERTOS EN MODO TRONCAL)

    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/2
    Conf t
    Int f1/2
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/interfaces_truncales_en_el_switch_4_Hkfrl7FDm.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688710](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/interfaces_truncales_en_el_switch_4_Hkfrl7FDm.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688710)

## CONFIGURACIÓN SWITCH SW4 (CONFIGURACIÓN COMO ROOT)
![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/Configuraci%C3%B3n_del_switch_4_como_root_primary_a_tods_las_vlan_V-Z49OYa4.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688990](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/Configuraci%C3%B3n_del_switch_4_como_root_primary_a_tods_las_vlan_V-Z49OYa4.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688990)


## CONFIGURACIÓN DE SWITCH SW5 (PUERTOS EN MODO TRONCAL)

    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/2
    Conf t
    Int f1/2
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/interfaces_truncales_en_el_switch_5_sD-LsVfrn.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688761](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/interfaces_truncales_en_el_switch_5_sD-LsVfrn.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688761)

## CONFIGURACIÓN DE SWITCH SW6 (PUERTOS EN MODO TRONCAL)
    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/1
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/2
    Conf t
    Int f1/2
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End
    
    #Configuración puerto f1/3
    Conf t
    Int f1/3
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/Interfaces_truncales_en_el_switch_6_2cEZxlOfN.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688864](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/Interfaces_truncales_en_el_switch_6_2cEZxlOfN.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688864)

## CONFIGURACIÓN DE SWITCH SW7 (PUERTOS EN MODO TRONCAL)
    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/1
    Conf t
    Int f1/1
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/2
    Conf t
    Int f1/2
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/interfaces_truncales_en_el_switch_7_yWcITETf_.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688790](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/interfaces_truncales_en_el_switch_7_yWcITETf_.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688790)


### CONFIGURACIÓN DE SWITCH SW7 (PUERTOS EN MODO ACCESO)

    #Configuración para puerto f1/3
    Conf t
    Int f1/3
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End
    
    #Configuración para puerto f1/4
    Conf t
    Int f1/4
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/5
    Conf t
    Int f1/5
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/6
    Conf t
    Int f1/6
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/7
    Conf t
    Int f1/7
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/8
    Conf t
    Int f1/8
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/9
    Conf t
    Int f1/9
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/10
    Conf t
    Int f1/10
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/11
    Conf t
    Int f1/11
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/12
    Conf t
    Int f1/12
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/13
    Conf t
    Int f1/13
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/15
    Conf t
    Int f1/15
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/14
    Conf t
    Int f1/14
    Switchport mode Access
    Switchport Access vlan 20
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/Configuracion_del_puerto_a_mode_acceso_del_sw7_a_la_pc9_informatica_odUUP3EDc.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688913](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/Configuracion_del_puerto_a_mode_acceso_del_sw7_a_la_pc9_informatica_odUUP3EDc.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688913)

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/Configuracion_de_las_vlans_nJxC2ZCED.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688904](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/ANGEL/Configuracion_de_las_vlans_nJxC2ZCED.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742688904)

# TOPOLOGÍA 3
### CONFIGURACIÓN DE SWITCH SW1 (PUERTOS EN MODO ACCESO)



    #Configuración para puerto f1/5
    Conf t
    Int f1/5
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/6
    Conf t
    Int f1/6
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/7
    Conf t
    Int f1/7
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/8
    Conf t
    Int f1/8
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/9
    Conf t
    Int f1/9
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/10
    Conf t
    Int f1/10
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/11
    Conf t
    Int f1/11
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/12
    Conf t
    Int f1/12
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/13
    Conf t
    Int f1/13
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/14
    Conf t
    Int f1/14
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/15
    Conf t
    Int f1/15
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/3
    Conf t
    Int f1/3
    Switchport mode Access
    Switchport Access vlan 30
    Do wri
    End

    #Configuración para puerto f1/4
    Conf t
    Int f1/4
    Switchport mode Access
    Switchport Access vlan 30
    Do wri
    End



![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw1-vlan-sw_qbQ4Fzv-_.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601127](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw1-vlan-sw_qbQ4Fzv-_.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601127)

## CONFIGURACIÓN DE SWITCH SW1 (PUERTOS EN MODO TRONCAL)
    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/1
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/2
    Conf t
    Int f1/2
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End
![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw1-status_b1GfW3MZK.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601234](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw1-status_b1GfW3MZK.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601234)

### CONFIGURACIÓN DE SWITCH SW1 (VLAN)

    Conf t
    Vtp domain grupo1
    Vtp password contraseñadeldominio
    Vtp mode Client
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw1-vtp-status_4H-zyeIr0.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601166](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw1-vtp-status_4H-zyeIr0.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601166)


### CONFIGURACIÓN DE SWITCH SW1 (PUERTOS EN MODO ACCESO)


    #Configuración para puerto f1/4
    Conf t
    Int f1/4
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/5
    Conf t
    Int f1/5
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/6
    Conf t
    Int f1/6
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/7
    Conf t
    Int f1/7
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/8
    Conf t
    Int f1/8
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/9
    Conf t
    Int f1/9
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/10
    Conf t
    Int f1/10
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/11
    Conf t
    Int f1/11
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/12
    Conf t
    Int f1/12
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/13
    Conf t
    Int f1/13
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/14
    Conf t
    Int f1/14
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/15
    Conf t
    Int f1/15
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/2
    Conf t
    Int f1/2
    Switchport mode Access
    Switchport Access vlan 10
    Do wri
    End

    #Configuración para puerto f1/3
    Conf t
    Int f1/3
    Switchport mode Access
    Switchport Access vlan 10
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw2-vlan-sw_g2CTUOUfv5.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601238](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw2-vlan-sw_g2CTUOUfv5.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601238)


## CONFIGURACIÓN DE SWITCH SW2 (PUERTOS EN MODO TRONCAL)
    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/1
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw-interfaces.status_KPIzkYw2I.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601178](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw-interfaces.status_KPIzkYw2I.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601178)

### CONFIGURACIÓN DE SWITCH SW2 (VLAN)

    Conf t
    Vtp domain grupo1
    Vtp password contraseñadeldominio
    Vtp mode Client
    Do wri
    End
    
![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw-vtp-status_kVCrTfwaL9.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601255](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw-vtp-status_kVCrTfwaL9.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601255)

### CONFIGURACIÓN DE SWITCH SW3 (PUERTOS EN MODO ACCESO)


    #Configuración para puerto f1/4
    Conf t
    Int f1/4
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/5
    Conf t
    Int f1/5
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/6
    Conf t
    Int f1/6
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/7
    Conf t
    Int f1/7
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/8
    Conf t
    Int f1/8
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/9
    Conf t
    Int f1/9
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/10
    Conf t
    Int f1/10
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/11
    Conf t
    Int f1/11
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/12
    Conf t
    Int f1/12
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/13
    Conf t
    Int f1/13
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/14
    Conf t
    Int f1/14
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/15
    Conf t
    Int f1/15
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/2
    Conf t
    Int f1/2
    Switchport mode Access
    Switchport Access vlan 40
    Do wri
    End

    #Configuración para puerto f1/3
    Conf t
    Int f1/3
    Switchport mode Access
    Switchport Access vlan 40
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw3-vlan-sw_93pzF8uJx7.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601235](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw3-vlan-sw_93pzF8uJx7.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601235)


## CONFIGURACIÓN DE SWITCH SW3 (PUERTOS EN MODO TRONCAL)
    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/1
    Conf t
    Int f1/1
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/s3-interface.status_LMPgLMlQg.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601199](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/s3-interface.status_LMPgLMlQg.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601199)

### CONFIGURACIÓN DE SWITCH SW3 (VLAN)

    Conf t
    Vtp domain grupo1
    Vtp password contraseñadeldominio
    Vtp mode Client
    Do wri
    End
![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw3-vtp-status_Qo11-oHym.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601195](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/sw3-vtp-status_Qo11-oHym.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601195)


### CONFIGURACIÓN DE SWITCH SW4 (PUERTOS EN MODO ACCESO)

    #Configuración para puerto f1/3
    Conf t
    Int f1/3
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/4
    Conf t
    Int f1/4
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/5
    Conf t
    Int f1/5
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/6
    Conf t
    Int f1/6
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/7
    Conf t
    Int f1/7
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/8
    Conf t
    Int f1/8
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/9
    Conf t
    Int f1/9
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/10
    Conf t
    Int f1/10
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/11
    Conf t
    Int f1/11
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/12
    Conf t
    Int f1/12
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/13
    Conf t
    Int f1/13
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/14
    Conf t
    Int f1/14
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/15
    Conf t
    Int f1/15
    Switchport mode Access
    Switchport Access vlan 1
    Do wri
    End

    #Configuración para puerto f1/2
    Conf t
    Int f1/2
    Switchport mode Access
    Switchport Access vlan 20
    Do wri
    End

![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/s4-vlan-sw_-WuYXJoXp.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601120](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/s4-vlan-sw_-WuYXJoXp.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601120)


## CONFIGURACIÓN DE SWITCH SW4 (PUERTOS EN MODO TRONCAL)
    #Configuración puerto f1/0
    Conf t
    Int f1/0
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End

    #Configuración puerto f1/1
    Conf t
    Int f1/1
    Switchport mode trunk
    Switchport trunk allowed vlan 1,10,20,30,40,1002-1005
    Do wri
    End
![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/s4-interfaces_ZlHCYezHod.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601308](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/s4-interfaces_ZlHCYezHod.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601308)



### CONFIGURACIÓN DE SWITCH SW4 (VLAN)

    Conf t
    Vtp domain grupo1
    Vtp password contraseñadeldominio
    Vtp mode Transparent
    Do wri
    End
![https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/s4-vtp-status_q64AGQHyhB.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601254](https://ik.imagekit.io/peu7i3asaiq/PROYECTO_REDES/RICARDO/s4-vtp-status_q64AGQHyhB.png?ik-sdk-version=javascript-1.4.3&updatedAt=1661742601254)