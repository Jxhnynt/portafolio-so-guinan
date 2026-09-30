# Listado de Comandos básicos
## S.O. Windows con PoweShell

### Ver características de la CPU
```
Get-CimInstance Win32_Processor
```
### Ver característiccas de la memoria RAM
```
Get-CimInstance Win32_PhysicalMemory
```
### Ver características del disco duro
```
Get-PhysicalDisk  ;  Get-Volume
```
### Ver características de E/S 
```
Get-PnpDevice -PresentOnly
```
### Ver resumen de propiedades de Hardware
```
systeminfo  ;  msinfo32
```
## S.O. Linux con bash
### Ver características de la CPU
```
lscpu
```