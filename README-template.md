# elparadisogonzalo  

Welcome to **elparadisogonzalo**, a decentralized project hosted on **Unstoppable Domains** and powered by **IPFS**. This project aims to provide a seamless, censorship-resistant experience using blockchain-based domain technology.  

## 🚀 Features  

- **Decentralized Hosting** – Content is stored on **IPFS**, ensuring security and immutability.  
- **Blockchain Domain** – Hosted on **Unstoppable Domains**, making it resistant to takedowns.  
- **Custom Email Configuration** – Supports decentralized email via **Unstoppable Domains**.  
- **Seamless API Integration** – Uses **Infura** for interacting with the IPFS network.  

## 🔧 Setup & Deployment  

### Prerequisites  
Ensure you have the following installed:  
- [Node.js](https://nodejs.org/) & npm  
- [IPFS CLI](https://docs.ipfs.tech/install/)  
- [Infura Account](https://infura.io/)  
- Linux shell (for deployment & management)  

### Clone the Repository  
```bash
git clone https://github.com/koagonzalo11/elparadisogonzalo.git
cd elparadisogonzalo
```

### Upload Content to IPFS  
Use IPFS to add your content:  
```bash
ipfs add -r ./public
```
Copy the generated **CID** and update your Unstoppable Domains configuration.  

### Configure Unstoppable Domains  
1. Log in to [Unstoppable Domains](https://unstoppabledomains.com/).  
2. Navigate to **Manage Domain** → **Website**.  
3. Add your IPFS CID under the website hosting settings.  

### API Documentation  
The API documentation is available on **GitHub** and **Infura**. See [API Docs](https://github.com/elparadisogonzalo/elparadisogonzalo.github.io/wiki) for more details.  

## 🛠 Troubleshooting  
- **Syncing issues?** Run `ipfs daemon` before adding new content.  
- **Domain not resolving?** Wait for blockchain propagation or check your domain settings.  

## 🤝 Contributing  
Feel free to open issues and pull requests to improve the project!  

## 📜 License  
This project is licensed under the **MIT License**.  

# locales