# 💻 Desktop Installation

### System Requirements
- **Operating System**: Windows 7 or later, macOS 10.12 or later.
- **Processor**: Intel or AMD 64-bit processor.
- **RAM**: At least 2 GB (4 GB recommended).
- **Disk Space**: 1.5 GB free space.
- **Internet**: Required for activation and updates.

### Installation Steps
1. Visit the [Tableau Downloads Page](https://www.tableau.com/products/desktop/download).
2. Select your operating system (Windows or Mac) and download the installer.
3. Run the downloaded file as an administrator (Windows) or open the .dmg file (Mac).
4. Follow the on-screen instructions to install.
5. Enter your product key if you have a paid license, or sign in with your Tableau account.
6. Launch Tableau Desktop and start creating visualizations!

### Troubleshooting
- Ensure your system meets the requirements.
- Disable antivirus temporarily if installation fails.
- Contact Tableau Support for license issues.

## Installation Process Flowchart

```mermaid
flowchart TD
    A[Start Installation] --> B[Check System Requirements]

    B --> C{Requirements Met?}
    C -->|No| D[Update System]
    C -->|Yes| E[Download Installer]

    D --> B
    E --> F[Visit Tableau Website]
    F --> G[Select OS Version]
    G --> H[Download Installer File]

    H --> I[Run Installer]
    I --> J{Operating System?}

    J -->|Windows| K[Run as Administrator]
    J -->|Mac| L[Open .dmg File]

    K --> M[Follow Installation Wizard]
    L --> M

    M --> N[Accept License Agreement]
    N --> O[Choose Install Location]
    O --> P[Install Components]

    P --> Q{Product Type?}
    Q -->|Paid License| R[Enter Product Key]
    Q -->|Free Trial| S[Sign In/Create Account]

    R --> T[Activate License]
    S --> T

    T --> U[Installation Complete]
    U --> V[Launch Tableau Desktop]
    V --> W[Start Creating Visualizations]

    style A fill:#e8f5e8
    style W fill:#c8e6c9
```

## System Requirements Check

```mermaid
graph TD
    A[System Requirements] --> B[Operating System]
    A --> C[Processor]
    A --> D[RAM]
    A --> E[Disk Space]
    A --> F[Internet Connection]

    B --> G[Windows 7+ or macOS 10.12+]
    C --> H[64-bit Intel/AMD]
    D --> I[2GB minimum, 4GB recommended]
    E --> J[1.5GB free space]
    F --> K[Required for activation]

    style A fill:#fff3e0
    style G fill:#e8f5e8
    style H fill:#e8f5e8
    style I fill:#e8f5e8
    style J fill:#e8f5e8
    style K fill:#fff9c4
```

## Troubleshooting Decision Tree

```mermaid
flowchart TD
    A[Installation Issue] --> B{What is the problem?}

    B -->|Download Failed| C[Check Internet Connection]
    B -->|Installation Fails| D[Check System Requirements]
    B -->|License Issues| E[Verify Product Key]
    B -->|Launch Problems| F[Check Antivirus Settings]

    C --> G[Retry Download]
    D --> H[Update System/OS]
    E --> I[Contact Tableau Support]
    F --> J[Disable Antivirus Temporarily]

    G --> K[Installation Success]
    H --> K
    I --> K
    J --> K

    style A fill:#ffebee
    style K fill:#e8f5e8
```