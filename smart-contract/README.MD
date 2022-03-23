     SCRIPTS
     Use them with yarn
     ex: yarn rename-contract CONTRACTNAME
     
     Deploying with Truffle:
     yarn add truffle
     truffle dashboard
     yarn deploy --network truffle
     yarn verify --network truffle
     
     
    "accounts": "hardhat accounts",
    "rename-contract": "hardhat rename-contract",
    "compile": "hardhat compile --force",
    "test": "hardhat test",
    "test-extended": "EXTENDED_TESTS=1 hardhat test",
    "test-gas": "REPORT_GAS=1 hardhat test",
    "local-node": "hardhat node",
    "root-hash": "hardhat generate-root-hash",
    "proof": "hardhat generate-proof",
    "deploy": "hardhat run scripts/1_deploy.ts",
    "verify": "hardhat verify --constructor-args config/ContractArguments.ts",
    "whitelist-open": "hardhat run scripts/2_whitelist_open.ts",
    "whitelist-close": "hardhat run scripts/3_whitelist_close.ts",
    "presale-open": "hardhat run scripts/4_presale_open.ts",
    "presale-close": "hardhat run scripts/5_presale_close.ts",
    "public-sale-open": "hardhat run scripts/6_public_sale_open.ts",
    "public-sale-close": "hardhat run scripts/7_public_sale_close.ts",
    "reveal": "hardhat run scripts/8_reveal.ts"
