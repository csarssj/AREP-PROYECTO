# Patrones y estrategías de DRP yBackups en la nube

## Descripción

Se plante un escenario donde se desea evaluar la capacidad de Azure Backup para proteger el contenido de equipos locales y máquinas virtuales de IaaS de Azure. R. Datum Corporation también desea evaluar Azure Site Recovery para proteger las máquinas virtuales de Azure.

![image](https://github.com/csarssj/AREP-PROYECTO/blob/main/img/DRP-Activo_Activo.png)

## Objetivos 

La finalidad de este ejercicio es: 
	
   - Implementar Azure Backup.
	
   - Implementar la protección basada en Azure Site Recovery de las máquinas virtuales de Azure.
	
## Steps

### Azure Backup

1. Crear una bóveda de servicios de recuperación

2 .Configurar la bóveda para la copia de seguridad local

3. Instalar y configurar el agente de servicios de recuperación de Azure

4. Crea un horario de respaldo

5. Ejecuta una copia de seguridad

6. Realizar una restauración

7. Deshabilite las copias de seguridad y elimine la bóveda

### Protección de máquinas virtuales mediante Azure Site Recovery

1. Crear una bóveda de Azure Recovery Services

2. Configurar la replicación de máquinas virtuales de Azure

3. Revise la configuración de replicación de máquinas virtuales de Azure

4. Deshabilite la replicación de una máquina virtual de Azure y elimine el almacén de Azure Recovery Services

5. Eliminar el entorno del laboratorio

	
## Authors

[Brayan Buitrago](https://github.com/DonSantiagoS) 
[Guillermo Catro](https://github.com/memo1019) 
[César González](https://github.com/csarssj) 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) 