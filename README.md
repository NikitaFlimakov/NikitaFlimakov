# Nikita Flimakov

Tech Lead, .NET and Azure. I run the 5-developer core team behind a print e-commerce platform
(order routing to 50+ print providers, multi-carrier shipping, ~15 services on AKS) and an
LLM-based accounts-payable product on Azure OpenAI.

Public code here is extracted from that work and rewritten as standalone libraries:

- [secure-webhooks-dotnet](https://github.com/NikitaFlimakov/secure-webhooks-dotnet) — Standard Webhooks
  signing, DNS-rebinding-safe SSRF guard, AES-GCM secret protection, resilient delivery. .NET 8/10, AOT-clean.
- [invoice-extraction-evals](https://github.com/NikitaFlimakov/invoice-extraction-evals) — eval harness for
  LLM invoice extraction: golden set, field metrics, calibrated LLM judge, bootstrap CIs, CI regression gate.
- [opensoft/dartwing-gateway](https://github.com/opensoft/dartwing-gateway) — API gateway I built at work (public).

Contact: flimakov@gmail.com
