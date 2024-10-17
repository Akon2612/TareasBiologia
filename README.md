# Biologia. Actividad 4.

```mermaid
¡Absolutamente! Vamos a transformar ese código en un mapa conceptual más visual y representativo.

Comencemos por analizar lo que queremos mejorar:

Visualización: Queremos que el mapa se vea más como un mapa conceptual tradicional, con ramas y jerarquías claras.
Detalles: Podemos agregar más nodos y enlaces para profundizar en cada tema.
Estilo: Podemos personalizar el estilo del mapa con colores, formas y tamaños de los nodos.
Aquí te presento una nueva versión del código, con algunas modificaciones:

Fragmento de código
graph LR
    subgraph Definición de la Célula
        A(Unidad fundamental de vida) --> B{Procariotas}
        A --> C{Eucariotas}
    end

    subgraph Teoría Celular
        D[Todos los seres vivos están compuestos por células] --> E(Célula es la unidad básica estructural)
        D --> F(Célula es la unidad básica funcional)
        D --> G(Toda célula proviene de otra célula preexistente)
    end

    subgraph Teorías de la Evolución Celular
        H(Teoría Endosimbiótica) --> I{Origen de mitocondrias y cloroplastos}
        J(Selección Natural) --> K{Adaptación y supervivencia}
    end

    subgraph Postulados Teóricos
        L((Teoría Celular)) --> M((Teoría Endosimbiótica))
        L --> N((Selección Natural))
    end

    classDef default fill:#fff,stroke:#000,stroke-width:1px;
    classDef highlighted fill:#f9f,stroke:#000,stroke-width:2px;

    class D,E,F,G highlighted
