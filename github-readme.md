# 📋 Aplicación de Consentimientos Informados
## Cirugía Reconstructiva con Colgajos Libres

Una aplicación web profesional para generar consentimientos informados y conclusiones para historia clínica en cirugía reconstructiva.

![Screenshot](https://via.placeholder.com/800x400/4F46E5/FFFFFF?text=Consentimientos+Informados)

## 🏥 Especialidades Incluidas

### 🩺 Reconstrucción Mamaria
- **DIEP** (Deep Inferior Epigastric Perforator)
- **SIEA** (Superficial Inferior Epigastric Artery)
- **Colgajo Inguinal Libre**
- **ALT para Mama** (Anterolateral del Muslo)

### 🦷 Reconstrucción Cabeza y Cuello
- **ALT** (Anterolateral del Muslo)
- **Colgajo Radial del Antebrazo**
- **Colgajo de Peroné**
- **Colgajo Escapular/Paraescapular**
- **Colgajo de Latissimus Dorsi**

### 🦵 Colgajos Libres para Miembros Inferiores
- **ALT para Miembro Inferior**
- **Colgajo Radial para Miembro Inferior**
- **Colgajo Escapular para Miembro Inferior**
- **Latissimus Dorsi para Miembro Inferior**

## ✨ Características

- 🎯 **Interfaz intuitiva** - Navegación simple por especialidades
- 📝 **Consentimientos completos** - Descripción, riesgos, cuidados postoperatorios
- 🏥 **Conclusiones para historia clínica** - Formato profesional listo para copiar
- 📋 **Función de copiado** - Un clic para copiar al portapapeles
- 📱 **Responsive** - Funciona en desktop, tablet y móvil
- ⚡ **Rápido y eficiente** - Sin dependencias externas

## 🚀 Uso

1. **Seleccionar especialidad** - Elige entre las 3 áreas principales
2. **Elegir procedimiento** - Selecciona el colgajo específico
3. **Revisar contenido** - Navega entre consentimiento y conclusión
4. **Copiar información** - Un clic para copiar a la historia clínica

## 💻 Tecnologías

- **React** - Framework principal
- **Tailwind CSS** - Estilos y diseño responsive
- **Lucide React** - Iconografía moderna
- **JavaScript** - Lógica de la aplicación

## 📦 Instalación

### Opción 1: Uso Directo
Simplemente abre el archivo HTML en tu navegador.

### Opción 2: Desarrollo Local
```bash
# Clonar repositorio
git clone https://github.com/tu-usuario/consentimientos-informados.git

# Instalar dependencias
npm install

# Ejecutar en desarrollo
npm start
```

## 🏗️ Estructura del Proyecto

```
consentimientos-informados/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   └── ConsentFormsApp.jsx
│   ├── data/
│   │   └── procedures.js
│   └── index.js
├── package.json
└── README.md
```

## 📋 Contenido Médico

Todos los consentimientos incluyen:
- **Descripción detallada** del procedimiento
- **Riesgos específicos** por tipo de colgajo
- **Cuidados postoperatorios** detallados
- **Alternativas terapéuticas**
- **Conclusiones estructuradas** para historia clínica

## 🔧 Personalización

### Agregar Nuevo Procedimiento
1. Añadir entrada en `procedures` object
2. Definir datos en `consentData` object
3. Incluir: title, description, risks, postop, alternatives, conclusion

### Modificar Contenido
Editar directamente los textos en el objeto `consentData` dentro del componente.

## 📱 Compatibilidad

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Dispositivos móviles

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -m 'Agregar nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.

## ⚠️ Disclaimer Médico

Esta aplicación es una herramienta de apoyo para profesionales médicos. El contenido debe ser revisado y adaptado según:
- Normativas locales
- Protocolos institucionales
- Criterio médico profesional
- Actualización constante de evidencia científica

## 👨‍⚕️ Autor

Desarrollado para uso en práctica de cirugía reconstructiva con colgajos libres.

## 📞 Contacto

Para preguntas o sugerencias:
- 📧 Email: [tu-email@ejemplo.com]
- 🐛 Issues: [GitHub Issues](https://github.com/tu-usuario/consentimientos-informados/issues)

---

**⭐ Si te resulta útil, no olvides dar una estrella al repositorio**