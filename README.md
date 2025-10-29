# Crear directorio y estructura
mkdir system_monitor
cd system_monitor

# Crear estructura de carpetas
mkdir src include

# Crear archivos en src/
touch src/main.c
touch src/cpu_info.c
touch src/memory_info.c
touch src/system_info.c
touch src/tui.c

# Crear archivos en include/
touch include/monitor.h
touch include/tui.h

# Crear archivos raíz
touch Makefile
touch README.md
touch .gitignore
