# 📖 Guía Completa de Uso - Sistema OATI

## 🎯 Introducción
Guía paso a paso para utilizar todas las funcionalidades del sistema de registro de actividades de la Oficina de Apoyo Técnico Informático.

## 📋 1. Registro de Actividades

### 1.1 Formulario Principal
**Campos obligatorios** (marcados con *):
- **Categoría**: Selecciona el tipo de actividad
- **Trabajo Realizado**: Describe brevemente la actividad
- **Dependencia**: Área que solicitó el servicio
- **Fecha**: Fecha de realización (formato: AAAA-MM-DD)
- **Detalle del Trabajo**: Descripción completa
- **Cómo fue la Solicitud**: Medio por el que se recibió
- **OATI Responsable**: Nombre del técnico
- **Status**: Estado actual de la actividad
- **Operatividad**: Estado del equipo
- **Tipo de Equipo**: Categoría del equipo
- **Marca**: Fabricante del equipo
- **Modelo**: Modelo específico
- **Serial**: Número de serie
- **Nro Bien**: Número de inventario

### 1.2 Ejemplo de Registro Correcto
```json
{
  "categoria": "Mantenimiento",
  "trabajoRealizado": "Limpieza interna de computadora",
  "dependencia": "Sistemas",
  "fecha": "2023-12-20",
  "detalleTrabajo": "Limpieza completa de componentes internos, cambio de pasta térmica y limpieza de ventiladores",
  "solicitud": "Presencial",
  "oati": "Juan Pérez López",
  "status": "Completado",
  "operatividad": "Operativo",
  "tipoEquipo": "Computadora",
  "marca": "HP",
  "modelo": "EliteDesk 800 G4",
  "serial": "ABC123456789",
  "nroBien": "SIS-2023-00158"
}
