# Actividades con el modelo E/R
## 1. Obtén el diagrama E/R con las dos entidades siguientes:
    • EMPLEADO (Id_E, DNI_E, Nombre, Teléfono, Salario)
    • DEPARTAMENTO (Código_D, Nombre, Localización)
    
    Teniendo en cuenta que:
    a) Un empleado pertenece a un único departamento y en un departamento puede haber varios empleados. Pero sólo uno será el jefe del departamento.
    b) Un empleado podrá ser jefe o no. Si no es jefe, su jefe será el del departamento al que pertenece.

##    2. Se desea diseñar una base de datos sobre la información de una cadena editorial teniendo en cuenta que:
    a) La editorial tiene varias sucursales, con su domicilio, teléfono y un código de sucursal.
    b) Cada sucursal tiene varios empleados, de los cuales tendremos sus datos personales, DNI y teléfono. Un empleado trabaja en una única sucursal.
    c) En cada sucursal se publican varias revistas, de las que almacenaremos su título, número de registro, periodicidad y tipo.
    d) La editorial tiene periodistas (que no trabajan en las sucursales) que pueden escribir artículos para varias revistas. Almacenaremos los mismos datos que para los empleados, añadiendo su especialidad.
    e) Para cada revista, almacenaremos información de cada número, que incluirá la fecha, número de páginas y el número de ejemplares vendidos.
 ## 3. Se desea diseñar una base de datos sobre las películas de una cadena de video clubs para mejorar su servicio. La información que nos han facilitado es la siguiente:
    a) Una película se caracteriza por su título, nacionalidad, productora y fecha. Puede haber varias películas con el mismo título pero rodadas en fechas distintas.
    b) En una película pueden participar varios actores (nombre, nacionalidad, sexo) algunos de ellos como actores principales.
    c) Una película está dirigida por un director (nombre, nacionalidad).
    d) De cada película se dispone de uno o varios ejemplares diferenciados por un número de ejemplar y caracterizados por su estado de conservación.
    e) Un ejemplar se puede encontrar alquilado a algún socio (DNI, nombre, dirección, teléfono) . Se desea almacenar la fecha de comienzo del alquiler y la de devolución.
    f) Un socio tiene que ser avalado por otro socio que responda de él en caso de tener problemas en el alquiler.

## 4. Un Ayuntamiento desea actualizar el sistema que gestiona el Padrón Municipal. Para ello nos solicitan que diseñemos un esquema E/R que recoja la organización de un sistema de información en el que se quiere tener los datos sobre municipios, viviendas y personas. La única información que nos han facilitado es la siguiente:
    a) Cada persona sólo puede habitar una vivienda, pero puede ser propietaria de varias.
    b) Pueden haber viviendas vacias.
    c) También les interesa la relación de las personas con su cabeza de familia. Suponen que solo puede haber uno por vivienda.
## 5. Se desea diseñar una BD de una entidad bancaria que contenga información sobre los clientes, las cuentas, las sucursales y las transacciones producidas. Construye el modelo E/R teniendo en cuenta las siguientes restricciones:
    a) Una transacción viene determinada por un número de transacción (único para cada cuenta), la fecha y la cantidad.
    b) Un cliente puede tener muchas cuentas.
    c) Una cuenta puede ser de muchos clientes.
    d) Una cuenta sólo puede estar en una sucursal.
## 6. Una base de datos para una pequeña empresa debe contener información acerca de clientes, artículos y pedidos. Ten en cuenta la siguiente información:
    a) Para cada cliente: Número de cliente (único), Direcciones de envío (varias por cliente), Saldo, Límite de crédito, Descuento.
    b) Para cada artículo: Número de artículo (único), Fábricas que lo distribuyen, Existencias de ese artículo en cada fábrica, Descripción del artículo.
    c) Para cada pedido: Cada pedido se registrará en un documento impreso que tiene una cabecera y el cuerpo del pedido. Para generar dicho informe se necesitará la siguiente información:
    • La cabecera está formada por el número de cliente, dirección de envío y fecha del pedido.
    • El cuerpo del pedido son varias líneas, en cada línea se especifican el número del artículo pedido y la cantidad.
    d) Además, se ha determinado que se debe almacenar la información de las fábricas. Sin embargo, dado el uso de distribuidores, se usará: Número de la fábrica (único) y Teléfono de contacto.
    e) Y se desean ver cuántos artículos (en total) provee la fábrica. También, por información estratégica, se podría incluir información de fábricas alternativas respecto de las que ya fabrican artículos para esta empresa.

## 7. Realiza el diagrama E/R para el siguiente supuesto. Le contratan para hacer una BD que permita apoyar la gestión de un sistema de ventas. La empresa necesita llevar un control de proveedores, clientes, productos y ventas.
    a) Un proveedor tiene un código único, nombre, dirección, teléfono y página web.
    b) Un cliente también tiene un código único, nombre, dirección, pero puede tener varios teléfonos de contacto. La dirección se entiende por calle, número, comuna y ciudad.
    c) Un producto tiene un id único, nombre, precio actual, stock y nombre del proveedor. Además se organizan en categorías, y cada producto va sólo en una categoría.
    d) Una categoría tiene id, nombre y descripción.
    e) Por razones de contabilidad, se debe registrar la información de cada venta con un id, fecha, cliente, descuento y monto final.
    f) Además se debe guardar el precio al momento de la venta, la cantidad vendida y el monto total por el producto.
