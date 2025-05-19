# 📧 Gestor de Correos POP3 - Proyecto del Curso
**📝 Descripción del Proyecto**

Este proyecto tiene como objetivo implementar un gestor de correos básico utilizando el protocolo POP3 de Python. Se desarrollará una aplicación que permita conectarse a servidores de correo, descargar mensajes y realizar operaciones básicas de gestión.

### 🎯 Objetivos de Aprendizaje

- Implementar funcionalidades de red usando la librería `poplib` de Python
- Trabajar con metodologías de desarrollo colaborativo (Git/GitHub)
- Aplicar principios de modularidad en Python


## 🏗️ Estructura del Proyecto

```
mail-controller/
├── src/
│   └── mail/
│       ├── mail.py        # Lógica principal y entrada
│
├── /tests/                  
│   ├── test.py
├── pyproject.toml         # Configuración del paquete
├── README.md              # Este archivo
└── .gitignore             # Archivos a ignorar
```

---

## ⚡ Funcionalidades del Proyecto

- [ ] **Conexión POP3**: Establecer conexión segura con servidor de correo
- [ ] **Autenticación**: Login con usuario y contraseña
- [ ] **Listar mensajes**: Mostrar lista de correos en el servidor
- [ ] **Descargar mensaje**: Obtener el contenido de un email específico
- [ ] **Mostrar inbox**: Visualizar bandeja de entrada por consola
- [ ] **Cerrar conexión**: Terminar sesión de forma segura


## 🚀 Cómo Empezar

### 1. Clonar el Repositorio

```bash
git clone https://github.com/ACMUD/mail-controller
cd mail-controller
```

### 2. Configurar el Entorno

```bash
# Crear entorno virtual
python -m venv venv

# Activar entorno virtual
# En Windows:
venv\Scripts\activate
# En Linux/Mac:
source venv/bin/activate

# Instalar dependencias
pip install -r requirements.txt
```

## 💻 Metodología de Trabajo

### 🔄 Flujo de Trabajo con Git

1. **Crear una rama** para cada nueva funcionalidad:
   ```bash
   git checkout -b feature/nombre-funcionalidad
   ```

2. **Realizar commits** pequeños y descriptivos:
   ```bash
   git add .
   git commit -m \"feat: implementar conexión POP3 básica\"
   ```

3. **Subir la rama** al repositorio remoto:
   ```bash
   git push origin feature/nombre-funcionalidad
   ```

4. **Crear Pull Request** en GitHub para revisión

### 📝 Convención de Commits

Seguimos el estándar de [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` nueva funcionalidad
- `fix:` corrección de errores
- `docs:` cambios en documentación
- `test:` agregar o modificar tests
- `refactor:` refactorización de código

**Ejemplos:**
```
feat: agregar método para descargar mensajes
fix: corregir error de conexión SSL
docs: actualizar README con ejemplos
test: agregar tests para clase Message
```

### 🌿 Estrategia de Ramas

- `main`: rama principal (código estable)
- `develop`: rama de desarrollo (integración)
- `feature/`: ramas para nuevas funcionalidades

### 📋 Pull Requests

Cada PR debe incluir:

1. **Descripción clara** de los cambios realizados
2. **Documentación** actualizada si es necesario
3. **Revisión** de al menos un compañero

#### Template para PR:

```markdown
## Descripción
Breve descripción de los cambios realizados.

## Tipo de cambio
- [ ] Nueva funcionalidad
- [ ] Corrección de error
- [ ] Refactorización
- [ ] Actualización de documentación

## Checklist
- [ ] Mi código sigue el estilo del proyecto
- [ ] He realizado una auto-revisión
- [ ] He comentado el código en áreas complejas
- [ ] Mis cambios no generan nuevas advertencias
```

---

### 💡 Consejos para Contribuir:

- Leer el código existente antes de empezar
- Mantener tus PRs pequeños y enfocados
- Documentar funciones complejas
- Pedir ayuda si hay complicaciones


## 📚 Recursos Adicionales

### Documentación Oficial:
- [Python poplib](https://docs.python.org/3/library/poplib.html)
- [Email package](https://docs.python.org/3/library/email.html)
- [Git Documentation](https://git-scm.com/doc)


## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

---

*¡Happy coding! 🐍📧*