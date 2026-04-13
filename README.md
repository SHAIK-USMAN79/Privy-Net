# Privy-Net
Blockchain is used to securely store and manage user data through smart contracts, ensuring privacy, transparency, and full user control without relying on a central authority.


Privy-Net/
│
├── Decentralized Social Media/
│   │
│   ├── Evault.json                 # Smart contract ABI (contract interface)
│   │
│   ├── VaultApp/                   # Main Web Application
│   │   ├── static/                 # CSS, JS, UI files
│   │   ├── templates/              # HTML pages (frontend UI)
│   │   └── Python server files     # Backend logic (Flask/Django)
│   │
│   ├── hello-eth/                  # Blockchain Environment
│   │   ├── contracts/              # Solidity smart contracts
│   │   ├── migrations/             # Deployment scripts
│   │   ├── node_modules/           # Dependencies (ignored in Git)
│   │   ├── runBlockchain.bat       # Starts Ethereum local blockchain
│   │   └── package.json            # Node dependencies
│   │
│   └── requirements.txt            # Python dependencies
│
├── SCREENS.docx                    # Full project execution guide 📄
├── .gitignore                      # Ignore unwanted files
└── README.md                       # Project documentation



Traditional social media platforms are centralized, which means:

Data stored in one server ❌
Risk of hacking ❌
Server crash → service down ❌

To solve this, your project introduces:

👉 Decentralized Social Media using Blockchain

⛓️ How Blockchain is Used

Uses:
👉 Ethereum

Key Idea:
Data is stored in multiple nodes
Each record = block
Each block has:
Data
Hash code

✔️ If someone changes data → hash changes → system detects ❌
✔️ So data is secure & immutable

⚙️ Core Components
1️⃣ Smart Contract (Solidity)
Written in Solidity
Stores and retrieves data
Deployed on blockchain

📌 Output:

Contract Address
Transaction Hash
Block Number
2️⃣ Blockchain Setup

From your document:

Run:
hello-eth/node-modules/bin/runBlockchain.bat
Then execute:
migrate

✔️ Deploys contract
✔️ Generates contract address

3️⃣ Backend (Python)
Connects to blockchain using contract address
Sends and retrieves data
Handles:
Upload
View
Search

4️⃣ Frontend (VaultApp)

Provides UI for:

Admin login
Upload documents
View documents
Search documents

📄 5️⃣ Document System (Your Main Feature)

👉 Decentralized Document Management / Social Media

Admin can:
Upload documents
Store data on blockchain
View stored data
User can:
Search documents
View metadata
❌ Cannot download files

🔄 Workflow (From Your Screens)
Start blockchain
Deploy contract
Start Python server
Open browser
Admin login
Upload document
Data stored in blockchain
Get:
Hash
Block number
Users can search & view

🔐 Security Features
✔️ Immutable data
✔️ Hash verification
✔️ Decentralized storage
✔️ No single point of failure

🎯 Key Features
⛓️ Blockchain-based storage
🔐 Secure document upload
🔍 Search functionality
👤 Role-based access (Admin/User)
📊 Transaction tracking
