# 🛠️ Scripts de Pentesting

Colección de scripts personalizados para automatizar tareas comunes de pentesting, enumeración y post-explotación.

## 📂 Estructura

```
scripts/
├── enumeration/
│   ├── port-scan.py
│   └── subdomain-enum.sh
├── exploitation/
│   ├── reverse-shell.py
│   └── payload-gen.sh
├── post-exploitation/
│   ├── priv-esc.py
│   └── persistence.sh
└── utilities/
    └── report-gen.py
```

## 🚀 Categorías

### Enumeración
- Escaneo de puertos
- Enumeración de subdominios
- Fuzzing de directorios
- Enumeración de servicios

### Explotación
- Generadores de payloads
- Reverse shells
- Inyección SQL
- XSS

### Post-Explotación
- Escalada de privilegios
- Persistencia
- Recolección de datos
- Movimiento lateral

## 💻 Lenguajes Utilizados
- Python 3.x
- Bash
- PowerShell
- Ruby

## 📋 Requisitos

```bash
# Python packages
pip install -r requirements.txt

# Herramientas necesarias
sudo apt install nmap
sudo apt install gobuster
```

## 🔧 Uso

### Ejemplo de script de enumeración:
```bash
./enumeration/port-scan.py -t 192.168.1.1 -p 1-1000
```

### Ejemplo de generación de payload:
```bash
./exploitation/payload-gen.sh -i eth0 -p 4444
```

## 📌 Buenas Prácticas

1. Todos los scripts deben incluir:
   - Documentación clara
   - Manejo de errores
   - Opciones de ayuda (-h, --help)
   - Control de versiones

2. Formato estándar:
```python
#!/usr/bin/env python3
"""
Nombre: Script de ejemplo
Autor: Tu nombre
Versión: 1.0
Descripción: Breve descripción del script
"""

def main():
    # Código principal
    pass

if __name__ == "__main__":
    main()
```

## 🔒 Seguridad

- No incluir credenciales en los scripts
- Usar variables de entorno para datos sensibles
- Validar inputs
- Manejar excepciones
- Seguir principio de mínimo privilegio

## 🤝 Contribuciones

1. Fork el repositorio
2. Crea una rama (`git checkout -b feature/script-nuevo`)
3. Commit tus cambios (`git commit -m 'Agrega nuevo script'`)
4. Push a la rama (`git push origin feature/script-nuevo`)
5. Abre un Pull Request

### Template para nuevos scripts:
```markdown
## Nombre del Script
- **Propósito**: Breve descripción
- **Uso**: Ejemplo de uso
- **Requisitos**: Dependencias necesarias
- **Notas**: Información adicional
```

## ⚠️ Disclaimer

Estos scripts son para uso educativo y ético. No me hago responsable del mal uso de estas herramientas.

## 📚 Referencias

- [Python Documentation](https://docs.python.org/3/)
- [Bash Scripting Guide](https://tldp.org/LDP/abs/html/)
- [PowerShell Documentation](https://docs.microsoft.com/en-us/powershell/)
