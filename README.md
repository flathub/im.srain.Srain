# Srain

___Modern IRC___

Modern IRC client written in GTK

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub im.srain.Srain
flatpak run im.srain.Srain
```

## Building

```bash
git clone git@github.com:flathub/im.srain.Srain.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install im.srain.Srain.yaml
```

---

**Technologies**: GNOME, GTK4, C
