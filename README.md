# 🧪 Selenium-Cucumber Automation Project

Este es un proyecto de automatización de pruebas web utilizando **Selenium WebDriver**, **Cucumber**, y **TestNG** en **Java**.

---

## 🚀 Tecnologías utilizadas

- 💻 Java 17+
- 🧪 Selenium WebDriver
- 🍋 Cucumber
- 🧪 TestNG
- ⚙️ Gradle
- 💡 WebDriverManager

---

## 🗂️ Estructura del proyecto

```
src
├── test
│   └── java
│       ├── pages                # Clases con Page Objects
│       ├── runner               # Clase runner con Cucumber y TestNG
│       └── selenium/cucumber    # Steps definitions
│
└── resources
    └── features                 # Archivos .feature de Cucumber
```

---

## ▶️ ¿Cómo correr los tests?

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/GonzaloArrieta/selenium-cucumber.git
   cd selenium-cucumber
   ```

2. Ejecutar con Gradle:
   ```bash
   ./gradlew clean test
   ```

3. Ver reportes de TestNG en `test-output/index.html`.

---

## 📸 Evidencias de prueba

Se generan automáticamente capturas de pantalla en caso de fallos o validaciones importantes (ver carpeta `test-output/`).

---

## 🧠 Autor

**Gonzalo Arrieta**  
 Proyecto inicial para aprendizaje y buenas prácticas con Selenium + Cucumber.

---

## ⭐ ¿Te sirvió?

¡Rompete esa ⭐ al repo!
Abrí un issue o hacé un fork si querés colaborar.
