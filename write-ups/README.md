# 📝 Write-ups de Máquinas

Esta carpeta contiene documentación detallada de las máquinas resueltas en plataformas como HackTheBox y TryHackMe, siguiendo el roadmap de aprendizaje.

## 📂 Estructura

```
write-ups/
├── hackthebox/
│   ├── starting-point/
│   │   ├── meow.md
│   │   └── fawn.md
│   └── easy/
├── tryhackme/
│   ├── basics/
│   └── easy/
└── templates/
    └── machine-template.md
```

## 🎯 Progreso

- **HackTheBox**
  - Starting Point: 0/2
  - Easy: 0/10
  - Medium: 0/5
  
- **TryHackMe**
  - Basics: 0/5
  - Easy: 0/10

![Progress](https://img.shields.io/badge/Máquinas%20Resueltas-0%2F50-green)

## 📚 Categorías

Las máquinas están categorizadas por:
- Sistema Operativo (Linux/Windows)
- Vectores de ataque principales
- Técnicas de escalada de privilegios
- Dificultad

## ✍️ Formato

Cada write-up incluye:
- Información básica de la máquina
- Reconocimiento inicial
- Vectores de entrada encontrados
- Proceso de explotación
- Escalada de privilegios
- Herramientas utilizadas
- Lecciones aprendidas
- Screenshots relevantes

## 🔍 Índice de Técnicas

- **Enumeración**
  - Nmap
  - Gobuster
  - SMB
  
- **Explotación**
  - SQL Injection
  - Remote Code Execution
  - File Upload
  
- **Escalada de Privilegios**
  - SUID Binaries
  - Kernel Exploits
  - Misconfigured Services

## 🚀 Máquinas Destacadas

| Nombre | Plataforma | Dificultad | Técnicas Principales |
|--------|------------|------------|---------------------|
| Meow   | HTB        | Very Easy  | Telnet             |
| Fawn   | HTB        | Very Easy  | FTP                |

## 📌 Guías de Contribución

1. Usa el template proporcionado en `/templates/machine-template.md`
2. Incluye screenshots claros y relevantes
3. Documenta todos los intentos, incluso los fallidos
4. Explica las lecciones aprendidas
5. Mantén la información organizada y clara

## ⚠️ Disclaimer

Estos write-ups son para propósitos educativos. Las soluciones se publican solo cuando las máquinas son retiradas (HTB) o con el permiso correspondiente (THM).

## 🔗 Enlaces Útiles

- [ROADMAP.md](../ROADMAP.md) - Plan de estudio detallado
- [scripts/](../scripts/) - Scripts útiles para pentesting
- [resources/](../resources/) - Recursos adicionales
