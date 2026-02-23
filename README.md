# ont-huawei-bridge-telecom-personal-flow-argentina
Instructivo oficial septiembre 2024 - Configuración ONTs Huawei HG8245U / HG8245W5-8T-V2 / HG8145X6-10 en Modo Bridge (Telecom - Personal - Flow) Argentina

# Instructivo ONTs Huawei en Modo Bridge - Telecom / Personal / Flow (Septiembre 2024)

**Modelos compatibles:**
- HG8245U
- HG8245W5-8T-V2
- HG8145X6-10

Guía completa y oficial para configurar **modo Bridge puro** en fibra óptica de Telecom Argentina (Fibertel), Personal y Flow.

### ¿Para qué sirve?
- Tener IP pública en tu propio router (TP-Link, Asus, Mikrotik, etc.)
- Evitar doble NAT
- Mantener telefonía y TV IP

### Descarga directa del PDF
[📥 Descargar Instructivo completo (PDF)](https://github.com/angelettif/ont-huawei-bridge-telecom-personal-flow-argentina/blob/main/guia-ont-modo-bridge-argentina.pdf)

### Pasos principales (resumen)
1. Verificar servicio activo
2. Conectar por Ethernet + IP fija
3. Acceder a http://192.168.1.1/admin.html (admin / CalVxePV1!)
4. Deshabilitar WAN 1_INTERNET_R_VID_33
5. Crear nueva WAN en modo Bridge (VLAN 33)
6. Asociar puertos LAN 1-4 al bridge
7. Apagar WiFi 2.4G y 5G de la ONT
8. Configurar PPPoE en tu router:  
   **Usuario:** [ID_cliente]_BRIDGE@telecom  
   **Password:** telecom

### Palabras clave (para que te encuentren)
ont bridge huawei, modo bridge huawei, hg8245u bridge, hg8245w5 bridge, hg8145x6 bridge, telecom fibra bridge, personal flow bridge, _BRIDGE@telecom, ont modo puente telecom, configurar ont bridge argentina, fibertel bridge 2024, dominio digital ont bridge

Hecho en Argentina - Septiembre 2024  
