# Procesos-Tecnol-gicos
graph TD
    A[Materia Prima: Cacahuate Concasse/Entero] --> B[1. Selección y Limpieza]
    B --> C[2. Tostado Previo de la Almendra]
    
    subgraph "Proceso de Enrobrado / Cobertura"
    C --> D[3. Bombo Enrobrador Tambor Giratorio]
    E[Jarabe Binder: Agua + Azúcar + Sal + Almidón] --> D
    F[Mezcla Seca: Harina de Trigo + Fécula de Maíz] --> D
    D --> G[Asperjado alternado de jarabe y polvo en capas sucesivas]
    G --> H[Formación del cascarón crocante]
    end

    H --> I[4. Calibración y Tamizado]
    I --> J[5. Horneado y Secado Continuo]
    
    subgraph "Transformaciones Químicas y Texturización"
    J --> K[Deshidratación de la corteza]
    J --> L[Gelatinización de almidones]
    J --> M[Reacción de Maillard caramelización]
    end

    K --> N[6. Sazonado y Glaseado]
    L --> N
    M --> N
    O[Salsa de Soja + Glutamato + Chile/Colorante] --> N

    N --> P[7. Enfriamiento Controlled]
    P --> Q[8. Control de Calidad y Humedad Residual]
    Q --> R[9. Empacado Automatizado con Atmósfera Modificada / Se
