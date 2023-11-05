# UnbelievaBoat-en-BDFD

¡Hola! soy el creador de estos codigos xquab pertenesco al equipo de [The BDS Word](https://discord.gg/dru9uRYKqq). Sigue las indicaciones para poder usar el codigo ten en cuenta que si no sabes como funciona el codigo no desordenes nada o lo romperas.

Posdata: Si quieres codigos y guias unete al servidor **servidor**. Tambien podras estar al tanto de novedades de proyectos mas adelante.
Link: https://discord.gg/dru9uRYKqq

### Algunos canales con los que contamos.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/48c08513-60a8-4b1a-ba40-01fec23548ba) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/cdfd37cb-644b-45d9-b2c7-efa3c973d10f) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/ea18e114-b14e-40f9-94d3-7cf16a932f75) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/0e7a6b43-0855-4737-af73-cc668f48f102) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/00c86bed-9cd5-471c-8065-9c73514e9792)





## Guia tutorial

### Variables Necesarias.

Crealas tal y como esta, cada valor de variable es unico y necesario al igual que el nombre.

|    Nombre     |  Valor  | 
| --------------| ------- | 
| item          |   {}    |
| descripcion   |   {}    |
| requerido     |   {}    |
| dar           |   {}    |
| quitar        |   {}    |
| balance       |   {}    |
| contador      |   {}    |
| valor         |   {}    |
| stock         |   {}    |
| reply         |   {}    |
| currency      | :emoji: |
| role-collect  |   {}    |
| count-collect |   {}    |

__Importante__: Debes tener dos variables para complementar este codigo que seria tu "dinero" "banco" en economia.

## Avanzes del resultado

### Crear-item
Crea los nombre de los items pero no mayor a 30 caracteress esto esta balanceado para usuarios premium y no premium sobre el limite de caracteres en las variables, __tambien que cada espacio que use sera remplazado por "_"__. tenga en cuenta esto.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/3266ff80-de49-4d03-9485-e98dbe47ffbb)

### Edit-item
Edita el item ya creado puedes usar el nombre del item dentro de doble comillas.
Ejemplo: `"item_name"`

__Opciones disponibles:__
- name, price, value, description,stock, role-required , role-give, role-removed, required-balance, reply.

__Reply - Tags:__
- `{member.id}`, `{member.username}`, `{member.tag}`, `{member.mention}`, `{server.id}`, `{server.name}`, `{servers.members}`.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/508f0024-de62-4c20-b56c-1f7ec713a7f9) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/b74b2db6-4d83-407e-8c39-9099b8a51af7)

## Buy-item
Compra los items necesarios que haiga en la tienda pero, ¡Cuidado que no tengas dinero!.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/05a36ba9-6171-4527-b119-c8bb202c6409)

__Importante__

Debes remplazar los var por las dos variables de "dinero" y "banco" que manejes.
de los __contrario__ el buy-item no funcionara y seguramente no hara las restas correspondientes en el dinero y balance requeridos.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/24f2ada0-737b-401b-ba60-f0484ea3057b)

## Inventory

Mira todo tu inventario disponible, tambien puedes ver el de un usuario.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/b1f489cb-e7f8-40d7-af73-bef7995d98b1)

## Use

Usa los items y reclama a la vez la reconpensas que trae este item!!. tienes la opcion de cuantos usos darle y restarte.
__Nota__
Puedes personalizar el mensaje de canjeo con edit-item en la opcion de `reply` de dicho item.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/ecb8987b-b361-4131-adad-87ce2e27268a)

## Collect
Mira todos los roles recolectados canjeados con el comando `use`. 
__Importante__
este codigo no esta terminado en si falta agrega esos porcentajes de dinero que no se que significan. Pero su funcion esta al 100%

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/d8f18baf-6523-460f-be34-49a7718aba56)

