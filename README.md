# AplicacionHotelParte2

Aplicación de escritorio para la gestión de un hotel, desarrollada en **Java** con **JavaFX** y construida con **Maven**. Es la segunda parte del proyecto de la aplicación de hotel.

## Descripción

HotelApp es una aplicación con interfaz gráfica que permite gestionar las operaciones básicas de un hotel (habitaciones, clientes y reservas). Tras la parte 1 hemos implementado un apartado para ver los ingresos generados entre días.


##  Funcionalidades

- Gestión de habitaciones
- Gestión de clientes
- Gestión de reservas
- Interfaz gráfica con JavaFX (FXML)



##  Tecnologías

| Tecnología | Versión |
|---|---|
| Java (JDK) | 21 |
| JavaFX (`javafx-controls`, `javafx-fxml`) | 21.0.4 |
| Maven | 3.8+ |
| javafx-maven-plugin | 0.0.8 |

##  Estructura del proyecto

```
AplicacionHotelParte2/
├── src/
│   └── main/          # Código fuente y recursos (clases Java, FXML...)
├── target/            # Archivos generados por la compilación de Maven
├── pom.xml            # Configuración de Maven y dependencias
└── README.md
```

##  Requisitos previos

- [JDK 21](https://adoptium.net/) o superior
- [Apache Maven](https://maven.apache.org/download.cgi) 3.8 o superior

Comprueba que están instalados:

```bash
java -version
mvn -version
```

## Instalación y ejecución

1. Clona el repositorio:

   ```bash
   git clone https://github.com/znx88/AplicacionHotelParte2.git
   cd AplicacionHotelParte2
   ```

2. Compila el proyecto:

   ```bash
   mvn clean compile
   ```

3. Ejecuta la aplicación (la clase principal es `Main`):

   ```bash
   mvn javafx:run
   ```

### Ejecutar desde un IDE

Importa el proyecto como proyecto Maven en IntelliJ IDEA, Eclipse o NetBeans y ejecuta la clase `Main`.

## Uso

1. Inicia la aplicación.
2. Navega por los menús de la interfaz para gestionar habitaciones, clientes y reservas.

