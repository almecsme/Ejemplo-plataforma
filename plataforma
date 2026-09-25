graph TD
    %% Definición de Estilos de Áreas
    subgraph Comercial [ÁREA COMERCIAL / INGRESO]
        A[Interés del Usuario] --> B(Registro de Datos / Lead)
        B --> C[Asesoría y Selección del Curso]
    end

    subgraph Financiero [ÁREA FINANCIERA]
        C --> D[Generación de Costos o Cotización]
        D --> E{¿Pago Exitoso / Acuerdo Firmado?}
        E -- No --> D
    end

    subgraph Academico [ÁREA ACADÉMICA]
        E -- Sí --> F[Creación Automática de Cuenta]
        F --> G[Activación del Curso en Aula Virtual]
        G --> H([Ingreso del Estudiante a Clases])
    end

    %% Estilos Visuales
    style Comercial fill:#e6f3ff,stroke:#0066cc,stroke-width:2px
    style Financiero fill:#fff2cc,stroke:#d6b656,stroke-width:2px
    style Academico fill:#e2f0d9,stroke:#385723,stroke-width:2px
