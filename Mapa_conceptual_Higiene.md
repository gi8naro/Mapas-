graph TD
    A[Higiene de los Alimentos] -->|Conjunto de condiciones y medidas para garantizar la seguridad y salubridad| B(Limpieza y Desinfección)
    A -->|Se previene mediante| C(Contaminación de los Alimentos)
    A -->|Apoya a| D(Control Microbiológico de los Alimentos)
    A -->|Componente clave de| E(Manipulación de Alimentos)

    B -->|Forma parte de| A
    B -->|Complementa a| F(Limpieza)
    B -->|Sigue a| G(Desinfección)

    C -->|Tipo de| H(Contaminación Cruzada)
    C -->|Consecuencia de| I(Enfermedades Transmitidas por Alimentos - ETA)

    J(Higiene Personal) -->|Influye en| K(Preparación de Alimentos)
    K -->|Puede causar| C
    K -->|Afectada por| J

    L(Almacenamiento de Alimentos) -->|Puede prevenir| C

    E -->|Regulan| M(Normas Sanitarias)
    M -->|Garantizan cumplimiento de| N(Inspección, Verificación y Certificación)

    subgraph Detalles
        F[Limpieza]:::definition
        G[Desinfección]:::definition
        C[Contaminación de los Alimentos]:::definition
        H[Contaminación Cruzada]:::definition
        J[Higiene Personal]:::definition
        D[Control Microbiológico de los Alimentos]:::definition
        K[Preparación de Alimentos]:::definition
        L[Almacenamiento de Alimentos]:::definition
        E[Manipulación de Alimentos]:::definition
        M[Normas Sanitarias]:::definition
        N[Inspección, Verificación y Certificación]:::definition
        I[Enfermedades Transmitidas por Alimentos (ETA)]:::definition
    end

    classDef definition fill:#f9f,stroke:#333,stroke-width:2px;
