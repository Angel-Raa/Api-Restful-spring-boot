# spring security jwt authentication and authorization

Si encuentras útil este repositorio, ¡por favor ayúdanos marcándolo con una ⭐! 😊

## ¿Qué son los JSON Web Tokens (JWT)?

Los JSON Web Tokens (JWT) son un estándar abierto para la transmisión segura de información en formato JSON. Están compuestos por tres partes separadas por puntos:

1. **Header**: Contiene información sobre el token, como el algoritmo de firma utilizado.

2. **Payload**: Incluye los datos del token, como el nombre de usuario, la fecha de expiración, entre otros.

3. **Signature**: Es una firma digital utilizada para verificar la autenticidad del token.

Los JWT se utilizan ampliamente para la autenticación y autorización de usuarios en aplicaciones web. Ofrecen la ventaja de permitir el envío seguro de información entre servidores y clientes, sin necesidad de almacenar datos sensibles en el servidor.

## Ventajas de los JWT

- **Seguridad**: Los JWT se pueden firmar digitalmente para verificar su autenticidad, lo que los hace resistentes a la falsificación.

- **Eficiencia**: Los JWT son ligeros y fáciles de transportar debido a su formato compacto.

- **Facilidad de uso**: Implementar JWT en aplicaciones web es sencillo gracias a su estructura y a las bibliotecas disponibles.

## Usos comunes de los JWT

1. **Autenticación**: Los JWT se utilizan para autenticar a los usuarios en aplicaciones web. El servidor emite un JWT después de que el usuario se haya autenticado con éxito, y este token se utiliza para verificar la identidad del usuario en las solicitudes posteriores.

2. **Autorización**: Los JWT se pueden utilizar para autorizar a los usuarios a acceder a recursos específicos. Los claims (reclamos) en el payload del JWT pueden contener información sobre los roles o permisos del usuario.

3. **Intercambio de información**: Los JWT se emplean para intercambiar información de forma segura entre aplicaciones web. Esto es útil en casos como la comunicación entre microservicios o la autenticación en una API.

### Docs 
```
http://localhost:8000/api/v1/swagger-ui/index.html#/
```
![](https://github.com/Angel-Raa/spring-security-jwt-authentication-and-authorization/blob/main/src/main/resources/img/docs.png)




Esperamos que esta documentación te ayude a comprender mejor cómo usar los JSON Web Tokens (JWT) en tu aplicación de Spring Security. Si tienes alguna pregunta o sugerencia, no dudes en abrir un problema o contribuir al repositorio.





