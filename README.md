Problem: 

Secret Network suffers from a bad bridge UX which creates a situation where it is not possible to use one bridge for all actions:

- Dashboard only allows IBC 
- Tunnel only Axelar assets
- Shade does not support ETH L2s 


About: 
SCRT bridge SDK should be an open-source unified source code base providing a complete solution for implementing all active bridge solutions for Secret <-> X chain 

Each Secret Network dapp should be able to use this base to achieve a better UX for its users 


Main goals: 

- Support IBC 
- Support .axl
- Support for Ethereum L1 and L2s via Axelar 
- Support automatic swap from native to .axl 
- Arrival Gas on selected assets using Shade Swap ( ATOM, OSMO, ETH, .... ) 

Secondary goals:
- Option to anonymize the arrival address reasearch ( assets will be sent to the SCRT contract which will then send them to the user )
- Crosschain Swap - Squid roter integration
- Native Cosmos USDT ( Kava ) and USDC ( Noble ) swap to .axl via Squid Roter 
