# 🌐 Azure VPN Client Setup Guide (Windows)

This guide walks you through downloading, configuring, and connecting to Azure VPN using the **Azure VPN Client** on Windows.

---

## ✅ Step 1: Prerequisites

Before you begin, make sure:

- You have an **Azure VPN Gateway** configured for **Point-to-Site (P2S)** connections.
- The gateway supports your chosen **authentication method** (Azure Entra ID, certificate-based, or RADIUS).
- You have access to the **VPN client profile** from the Azure portal.

---

## 🛠️ Step 2: Download Azure VPN Client

### Option 1: Microsoft Store

1. Open the **Microsoft Store**.
2. Search for **"Azure VPN Client"**.
3. Click **Install**.
4. Or use this direct link: [Azure VPN Client on Microsoft Store](https://apps.microsoft.com/detail/9np355qt2sqb?hl=en-us&gl=US)

### Option 2: Direct Download

- Download the installer directly from Microsoft: https://aka.ms/azvpnclientdownload

---

## 📦 Step 3: Get the VPN Client Profile

1. In the **Azure Portal**, navigate to your **VPN Gateway**.
2. Under **Point-to-site configuration**, click **Download VPN client**.
3. Extract the downloaded `.zip` file to access the configuration file (e.g., `azurevpnconfig.xml` or `azurevpnconfig_aad.xml`).

---

## 🧩 Step 4: Import the VPN Profile

1. Launch the **Azure VPN Client**.
2. Click the **+** button to add a new connection.
3. Select **Import** and choose the `.xml` file from the extracted profile.
4. The client will auto-fill the connection details.

---

## 🔐 Step 5: Connect to Azure VPN

1. In the Azure VPN Client, select the imported profile.
2. Click **Connect**.
3. Authenticate using the configured method (e.g., Entra ID, certificate).
4. Once connected, you’ll have secure access to your Azure virtual network.

---

## 📄 PDF Version

You can also download this guide as a PDF: [Azure_VPN_Client_Setup_Guide.pdf](https://us-api.asm.skype.com/v1/objects/0-wus-d3-f033000fe6f13961fc00db534c857646/content/original/Azure_VPN_Client_Setup_Guide.pdf)

---

> 💡 Need help with macOS or Linux setup? Let me know!

