# solana-RPC-forwarder

Need: Python 3.10 or above.

Please set the http://localhost:8080 as the solana RPC url.

All the RPC requests will be forwarded to "https://api.mainnet-beta.solana.com" by this forwarder.

Why we need this forwarder:
1. This will fix the problem of solana RPC server rejection to user's browser (cross header error)
2. The forwarder can re-try when solana RPC server limits the rate of request from clients.

