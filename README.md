# DoctorMotors — Sistema de Gestión de Taller

Sistema de gestión de taller mecánico para motos desarrollado en Python. Permite registrar vehículos, hacer seguimiento del estado de cada reparación, gestionar piezas y generar recibos en PDF. Cuenta con interfaz gráfica de tema oscuro, base de datos SQLite local y se distribuye como ejecutable Windows.

---

## Capturas de pantalla

### Login
![Login](imagenes%20de%20las%20pruebas/Login.png)

### Dashboard
![Dashboard](imagenes%20de%20las%20pruebas/Dashboard.png)

### Vista general
![Vista general](imagenes%20de%20las%20pruebas/Captura%20de%20pantalla%202026-05-23%20125801.png)

### Orden generada
![Orden generada](imagenes%20de%20las%20pruebas/Orden%20Generada.png)

---

## Características

- Registro de motos con datos del propietario (marca, modelo, placa, km, etc.)
- Seguimiento de estados: En espera · En reparación · Listo · Entregada · Cancelada
- Gestión de piezas y mano de obra por orden
- Generación de recibos en PDF
- Interfaz gráfica con tema oscuro (Tkinter)
- Base de datos local SQLite en `%APPDATA%\DoctorMotors`
- Autenticación con sesión persistente
- Distribuido como ejecutable `.exe` (PyInstaller + Inno Setup)

---

## Tecnologías

| Tecnología | Uso |
|---|---|
| Python | Lenguaje principal |
| Tkinter / ttk | Interfaz gráfica |
| SQLite | Base de datos local |
| ReportLab | Generación de PDF |
| PyInstaller | Empaquetado ejecutable |
| Inno Setup | Instalador Windows |

---

## Autor

**Fernando Velez**  
© 2026 DoctorMotors. Todos los derechos reservados.
