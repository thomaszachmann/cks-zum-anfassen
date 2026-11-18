# CKS zum Anfassen – Begleitcode

Begleitcode zum Buch **CKS zum Anfassen** – Certified Kubernetes Security Specialist,
praxisnahe Prüfungsvorbereitung. Teil der Reihe IT-Trainingslager von Thomas Zachmann.

Buchseite: https://it-trainingslager.de/buecher/cks

## Inhalt

- `notes-api/` – kleine Go-API (Go 1.27), die du im Buch selbst als Image baust,
  minimierst, scannst, signierst und abgesichert betreibst.

Alle Schlüssel und Passwörter im Buch (z. B. `lab-key-123`) sind Laborwerte – nie in
Produktion verwenden.

Getestet mit kubeadm v1.37.1/v1.37.2, containerd v2.4.2, Cilium 1.20.5 und podman 4.9.3
auf Ubuntu 24.04.

## Schnellstart

```bash
git clone https://github.com/thomaszachmann/cks-zum-anfassen
cp -r cks-zum-anfassen/notes-api ~/cks/notes-api
```

## Hinweis

Dieses Projekt steht in keiner Verbindung zur Linux Foundation oder zur CNCF. CKS ist
eine Marke der Linux Foundation.
