# ProjectMiniApi — Azure Load Testing demo

A minimal ASP.NET Core Web API with a JMeter test plan, used to demonstrate Azure Load Testing from a GitHub Actions pipeline.

## What's inside

- `Program.cs`, `ProjectMiniApi.csproj` — the minimal API
- `load-test.jmx` — JMeter test plan
- `.github/workflows/` — build and load-test workflow

## How to use

`dotnet run` locally; the workflow runs the load test in Azure Load Testing.

---

**Author:** [Raushan Ranjan (Raushan Sir)](https://raushan-ranjan.azurewebsites.net) · Microsoft Certified Trainer (MCT) · Creator of [RR Skillverse](https://rrskillverse.in)
