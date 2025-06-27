```mermaid
graph TD
    A[Higiene de los Alimentos] -->|Conjunto de condiciones y medidas necesarias para garantizar la seguridad y salubridad| B(Limpieza y Desinfección)
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
        F
        G
        C
        H
        J
        D
        K
        L
        E
        M
        N
        I
    end
