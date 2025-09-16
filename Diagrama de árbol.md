```mermaid
graph TD
    A[Lanzamiento 1] --> B(Cara)
    A --> C(Cruz)
    B --> D(Cara)
    B --> E(Cruz)
    C --> F(Cara)
    C --> G(Cruz)
    D --> H(Cara)
    D --> I(Cruz)
    E --> J(Cara)
    E --> K(Cruz)
    F --> L(Cara)
    F --> M(Cruz)
    G --> N(Cara)
    G --> O(Cruz)
    
    subgraph Espacio Muestral
        H(CCC)
        I(CCX)
        J(CXC)
        K(CXX)
        L(XCC)
        M(XCX)
        N(XXC)
        O(XXX)
    end
    D --> H & I
    E --> J & K
    F --> L & M
    G --> N & O
