# TTC
Trash To Cash
```
## 📁 TTC-Repository (Wurzelverzeichnis)
│
├── 📄 .nojekyll                <-- Schaltet den Jekyll-Compiler auf GitHub Pages ab
├── 📄 index.html               <-- DIE HAUPTSCHALTZENTRALE (Login, Fiat-Kalkulator, Brücken-Button)
│
├── 📁 python/                  <-- DAS PYTHON-BACKEND (Echte Kryptografie & SHA-256 Engine)
│   └── 📄 core_engine.py       <-- Zentrale Python-Datei für Seed-Generierung & Bilanz-Abgleich
│
├── 📁 src/                     <-- DER SRC-ORDNER (Zentrale Source-Dateien & Komponenten)
│   ├── pzqqet_master_node.py
│   ├── codeql.v1.py 
│   ├── codeql.v2.py 
│   ├── codeql.v3.py 
│   └── 📄 matrix_core.js       <-- Gemeinsame Logik für Ledger, UI-Sichtbarkeit und States
│
├── 📁 net/                     <-- EBENE 1: DIE KRYPTO-BLOCKCHAIN (.net)
│   └── 📄 index.html           <-- Krypto-Handelsdeck & Trading
│
├── 📁 dev/                     <-- EBENE 2: DIE SYSTEM-BLOCKCHAIN (.dev)
│   └── 📄 index.html           <-- Admin-Terminal & System-Status
│
├── 📁 app/                     <-- EBENE 3: DIE AI-BLOCKCHAIN (.app)
│   └── 📄 index.html           <-- Silent-Matrix & Konsens-Schicht
└── pzqqet_master_node.py
```
