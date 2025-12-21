# CI/CD → Cloud Run (Google Cloud)

Projekt prezentuje **w pełni automatyczny pipeline CI/CD** na Google Cloud Platform.
Aplikacja jest konteneryzowana w Dockerze i **automatycznie budowana oraz wdrażana do Cloud Run** po każdym pushu do repozytorium GitHub.

---

## 🎯 Cel projektu

Celem projektu było pokazanie:
- praktycznej znajomości **CI/CD**
- pracy z **kontenerami (Docker)**
- automatycznego deployu do **Cloud Run**
- konfiguracji **IAM i kont serwisowych**

Projekt nie wymaga ręcznych wdrożeń – cały proces jest zautomatyzowany.

---

## 🧱 Architektura

```text
GitHub
  ↓
Cloud Build (CI/CD)
  ↓
Artifact Registry
  ↓
Cloud Run (serverless)
