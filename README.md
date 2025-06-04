# Azure API Management ARM Template (with Pet Store API)

This repository contains an ARM (Azure Resource Manager) template for provisioning an Azure API Management (APIM) service with the **Pet Store API** integrated.

## 🚀 Purpose

This project demonstrates Infrastructure as Code (IaC) for deploying both:
- An APIM service
- A sample API (Swagger Pet Store)

## 📄 Template File

- `azure-apim-template.json`: Defines the APIM service and adds the Pet Store API using Swagger.

## 📥 Parameters

The template uses the following parameters:

- `apiManagementServiceName`: Name of the APIM instance.
- `publisherEmail`: Contact email for the publisher.
- `publisherName`: Display name of the publisher.

You can provide them inline in the portal or in a separate parameters file.

## 🛠️ How to Deploy

1. Go to [Azure Portal](https://portal.azure.com).
2. Search for **Template deployment** and click "Create".
3. Select **Build your own template in the editor**.
4. Paste contents of `azure-apim-template.json`.
5. Save, review, and deploy.

> Deployment time for Developer tier is ~15-20 minutes.

## 📌 Notes

- This template uses the **Developer SKU** (for testing and development).
- The Pet Store API is imported via Swagger.

## 🤝 Contributing

Feel free to fork, enhance, or submit issues for improvements.

---

© 2025 by Félix Suárez
