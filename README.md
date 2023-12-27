<div align="center">
  <img src="https://i.imgur.com/Vaah2gJ.png"  />
  <h1>Scroll Soft</h1>
  <p>This software simplifies wallet management on the Scroll network, providing access to a variety of features and a high level of randomization for enhanced security.</p>
</div>
---
<h2>🚀 Installation</h2>

```
git clone https://github.com/czbag/scroll.git

cd scroll

pip install -r requirements.txt

# Before you start, configure the required modules in modules_settings.py

python main.py
```
---
<h2>🚨 Modules</h2>

1. Make deposit/withdraw with official bridge

2. Make deposit/withdraw with Orbiter bridge

3. Make deposit/withdraw with LayerSwap bridge

4. Wrap/unwrap ETH

5. Swap on SkyDrome

6. Swap on SyncSwap

7. LayerBank lending protocol (deposit/withdraw)

8. Mint Zerius NFT and bridge this NFT to any chain (layerzero protocol)

9. Crete Omnisea NFT

10. Mint NFT on NFTS2ME

11. Dmail

12. Create Gnosis Safe

13. Deploy any contract

14. Custom routes - actions to be performed sequentially or randomly

15. Check gas before starting the module, if gas > specified, the software will wait for

16. Logging via logger module

---
<h2>⚙️ Settings</h2>

1) All basic settings are made in settings.py and modules_settings.py, inside there is information about what and where to write

2) In the accounts.txt file, specify your private keys

3) In the rpc.json file at the path zksync/data/rpc.json we can change the rpc to ours

Creator telegram channel(forked from this guy) –– https://t.me/sybilwave
