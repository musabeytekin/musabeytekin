# Musa Beytekin

AI engineer in Türkiye. I build LLM agent systems, the evaluation around them, and the backend they run on.

## Exradius

[Exradius](https://github.com/musabeytekin/exradius) is an open-source, self-hosted platform that runs AI agents on a company's own code. Every task gets its own locked-down Kubernetes pod. The agent works there, asks a person when it needs to, and delivers a branch or a patch. I designed and built all of it. Apache-2.0.

| Part | Built with |
|---|---|
| API and worker | Python, FastAPI, PostgreSQL, RabbitMQ |
| Operator | Go, controller-runtime, custom resources for runs and image builds |
| Egress proxy | Go, standard library only. It adds the model key and repository credentials on the way out, so no pod ever holds them |
| Runner | Claude Agent SDK, with an MCP server to ask a person, submit the result and attach files |
| Admin panel | React, TypeScript |
| Install | Helm chart, Terraform modules for AWS (EKS), GCP (GKE) and Azure (AKS) |

## Other work

- **MSc thesis, İnönü University, 2026.** I ran 10 open-weight LLMs (4B to 20B parameters) on the same hardware with Ollama and compared them on response speed, reliability, linguistic quality and emotion scoring. [Summary on my site](https://musabeytekin.github.io/#thesis).
- **[Smart Home Controller AI](https://github.com/musabeytekin/smart-home-controller-ai).** A multi-agent system in Python and LangChain. A coordinator agent reads a natural-language command and routes each part to a specialist agent.
- **Turkish Airlines, Software Engineer.** Java and Spring Boot microservices for airline reservation systems that process about 1,000 reservation records per second.

## Working with

Python, Java, Go, TypeScript · Claude Agent SDK, MCP, LangChain, Ollama · FastAPI, Spring Boot, RabbitMQ · Kubernetes, Docker, Helm, Terraform · PostgreSQL, Oracle, Couchbase

## Contact

[musabeytekin.github.io](https://musabeytekin.github.io) · [LinkedIn](https://linkedin.com/in/musabeytekin) · [musabeytekin867@gmail.com](mailto:musabeytekin867@gmail.com)
