```powershell
Microsoft Windows [Version 10.0.22631.3880]
(c) Microsoft Corporation. All rights reserved.

PS C:\Users\joem> whoami.exe

Name:    Joem
Status:  Software Engineer (Graduating Soon)
Profile: Results-oriented, decisive builder
Focus:   High-performance backend architecture & typed modern frontends

PS C:\Users\joem> Get-TechStack | Format-Table

Category               Technologies
--------               ------------
Core Backend           Python, C++, FastAPI, Pydantic
Data & Storage         PostgreSQL, SQLAlchemy, Alembic
Frontend               React, TypeScript
Ops & Orchestration    Docker, Docker Compose, n8n, WSL

PS C:\Users\joem> cat .\SystemDesign_Philosophy.txt

I build systems based on trade-offs and delegation. I combine Python and FastAPI for rapid API routing, while
delegating CPU-heavy mathematical computations to C++ (via pybind11) for lightning-fast execution. I utilize
n8n for automated workflow orchestration and strictly enforce type safety across the entire stack using
TypeScript on the client and Pydantic on the server.

PS C:\Users\joem> dir .\Projects

    Directory: C:\Users\joem\Projects

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        07/26/2026  09:41 PM      1,248,768 GYRSystem_NLP.exe
                                              Resume parsing system using TF-IDF, SBERT, XGBoost
-a----        07/30/2026  11:08 AM        842,240 Quant_StockTracker.dll
                                              Live market tracker using Python ingestion, C++ math

PS C:\Users\joem> ping portfolio -t

Pinging joemzkie.github.io [185.199.108.153] with 32 bytes of data:
Reply from 185.199.108.153: bytes=32 time=21ms TTL=56
Reply from 185.199.108.153: bytes=32 time=19ms TTL=56
Reply from 185.199.108.153: bytes=32 time=20ms TTL=56
Reply from 185.199.108.153: bytes=32 time=18ms TTL=56

Portfolio endpoint: https://joemzkie.github.io/Portfolio---joem/
```

[Open my portfolio](https://joemzkie.github.io/Portfolio---joem/)
