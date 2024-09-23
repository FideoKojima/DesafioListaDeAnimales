# 🐾 Sistema de Registro de Mascotas - Clínica Veterinaria Pet-XYZ

## 📋 Descripción
Este proyecto implementa un sistema en línea para la clínica veterinaria Pet-XYZ, permitiendo a médicos veterinarios y asistentes registrar información de tres tipos de animales: 🐶 Perros, 🐱 Gatos y 🐰 Conejos. El sistema utiliza un formulario web para capturar datos del animal y su dueño, y muestra la información recopilada en una lista.

## ✨ Características
- 📝 Registro de información para perros, gatos y conejos.
- 👤 Captura de datos del dueño (nombre, dirección, teléfono).
- 🦴 Captura de datos del animal (nombre, tipo, enfermedad/motivo de consulta).
- 📊 Visualización de los datos ingresados en formato de lista.

## 🛠️ Tecnologías Utilizadas
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📁 Estructura del Proyecto
```
pet-xyz-system/
│
├── 📄 index.html
├── 🎨 styles.css
├── 📜 script.js
└── 📚 README.md
```

## 🚀 Instalación
1. Clona este repositorio:
   ```
   git clone https://github.com/FideoKojima/DesafioListaDeAnimales.git
   ```
2. Navega al directorio del proyecto:
   ```
   cd pet-xyz-system
   ```
3. Abre `index.html` en tu navegador web preferido.

## 💻 Uso
1. 🌐 Abre la aplicación en tu navegador.
2. 📝 Completa el formulario con la información requerida:
   - 🐾 Tipo de animal (Perro, Gato o Conejo)
   - 👤 Nombre del propietario
   - 🏠 Dirección del propietario
   - 📞 Teléfono del propietario
   - 🐶🐱🐰 Nombre de la mascota
   - 🩺 Enfermedad o motivo de consulta
3. 🖱️ Haz clic en el botón "Agregar" para registrar la información.
4. 📋 La información ingresada se mostrará en una lista debajo del formulario.

## 🏗️ Estructura de Clases
El proyecto utiliza programación orientada a objetos con las siguientes clases:

1. `Propietario`: 👤 Almacena información del dueño de la mascota.
2. `Animal`: 🐾 Hereda de `Propietario` y añade el tipo de animal.
3. `Mascota`: 🦴 Hereda de `Animal` y añade detalles específicos de la mascota.

## 🎨 Personalización
Puedes personalizar los estilos editando el archivo `styles.css` para adaptar la apariencia a las necesidades específicas de la clínica Pet-XYZ.

## 🤝 Contribución
Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cambios mayores antes de enviar un pull request.

## 📜 Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## 📞 Contacto
Para cualquier consulta o sugerencia, por favor contacta a [Luis Suarez](mailto:suarezluis.ea@gmail.com).

---

🎓 Desarrollado como parte del desafío de programación de Desafío Latam.

![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Ftu-usuario%2Fpet-xyz-system&label=Visitantes&countColor=%23263759)