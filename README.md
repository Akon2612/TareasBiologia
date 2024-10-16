# TareasBiologia

```mermaid
graph LR
subgraph Definición de la Célula
    A(Unidad fundamental de vida):::green
    A --> B{Envoltura celular}
    A --> C{Citoplasma}
    A --> D{Material genético}
end

subgraph Postulados Teóricos
    E(Teoría Celular):::blue
    E --> F{Todos los organismos están compuestos por células}
    E --> G{La célula es la unidad básica de estructura y función}
    E --> H{Todas las células provienen de células preexistentes}
end

subgraph Teorias de la Evolución Celular
    I(Endosimbiosis):::orange
    I --> J{Origen de mitocondrias y cloroplastos}
    I --> K{Simbiosis entre células procariotas}
    L(Origen abiótico):::purple
    L --> M{Surgimiento de la vida a partir de materia inorgánica}
end

A --> E
E --> I
E --> L

classDef default fill:#ffffff,stroke:#333,stroke-width:1px,text-align:center,font-color:#000;
classDef green fill:#f0f,stroke:#333,stroke-width:2px,text-align:center,font-color:#000;
classDef blue fill:#cff,stroke:#333,stroke-width:2px,text-align:center,font-color:#000;
classDef orange fill:#ffc,stroke:#333,stroke-width:2px,text-align:center,font-color:#000;
classDef purple fill:#fcc,stroke:#333,stroke-width:2px,text-align:center,font-color:#000;
