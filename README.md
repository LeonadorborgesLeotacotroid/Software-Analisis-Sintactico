Instala las dependencias:

bash
Copiar
Editar
pip install ply
Ejecuta el intérprete:

bash
Copiar
Editar
python main.py
💻 Uso Básico
El intérprete ofrece un REPL (Read-Eval-Print Loop) interactivo:

shell
Copiar
Editar
subliminal666> x = 5 + 3;
subliminal666> imprimir(x);
8
subliminal666> si x > 0 hacer imprimir("Positivo"); fin
Positivo
Opciones especiales:

-v: Muestra los tokens generados (modo verbose)

-d: Modo depuración (próximamente)

salir: Termina la ejecución

📚 Ejemplos
Asignación y operaciones matemáticas:

bash
Copiar
Editar
subliminal666> a = 10;
subliminal666> b = a * 2 - 5;
subliminal666> imprimir(b);
15
Estructuras condicionales:

bash
Copiar
Editar
subliminal666> edad = 18;
subliminal666> si edad >= 18 hacer
           >    imprimir("Mayor de edad");
           > sino hacer
           >    imprimir("Menor de edad");
           > fin
Mayor de edad
Bucles:

bash
Copiar
Editar
subliminal666> contador = 0;
subliminal666> mientras contador < 3 hacer
           >    imprimir("Iteración: " + contador);
           >    contador = contador + 1;
           > fin
Iteración: 0  
Iteración: 1  
Iteración: 2
🏗️ Estructura del Proyecto
bash
Copiar
Editar
subliminal666/
├── lexico.py      # Analizador léxico (tokenizer)
├── sintactico.py  # Analizador sintáctico (parser)
├── main.py        # Interfaz principal del intérprete
└── README.md      # Este archivo
📝 Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
