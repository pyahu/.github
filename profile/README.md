<p align="center">
  <a href="https://pyahu.io">
    <img src="https://pyahu.io/logo.svg" alt="Pyahu" width="80" />
  </a>
</p>

<h3 align="center">Pyahu</h3>

<p align="center">
  The dev-to-staging platform for JVM teams.
</p>

<p align="center">
  <a href="https://pyahu.io">Website</a> &middot;
  <a href="https://shell.pyahu.io">Shell Docs</a> &middot;
  <a href="https://stacks.pyahu.io">Stacks Docs</a> &middot;
  <a href="https://cloud.pyahu.io">Cloud</a>
</p>

---

Pyahu handles everything before production for Java, Kotlin, and Spring Boot teams. Local environments, managed infrastructure, CI/CD with code analysis, security scanning, and automated tests in every pipeline. Your production stays on AWS, GCP, or Azure. Pyahu makes sure your code gets there tested, scanned, and ready to ship.

## Open Source Projects

### Pyahu Shell

Containerized dev environment built for JVM engineers. Java 25, Kotlin, Maven, Gradle, PostgreSQL and Kafka client tools, IDE remote dev (IntelliJ, VS Code), all pre-configured in a single Docker image.

- [Documentation](https://shell.pyahu.io)

### Pyahu Stacks

Declarative local infrastructure. Define PostgreSQL (CloudNativePG), Apache Kafka (Strimzi), Infisical (secrets), ingress, and TLS in one YAML file. Provision everything on a local Kind cluster with one command.

- [Documentation](https://stacks.pyahu.io)

## How it works

```
Your code ──→ Local dev ──→ Staging ──→ Artifact ──→ Your production
               (Shell)       (Cloud)    (OCI image +
               (Stacks)                  Helm chart)
```

**Shell** and **Stacks** are open source. **Cloud** is the managed platform on top.

## Contact

hello@pyahu.io
