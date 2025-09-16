```mermaid
graph TD
    A[Tamaño] --> B(Pequeña)
    A --> C(Grande)
    B --> D(Chocolate)
    B --> E(Vainilla)
    B --> F(Fresa)
    C --> G(Chocolate)
    C --> H(Vainilla)
    C --> I(Fresa)

    subgraph Combinaciones
        D(Pequeña, Chocolate)
        E(Pequeña, Vainilla)
        F(Pequeña, Fresa)
        G(Grande, Chocolate)
        H(Grande, Vainilla)
        I(Grande, Fresa)
    end
    B --> D & E & F
    C --> G & H & I
