# 🚀 Guía de Instalación y Ejecución

## Requisitos Previos

- Node.js 16+ instalado
- npm o yarn
- Git

## Instalación

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/mauricio-acuna-labs/Memory-Systems-Educational-Portal.git
   cd producto2-ia
   ```

2. **Instalar dependencias:**
   ```bash
   npm install
   ```

3. **Iniciar servidor de desarrollo:**
   ```bash
   npm start
   ```

4. **Abrir en el navegador:**
   ```
   http://localhost:3000
   ```

## Scripts Disponibles

- `npm start` - Inicia el servidor de desarrollo
- `npm run build` - Construye la aplicación para producción
- `npm test` - Ejecuta los tests
- `npm run eject` - Expone la configuración de webpack

## Estructura del Proyecto

```
src/
├── components/          # Componentes reutilizables
│   ├── Header.js       # Navegación principal
│   ├── Footer.js       # Pie de página
│   ├── LandingPage.js  # Página de inicio
│   ├── CodeBlock.js    # Bloque de código con syntax highlighting
│   └── LangGraphVisualizer.js  # Visualizador de grafos
├── modules/            # Módulos del currículo
│   └── module-a/       # Módulo A: LangGraph
├── assets/             # Estilos y recursos
└── templates/          # Plantillas descargables
```

## Desarrollo

### Agregar un Nuevo Módulo

1. Crear carpeta en `src/modules/module-x/`
2. Crear componente `ModuleX.js`
3. Agregar ruta en `App.js`
4. Actualizar navegación en `Header.js`

### Personalizar Estilos

Los estilos están en `src/assets/styles.css` usando CSS variables para facilitar el mantenimiento.

### Ejecutar Ejemplos de Python

Los ejemplos están en la carpeta `examples/`. Para ejecutar:

```bash
cd examples
python basic_agent.py
```

**Nota:** Necesitas configurar tu `OPENAI_API_KEY` en el archivo antes de ejecutar.

## Estado Actual

✅ **Completado:**
- Landing page responsivo
- Módulo A: Agentes en LangGraph (6 lecciones)
- Sistema de navegación y progreso
- Componentes base reutilizables

🚧 **En desarrollo:**
- Módulo B: Tools Seguras
- Módulo C: Memoria
- Módulo D: RAG Híbrido
- Módulo E: Evaluación
- Capstone final

## Contribuir

1. Fork del repositorio
2. Crear rama para nueva feature: `git checkout -b feature/nueva-feature`
3. Commit cambios: `git commit -m 'Add nueva feature'`
4. Push a la rama: `git push origin feature/nueva-feature`
5. Crear Pull Request

## Roadmap de Desarrollo

| Semana | Entregable | Estado |
|--------|------------|--------|
| 1 | Landing + Módulo A | ✅ Completado |
| 2 | Módulo B (Tools seguras) | 🔄 En progreso |
| 3 | Módulo C (Memoria) | ⏳ Pendiente |
| 4 | Módulo D (RAG híbrido) | ⏳ Pendiente |
| 5 | Módulo E (EvalOps local) | ⏳ Pendiente |
| 6 | Capstone final | ⏳ Pendiente |

## Soporte

Para preguntas o issues, usar el sistema de Issues de GitHub.
