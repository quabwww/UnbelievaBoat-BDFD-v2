# UnbelievaBoat-en-BDFD

¡Hola! soy el creador de estos codigos xquab pertenesco al equipo de [The BDS Word](https://discord.gg/dru9uRYKqq). Sigue las indicaciones para poder usar el codigo ten en cuenta que si no sabes como funciona el codigo no desordenes nada o lo romperas.

Posdata: Si quieres codigos y guias unete al servidor **servidor**. Tambien podras estar al tanto de novedades de proyectos mas adelante.
Link: https://discord.gg/dru9uRYKqq

### Algunos canales con los que contamos.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/48c08513-60a8-4b1a-ba40-01fec23548ba) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/cdfd37cb-644b-45d9-b2c7-efa3c973d10f) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/ea18e114-b14e-40f9-94d3-7cf16a932f75) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/0e7a6b43-0855-4737-af73-cc668f48f102) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/00c86bed-9cd5-471c-8065-9c73514e9792)





## Guia tutorial

### Variables Necesarias.

Crealas tal y como esta, cada valor de variable es unico y necesario al igual que el nombre.

|    Nombre              |                                                 Valor                                                  | 
| -----------------------| -------------------------------------------------------------------------------------------------------| 
| item                   |                        {}                                                                              |
| descripcion            |                        {}                                                                              |
| requerido              |                        {}                                                                              |
| dar                    |                        {}                                                                              |
| quitar                 |                        {}                                                                              |
| balance                |                        {}                                                                              |
| contador               |                         1                                                                              |
| valor                  |                        {}                                                                              |
| stock                  |                        {}                                                                              |
| reply                  |                        {}                                                                              |
| currency               |                      :emoji:                                                                           |
| role-collect           |                        {}                                                                              |
| count-collect          |                        {}                                                                              |
| contador-replys        |   {"work": "1", "crime": "1", "slut": "1"}                                                             |
| fallar-contador-replys |   {"crime": "1", "slut": "1"}                                                             |
| min-max-payout         |{"minwork": "1", "maxwork": "100", "mincrime": "1", "maxcrime": "100", "minslut": "1", "maxslut": "100"}|
| min-max-fail           |{"minwork": "1", "maxwork": "100", "mincrime": "1", "maxcrime": "100", "minslut": "1", "maxslut": "100"}|
| reply-work             |{}                                                                                                |
| reply-crime             |{}                                                                                               |
| reply-slut             |{}                                                                                                |
| fallar-reply-crime             |{}                                                                                               |
| fallar-reply-slut             |{}                                                                                                |
| probality                     |{"slut": "30", "crime": "40"}                                                                     |
| on/off-replys                 |false                                                                                             |
| reply-global                 |0                                                                                             |


__Importante__: Debes tener dos variables para complementar este codigo que seria tu "dinero" "banco" en economia.

## Avanzes del resultado

### [Crear-item](https://github.com/quabwww/UnbelievaBoat-BDFD/blob/main/UnbelievaBoat%3A%20Create-item)
Crea los nombre de los items pero no mayor a 30 caracteress esto esta balanceado para usuarios premium y no premium sobre el limite de caracteres en las variables, __tambien que cada espacio que use sera remplazado por "_"__. tenga en cuenta esto.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/3266ff80-de49-4d03-9485-e98dbe47ffbb)

### [Edit-item](https://github.com/quabwww/UnbelievaBoat-BDFD/blob/main/UnbelievaBoat%3A%20Edit-item)
Edita el item ya creado puedes usar el nombre del item dentro de doble comillas.
Ejemplo: `"item_name"`

__Opciones disponibles:__
- name, price, value, description,stock, role-required , role-give, role-removed, required-balance, reply.

__Reply - Tags:__
- `{member.id}`, `{member.username}`, `{member.tag}`, `{member.mention}`, `{server.id}`, `{server.name}`, `{servers.members}`.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/508f0024-de62-4c20-b56c-1f7ec713a7f9) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/b74b2db6-4d83-407e-8c39-9099b8a51af7)

