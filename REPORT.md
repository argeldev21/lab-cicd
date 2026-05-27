#  LAB CI/CD – Report Finale

##  Repository GitHub
[https://github.com/argeldev21/lab-cicd]

## 🌐 Sito Live (GitHub Pages)
[https://argeldev21.github.io/lab-cicd/]

##  Pipeline CI/CD
La pipeline è composta da tre job:

1. **Quality Check (CI)**  
   - Linting HTML con `htmlhint`  
   - Controllo link rotti con `lychee`

2. **Container Registry (GHCR)**  
   - Build immagine Docker  
   - Push su GitHub Container Registry

3. **Deployment (GitHub Pages)**  
   - Deploy automatico dei file statici  
   - Pubblicazione del sito live

##  Stato attuale
- Pipeline funzionante  
- Deploy attivo su GitHub Pages  
- Sito online e aggiornato automaticamente ad ogni push su `main`


# Screenshot FASE 6 (workflow & Errore intenzionale)
[images/Screenshot workflow.png, images/Screenshot errore-intenzionale.png]


# Screenshot FASE 6 (Sezione Packages)
[images/Screenshot packages.png]