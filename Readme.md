# Module 5: Hosting Services On-Premises and in Azure

# Lesson 1: Hosting Services On-Premises

### Demonstration: Hosting ASP.NET Core Services in IIS

- Abrimos el proyecto HostingISSAndISSExpress en Visual Studio 2019

- Ejecutamos

  



![](D:/20487C/Demo/20487-Mod3-Demo-Lesson5_3/img/Captura1.jpg)



- Abrimos **Internet Information Services(IIS) Manager**

- creamos un nuevo site con el nombre **HotelsSite** en el puerto 8085

  

  ![](D:/20487C/Demo/20487-Mod3-Demo-Lesson5_3/img/Captura3.jpg)

  

- En el Application pool del site cambiamos  **.NET CLR version** por **No Managed Code**

  ![](D:/20487C/Demo/20487-Mod3-Demo-Lesson5_3/img/Captura2.jpg)

- Publicamos desde Visual Studio

- Abrimos el navegador con la url **localhost:8085/api/Values**

  

![](D:/20487C/Demo/20487-Mod3-Demo-Lesson5_3/img/Captura4.jpg)