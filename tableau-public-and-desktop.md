# 🆓 Tableau Public and Desktop

### Tableau Public
- Free version of Tableau.
- Allows creation and sharing of visualizations publicly on Tableau's server.
- Limited to public data sources; cannot connect to private databases or local files.
- Workbooks are saved online and accessible to anyone.
- Ideal for learning, sharing public data insights, and building a portfolio.

### Tableau Desktop
- Paid software with full functionality.
- Supports connections to a wide range of data sources, including private databases, spreadsheets, and cloud services.
- Workbooks can be saved locally or published to Tableau Server/Online.
- Includes advanced features like data blending, custom calculations, and integration with R/Python.
- Suitable for professional data analysis and enterprise use.

### Key Differences
| Aspect          | Tableau Public | Tableau Desktop |
|-----------------|----------------|-----------------|
| **Cost**        | Free          | Paid License   |
| **Data Privacy**| Public Sharing| Private Handling|
| **Features**    | Basic         | Advanced       |
| **Storage**     | Online Only   | Local/Server   |

## Feature Comparison Diagram

```mermaid
graph TD
    A[Tableau Products] --> B[Tableau Public]
    A --> C[Tableau Desktop]
    
    B --> D[Free]
    B --> E[Public Sharing]
    B --> F[Basic Features]
    B --> G[Online Storage]
    B --> H[Learning/Portfolio]
    
    C --> I[Paid License]
    C --> J[Private Data]
    C --> K[Advanced Features]
    C --> L[Local/Server Storage]
    C --> M[Professional Use]
    
    style B fill:#e8f5e8
    style C fill:#e3f2fd
```

## Data Source Connectivity

```mermaid
graph TD
    A[Data Sources] --> B[Tableau Public]
    A --> C[Tableau Desktop]
    
    B --> D[Public Data Only]
    D --> E[Web Data Connectors]
    D --> F[Public APIs]
    D --> G[Sample Datasets]
    
    C --> H[All Data Sources]
    H --> I[Databases]
    H --> J[Spreadsheets]
    H --> K[Cloud Services]
    H --> L[Big Data]
    H --> M[Private APIs]
    
    style B fill:#fff3e0
    style C fill:#f3e5f5
```

## Use Case Flowchart

```mermaid
flowchart TD
    A[Choose Tableau Version] --> B{Primary Use Case?}
    
    B -->|Learning & Portfolio| C[Tableau Public]
    B -->|Professional Analysis| D[Tableau Desktop]
    B -->|Enterprise Deployment| E[Tableau Server/Online]
    
    C --> F[Free Access]
    C --> G[Public Sharing]
    C --> H[Basic Visualizations]
    
    D --> I[Paid License Required]
    D --> J[Private Data Access]
    D --> K[Advanced Analytics]
    
    E --> L[Server Infrastructure]
    E --> M[Team Collaboration]
    E --> N[Enterprise Security]
    
    style C fill:#c8e6c9
    style D fill:#bbdefb
    style E fill:#d1c4e9
```