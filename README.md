# Biologia. Actividad 4.

```mermaid
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

    style all text/font-color:#000;