### [Buy-item](https://github.com/quabwww/UnbelievaBoat-BDFD/blob/main/UnbelievaBoat%3A%20Buy-item)
Compra los items necesarios que haiga en la tienda pero, ¡Cuidado que no tengas dinero!.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/05a36ba9-6171-4527-b119-c8bb202c6409)

__Importante__

Debes remplazar los var por las dos variables de "dinero" y "banco" que manejes.
de los __contrario__ el buy-item no funcionara y seguramente no hara las restas correspondientes en el dinero y balance requeridos.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/24f2ada0-737b-401b-ba60-f0484ea3057b)

### [Inventory](https://github.com/quabwww/UnbelievaBoat-BDFD/blob/main/UnbelievaBoat%3A%20Inventory)

Mira todo tu inventario disponible, tambien puedes ver el de un usuario.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/b1f489cb-e7f8-40d7-af73-bef7995d98b1)

### [Use](https://github.com/quabwww/UnbelievaBoat-BDFD/blob/main/UnbelievaBoat%3A%20Use)

Usa los items y reclama a la vez la reconpensas que trae este item!!. tienes la opcion de cuantos usos darle y restarte.
__Nota__
Puedes personalizar el mensaje de canjeo con edit-item en la opcion de `reply` de dicho item.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/ecb8987b-b361-4131-adad-87ce2e27268a)

### [Collect](https://github.com/quabwww/UnbelievaBoat-BDFD/blob/main/UnbelievaBoat%3A%20Collect)
Mira todos los roles recolectados canjeados con el comando `use`. 
__Importante__
este codigo no esta terminado en si falta agrega esos porcentajes de dinero que no se que significan. Pero su funcion esta al 100%

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/d8f18baf-6523-460f-be34-49a7718aba56)

## [Item-info](https://github.com/quabwww/UnbelievaBoat-BDFD/blob/main/UnbelievaBoat%3A%20Item-info)
Obten toda la informacion de un item. puedes editar su reconpensa con `edit-item`.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/5b87e80c-fda9-4139-bc43-ea6aa4f13c01)

### [Set-currency](https://github.com/quabwww/UnbelievaBoat-BDFD/blob/main/Unbeliebeboat%3A%20Set-currency)
Establece un emoji valido para la moneda local de tu servidor. ¿Que esperas?.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/089486a3-2469-4b9e-ada1-5d472c699788)

### [Delete-item](https://github.com/quabwww/UnbelievaBoat-BDFD/blob/main/Unbeliebeboat%3A%20Delete-item)
Elimina los item de la tienda, cabe recalcar que los item en si se borran (servidor) pero no los valores aparte de los usuarios.
este se debe ya que la variable esta comprimida a `{}` funciones JSON y para restablecer un valor globalmente en local se usa `$resetUserVar` asi que si usamos eso estaria reseteando ya no un item de valor si no los 10.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/4ec0b4ce-9ada-4821-86e2-340ba7c618d6)

### [Shop](https://github.com/quabwww/UnbelievaBoat-BDFD/blob/main/Unbeliebeboat%3A%20Shop)
Mira toda la shop y sus articulos disponibles. Los item va rotando de manera ascendete quiere decir que se ira acomodando los items segun el orden de su valor.

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/cc591118-b928-4a48-8632-65ea8d7756ef)

## Otros

No deceas copiar codigo por codigo?. No hay problema puedes crear un bot en Bot Desinger For Discord y agregar este codigo compartido con todo los codigos ya introducidos

**Nota:** Perdon si ves codigos inncesarios se havian usado para testear comandos.

Share Code: gZ4lNta9barY57hfw0xvcppyz

**Tutorial:**

![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/d43e2b47-1812-4745-b64b-9879aed8144b) ![image](https://github.com/quabwww/UnbelievaBoat-BDFD/assets/148601206/0ce885b0-d99a-4c8e-8749-bd66a77bdeea)



