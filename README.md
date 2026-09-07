# Sistema de Gestion de Inventario - Techstore

## 1. Descripción del Proyecto
Este sistema permite la **gestión integral de ventas e inventarios** optimizando el control de existencias en tiempo real. Fue diseñado para mejorar la eficiencia operativa en *Techstore*.

## 2. Requisitos del Sistema
- [x] Python 3.10 o superior instalado
- [x] Base de Datos MySQL configurada
- [ ] Documentacion tecnica completada

## 3. Módulos del Sistema
| Modulo | Descripcion | Estado |
| --- | --- | --- |
| Autenticacion | Control de acceso y roles de usuario | Completado |
| Inventario | Registro y conteo de productos | En Proceso |
| Facturacion | Generacion de comprobantes de pago | Pendiente |

## 4. Ejemplo de Codigo Fuente
```python
def verificar_stock(cantidad):
    if cantidad > 0:
        return "Producto Disponible"
    else:
        return "Sin Stock"
        ```