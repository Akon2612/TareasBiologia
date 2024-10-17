# Biologia. Actividad 5.

```mermaid
graph LR
subgraph Definición de la Célula
    A(Unidad fundamental de vida)
    A --> B{Envoltura celular}
    A --> C{Citoplasma}
    A --> D{Material genético}
end

subgraph Postulados Teóricos
    E(Teoría Celular)
    E --> F{Todos los organismos están compuestos por células}
    E --> G{La célula es la unidad básica de estructura y función}
    E --> H{Todas las células provienen de células preexistentes}
end

subgraph Teorías de la Evolución Celular
    I(Endosimbiosis)
    I --> J{Origen de mitocondrias y cloroplastos}
    I --> K{Simbiosis entre células procariotas}
    L(Origen abiótico)
    L --> M{Surgimiento de la vida a partir de materia inorgánica}
end

A --> E
E --> I
E --> L

classDef default fill:#ffffff,stroke:#333,stroke-width:1px;
