graph TD 
    A["Jabez Jena<br/>AI & Full Stack Developer"] --> B{Artificial Intelligence} 
    A --> C{Full Stack Development} 
    A --> D{Guiding Principles}

    subgraph AI/ML
        B --> B1[Python]
        B --> B2[TensorFlow]
        B --> B3[Deep Learning / CNNs]
    end

    subgraph Full Stack
        C --> C1[React.js]
        C --> C2[Node.js / Express]
        C --> C3[MongoDB]
        C --> C4[Tailwind CSS]
    end

    subgraph Principles
        D --> D1[Scalable Architecture]
        D --> D2[Data-Driven Decisions]
        D --> D3[User-Centric Design]
    end

    subgraph Projects
        P1["Cellence AI<br/>(AI Drug Discovery)"]
        P2["ResQnet<br/>(AI Disaster Management)"]
        P3["Zaymazone<br/>(E-commerce Platform)"]
    end

    style A fill:#0e75b6,stroke:#fff,stroke-width:2px,color:#fff
    style P1 fill:#1a1a1a,stroke:#0e75b6,stroke-width:2px,color:#fff
    style P2 fill:#1a1a1a,stroke:#0e75b6,stroke-width:2px,color:#fff
    style P3 fill:#1a1a1a,stroke:#0e75b6,stroke-width:2px,color:#fff

    B1 --> P1
    B2 --> P1
    B3 --> P1

    C1 --> P2
    C2 --> P2
    C3 --> P2

    C1 --> P3
    C2 --> P3
    C3 --> P3
    C4 --> P3

    click P1 "https://github.com/JabezJesudasonJena/Cellence-Drug-Discovery-model" "View Project"
    click P2 "https://jabezjesudasonjena.github.io/ResQnet/" "View Live Demo"
