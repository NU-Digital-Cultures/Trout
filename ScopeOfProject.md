``` mermaid
flowchart TD
    B(The 'Tenant Talk' app fa:fa-handshake: our campaign developed for HtN)
    B --> C{Data-based advocacy approach}
    C -->|Quantitative data| D[fa:fa-map Interactive map using Leaflet, using data sourced from: ?]
    C -->|Qualitative data| E[fa:fa-paintbrush Tenants' real-life stories and experiences of renting]
    C -->|Data submissions process| F[fa:fa-file-alt Tenants upload personal submissions via the app]
    D ---> G[Embedded into Figma, our platform for creating our app] 
    E ---> G
