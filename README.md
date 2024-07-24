# Swisstronik Tesnet Techinal Task 4 (Mint a PERC20 Token)

## Steps

### 1. Clone Repository

```bash
git clone https://github.com/tianpratama1109/perc20-mint-token-swisstronik.git
```

```
cd swisstronik-perc20-mint-token
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
PRIVATE_KEY="your private key"
```

### 4. Update the Smart Contract (Optional)

If you want to modify the token name or symbol:

- Open the contracts folder.
- Edit the PERC20Sample.sol file.

### 5. Compile Smart Contract

```bash
npm run compile
```

### 6. Deploy the Smart Contract

```bash
npm run deploy
```

### 7. Mint Token

```bash
npm run mint
```

### 8. Transfer Token

```bash
npm run transfer
```

### 8. Finsihed

- Open the deployed-address.ts file (located in the utils folder), copy the address, and paste it into the testnet dashboard.
- Open the tx-hash.txt file (located in the utils folder), copy the transaction hash, and paste it into the testnet dashboard.
- Push the project to your GitHub and paste the repository link into the testnet dashboard.

