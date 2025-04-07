# Dokumentation 

<h2>Steg 1 - Förbered repository</h2>
- git fork av https://github.com/Degendeg/cua24s_gamestore<br/>
- git clone av fork-repo till lokal miljö för framtida ändringar<br/>

<h2>Steg 2 - App Service Setup</h2>
- "Web App" väljs som typ<br/>
- Läggs i ny resource group "GameShop"<br/>
- Aktivera inte Continuous Deployment (GitHub Actions) vid setup då Azure DevOps ska användas istället<br/>
- Aktivera Application Insights<br/>
<h4>App Service Specs</h4>
* Publish: Code<br/>
* Runtime stack: .NET 8.0<br/>
* OS: Windows<br/>
* Pricing Plan: Free F1<br/>
