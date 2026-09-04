# Themes & Icons

> Guía de instalación y configuración de temas GTK e iconos para Linux.

Personaliza el escritorio Linux de una forma sencilla y moderna.

### Distribuciones

- Debian
- Arch Linux
- Fedora

### Temas

- Orchis
- Layan
- Nordic
- Sweet
- New-Flavor

### Iconos

- Papirus
- Tela
- Reversal
- Qogir

---

## 01 · Dependencias

Antes de instalar los temas e iconos, instala las herramientas necesarias para descargar y compilar algunos de los proyectos.

### Debian

```bash
sudo apt update
sudo apt install git
```

### Arch Linux

```bash
sudo pacman -S git
```

### Fedora

```bash
sudo dnf install git
```

---

# Temas GTK

## 02 · Orchis

### Debian

Instala las dependencias:

```bash
sudo apt install sassc libgtk-3-dev gtk2-engines-murrine
```

Clona el repositorio:

```bash
git clone https://github.com/vinceliuice/Orchis-theme.git
```

Entra en el directorio:

```bash
cd Orchis-theme
```

Instala el tema:

```bash
./install.sh
```

### Arch Linux

Instala las dependencias:

```bash
sudo pacman -S sassc gtk3 gtk-engine-murrine
```

Clona el repositorio:

```bash
git clone https://github.com/vinceliuice/Orchis-theme.git
```

Entra en el directorio:

```bash
cd Orchis-theme
```

Instala:

```bash
./install.sh
```

### Fedora

Instala las dependencias:

```bash
sudo dnf install sassc gtk-murrine-engine
```

Clona el repositorio:

```bash
git clone https://github.com/vinceliuice/Orchis-theme.git
```

Entra en el directorio:

```bash
cd Orchis-theme
```

Instala:

```bash
./install.sh
```
