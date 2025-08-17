# Configuración y Simulación de Red VLAN en PNETLab

## Descripción
Este proyecto consiste en la configuración y simulación de VLANs entre subredes utilizando PNETLab. El objetivo es segmentar la red por grupos de usuarios, mejorar la seguridad y facilitar la administración del tráfico interno.

## Topología de Red
Se implementó una topología con switches donde cada puerto se asigna a una VLAN específica. Se aplican colores para identificar visualmente cada VLAN y aislar los grupos de usuarios.

### Consideraciones
- Ningún puerto permanece en la VLAN por defecto.  
- Los puertos no utilizados se asignan a una VLAN de parqueo para evitar accesos no autorizados.  
- Cada VLAN representa un grupo específico de usuarios.

## Asignación de VLANs

| VLAN | Nombre          |
|------|-----------------|
| 10   | Estudiantes     | 
| 20   | Docentes        | 
| 30   | Administrativos |
| 40   | Cafetería       | 
| 50   | IT              | 
| 60   | Cámaras         | 

## Objetivos
- Segmentar la red para mejorar la seguridad y control de tráfico.  
- Evitar que puertos no utilizados puedan ser accedidos por usuarios externos.  
- Facilitar la gestión de diferentes grupos mediante la identificación visual de VLANs.

## Uso
1. Cargar la topología en PNETLab.  
2. Configurar los switches según la asignación de VLANs.  
3. Verificar la conectividad entre los dispositivos de la misma VLAN mediante pings.  
4. Comprobar que los puertos en VLAN de parqueo no sean accesibles.

