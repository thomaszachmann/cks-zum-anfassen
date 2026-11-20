# CKS hands-on – Companion Code

Companion code for the book **CKS hands-on** (German edition: *CKS zum Anfassen*) – Certified
Kubernetes Security Specialist, practical exam preparation. Part of Thomas Zachmann's IT Drills series.

Book page: https://itdrills.com/books/cks · German edition: https://it-trainingslager.de/buecher/cks

## Contents

- `notes-api/` – a small Go API (Go 1.27) that you build into an image yourself in the book,
  then minimize, scan, sign and run hardened.

All keys and passwords in the book (e.g. `lab-key-123`) are lab values – never use them in
production.

Tested with kubeadm v1.37.1/v1.37.2, containerd v2.4.2, Cilium 1.20.5 and podman 4.9.3
on Ubuntu 24.04.

## Quick start

```bash
git clone https://github.com/thomaszachmann/cks-zum-anfassen
cp -r cks-zum-anfassen/notes-api ~/cks/notes-api
```

## Disclaimer

This project is not affiliated with the Linux Foundation or the CNCF. CKS is a trademark
of the Linux Foundation.
