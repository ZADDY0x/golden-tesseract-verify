# ZAA Verified: verified on the ZAA Network

Static verification page for **the ZAA Network** (batch provenance and verification, powered by **ZAA**) on **Polygon Amoy testnet**. Internal engine: Golden Tesseract v0.01 Alpha.

- Verify a batch: `https://zaddy0x.github.io/golden-tesseract-verify/?batch=ZAA-0001` (or `?token=1`)
- No wallet needed: reads the chain via the public RPC `https://polygon-amoy-bor-rpc.publicnode.com`
- ZAA Network batch registry (verified source): [0x461ACAcbC6B13ee885Da180F4113944dF76EC7DF](https://amoy.polygonscan.com/address/0x461ACAcbC6B13ee885Da180F4113944dF76EC7DF#code)
- Legacy ZA MED+ pilot registry (retired, still readable for `ZAM-` batch IDs): [0xAE3aF03bF54D11D5afc2304f1aEF7f2Ca0294800](https://amoy.polygonscan.com/address/0xAE3aF03bF54D11D5afc2304f1aEF7f2Ca0294800#code)

This repo contains only the built static files (React + viem). It holds no keys or secrets. Testnet alpha: not for production use.
