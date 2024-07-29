# Principios_JPA_Producto-
Grupo #9 
## Integrantes:
- Benites Geraldine
- Cadena Daniel
- Casco Bryan
- Chiriguaya Kevin
- Vallejo Andres

## : Crear la Entidad y el Repositorio

1. **Crear la Entidad Producto:**
   - Creamos un paquete llamado `model`.
   - Dentro del paquete `model`, crea una clase `Producto` con los siguientes atributos:
     ![image](https://github.com/user-attachments/assets/f2e489f9-6468-440f-bd40-d3f28f49b8d1)

2. **Crear el Repositorio ProductoRepository:**
   - Creamos un paquete llamado `repository`.
   - Dentro del paquete `repository`, crea una interfaz `ProductoRepository` que extienda `JpaRepository<Producto, Long>`.
     ![image](https://github.com/user-attachments/assets/04ec95d4-091d-4f14-b329-3d6570c70f44)

## Parte 3: Crear el Servicio

1. **Crear la Clase ProductoService:**
   - Creamos un paquete llamado `service`.
   - Dentro del paquete `service`, crea una clase `ProductoService` con métodos para manejar la lógica del negocio (CRUD).
     
     ![image](https://github.com/user-attachments/assets/e63aaf1c-7a45-46f6-8c18-132a07d097a2)
      ![image](https://github.com/user-attachments/assets/1263f7a4-df25-420f-bcfa-573c68df66ff)

## Parte 4: Crear el Controlador

1. **Crear la Clase ProductoController:**
   - Creamos un paquete llamado `controller`.
   - Dentro del paquete `controller`, crea una clase `ProductoController` con endpoints REST para manejar productos.
     ![image](https://github.com/user-attachments/assets/87c45846-a54f-48ea-91b5-a93c305f2ac8)


## Parte 5: Inicializar la Base de Datos

1. **Cargar Datos de Prueba:**
2. 
   ![image](https://github.com/user-attachments/assets/6bb723cc-2ad7-4a2e-9cb3-7f96b091ccae)
   
   
   ![image](https://github.com/user-attachments/assets/67a3954e-482e-4f28-ad28-22eb0cda867b)

## Parte 6: Ejecutar y Probar la Aplicación

1. **Ejecutar la Aplicación:**
  ![image](https://github.com/user-attachments/assets/38fb46a6-93d6-4271-95a2-3d10097d2270)

2. **Probar los Endpoints:**
   - Usamos herramientas como Postman o cURL para probar los endpoints creado:
     - `GET /api/productos`
     - ![image](https://github.com/user-attachments/assets/27ee6491-5904-49fb-a911-5f1c67036c53)

     - `GET /api/productos/{id}`
     - ![image](https://github.com/user-attachments/assets/748a51c0-b1f9-44da-9f56-f34f716d9014)

     - `GET /api/productos/search?nombre={nombre}`
     - ![image](https://github.com/user-attachments/assets/988b57b6-bf49-457f-b534-a4490deab078)

     - `GET /api/productos/searchByPrecio?preciomin={preciomin}&preciomax={preciomax}`
     - ![image](https://github.com/user-attachments/assets/3b09b55e-5c54-449f-8792-c9cae6a8c1f5)

