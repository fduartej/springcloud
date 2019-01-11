SPRING CLOUD

Este es un ejemplo acerca de como usar spring cloud y esta compuesto de los siguientes componentes:

- config: donde estan todas las configuraciones de las aplicaciones
- spring-cloud-config: este es un microservicio que se encarga de proveer todas las configuraciones a las diferentes aplicaciones.
- party-app: este es un microservicio que nos permite proveer las APIs para un CRUD del Party, ojo que aqui se podria crear diferentes tipo de parties como proveedores, clientes, empresas, integraciones y se podria gestionar el acceso y los roles que deben cumplir-
- product-app: este es un microservicio que nos permite proveer las APIs para un CRUD del Product, ojo aqui se pueden crear los features de cada producto, las aplicaciones del producto las vigencias, si es un producto tangigle o intangible.
- loan-app: este es un microservicio que nos permite proveer las APIs para un crear Loans, aprobar los prestamos, rechazar los prestamos etc.
- bank-app: este es una aplicacion front que integra los diferentes microservicios.

