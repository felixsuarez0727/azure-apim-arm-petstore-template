# Azure API Management ARM Templates

This repository contains two ARM templates to provision Azure API Management services using Infrastructure as Code.

## 📁 Templates Included

### 1. Basic API Management Template
**File:** `basic-apim-template.json`

This template provisions an API Management (APIM) service in the Developer tier.  
It includes basic service settings such as publisher email and name.

Use this template as a starting point to get familiar with ARM deployments.

---

### 2. Advanced API Management Template with Pet Store API
**File:** `advanced-apim-petstore-template.json`

This extended template includes:
- API Management service provisioning.
- Automatic import of the **Pet Store API** using a Swagger definition.

It demonstrates full Infrastructure as Code: deploying both the service and a working API in a single operation.

---

## ▶️ Video Walkthrough

Step-by-step videos demonstrating the deployment process are available in this playlist:  
📺 **[Azure APIM ARM Template - Step by Step](https://www.youtube.com/playlist?list=PLVumWBDLm-zLRf0cl8VIrpdKKHnrXPZee)**


---

## 🔗 Usage Instructions

1. Open Azure Portal → "Deploy a custom template"
2. Paste the contents of one of the JSON templates
3. Configure parameters (Service name, Publisher info)
4. Review and deploy

---

## 📌 Notes

- Templates are based on API version `2021-08-01`
- Use `Developer` SKU for test environments
- Estimated deployment time: ~15-20 minutes

---

## 📚 Resources

- [Microsoft Docs - ARM Templates](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)
- [Pet Store Swagger API](https://petstore.swagger.io/)

---

## 🛠 Author

Maintained by [@felixsuarez0727](https://github.com/felixsuarez0727)

