# Themes & Icons

> Installation and configuration guide for GTK themes and icons for Linux.

Customize your Linux desktop in a simple and modern way.

### Distributions

- Debian
- Arch Linux
- Fedora

### Themes

- Orchis
- Layan
- Nordic
- Sweet
- New-Flavor

### Icons

- Papirus
- Tela
- Reversal
- Qogir

---

## 01 · Dependencies

Before installing the themes and icons, install the tools necessary to download and compile some of the projects.

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

# Themes GTK

## 02 · Orchis

### Debian

Install the dependencies: 

```bash
sudo apt install sassc libgtk-3-dev gtk2-engines-murrine
```

Clone the repository:

```bash
git clone https://github.com/vinceliuice/Orchis-theme.git
```

Enter the directory:

```bash
cd Orchis-theme
```

Install:

```bash
./install.sh
```

### Arch Linux

Install the dependencies:

```bash
sudo pacman -S sassc gtk3 gtk-engine-murrine
```

Clone the repository:

```bash
git clone https://github.com/vinceliuice/Orchis-theme.git
```

Enter the directory:

```bash
cd Orchis-theme
```

Install:

```bash
./install.sh
```

### Fedora

Install the dependencies:

```bash
sudo dnf install sassc gtk-murrine-engine
```

Clone the repository:

```bash
git clone https://github.com/vinceliuice/Orchis-theme.git
```

Enter the directory:

```bash
cd Orchis-theme
```

Install:

```bash
./install.sh
```
### To be continued
