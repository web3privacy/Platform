# Scoring model testing repo

_Here we test the recent extended scoring approach for non-techies, whenever service is private or not._

_We consider the information collected during user registration and experience, whether it contains personal or sensitive data. Usually a user's personal information is hidden when the user is identified as wallet address, or collected if phone/email/bank account required._ 

[Applied scoring approach](https://mirror.xyz/0x0f1F3DAf416B74DB3DE55Eb4D7513a80F4841073/E9QPx9iKgPXPqEsAN-YklipSRJy9VTBMOLwwEcqqVpU)

**Simplified overview**
| Project | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------ | ------------- | ------------- |
| **Test project** | available & active GitHub / not (25%) | Live or 🚧 (exclusion criteria) | personal information hidden or 🚧 (exclusion criteria) | public team / not (25%) | available & not marketing docs / not (25%) | available & up to date third-party audit / not (25%) | total |
| -> | 25% | 🚧 | 🚧 | 25% | 25% | 25% | from 0% to 100% |

**Note**:
- persona: non-techie
- max score: 100% (public GitHub, third-party audit, public Docs, public team)  
- min score: 0%
- 🚩 - represents project sunset, empty or inactive Github, marketing docs
- 🚧 - represents that the project is not live on mainnet or demands user's personal information, which are exclusion criteria that force project score to be 0%

## DeFi
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/DEFI.png?raw=true)

**Total**: 38 projects

| Project  | Description | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| [Firn Protocol](https://app.firn.cash) | Firn is the first-ever zero-knowledge privacy platform in the _account-based_ model, and introduces pluggable, flexible privacy to Ethereum-based chains. ✨️**ZK** | ([GitHub](https://github.com/firnprotocol)) | live | hidden | anon | [Docs](https://docs.firn.cash) | [BlockSec](https://github.com/blocksecteam/audit-reports/blob/main/solidity/blocksec_firnprotocol_v1.0-signed.pdf) | 75% |
| [Shade](https://shadeprotocol.io)  | Shade Protocol is an array of connected privacy-preserving DeFi applications built on Secret Network  | ([GitHub](https://github.com/securesecrets/shade)) | live | hidden | anon | [Docs](https://docs.shadeprotocol.io/shade-protocol/) | 🚩 2022: [2 audits](https://docs.shadeprotocol.io/shade-protocol/research/audit-log) | 75% |
| [Silent protocol](https://www.silentprotocol.org)  | Silent Protocol is the first protocol enabling compliant full-stack privacy for smart contract assets and web3 applications at scale.  | - | 🚧 | 🚧 real name required | anon | - | - | 0% |
| 🚩 **sunset** [XATA](https://www.xata.fi) | A MEV Minimization solution to survive the Dark Forest  | - | 🚩 | hidden | anon | ([Docs](https://docs.xata.fi)) | - | 25% |
| [Sienna Network](https://sienna.network) | Sienna is a privacy-first and cross-chain decentralized finance platform where you can privately swap, lend and convert your tokens into their private equivalent  | 🚩`LOW` ([GitHub](https://github.com/SiennaNetwork)) | 🚧 | hidden | anon | [Docs](https://docs.sienna.network/main/) | 🚩 2022: [9 audits](https://sienna.network/audits/) | 75% |
| [Elusiv](https://elusiv.io) | Create blockchain privacy solutions that are built for everyday transactions — with the power of scalable ZK infrastructure on Solana ✨️**ZK** | ([GitHub](https://github.com/elusiv-privacy)) | live | hidden | ([Public](https://www.linkedin.com/search/results/people/?currentCompany=%5B%2280778213%22%5D&origin=COMPANY_PAGE_CANNED_SEARCH&sid=s_%40)) | 🚩 **marketing** [Docs](https://docs.elusiv.io/) | - | 75% |
| [Offshift](https://www.offshift.io) | Offshift’s proprietary Shifting mechanism allows users to Shift between our native token, XFT, and a full palette of private synthetics | 🚩 **LOW** ([GitLab](https://open.offshift.io/offshiftXFT)) | live | hidden | ([anon](https://offshift.io/#team)) | - | - | 25% |
| [CAPE](https://www.espressosys.com/product) | Configurable Asset Privacy for Ethereum | ([GitHub](https://github.com/EspressoSystems/cape)) | 🚧 | 🚧 real name required | anon | [Docs](https://docs.espressosys.com/sequencer/espresso-sequencer-architecture/readme) | - | 50% |
| [Evanesco](https://evanesco.org) | A financial protocol platform that combines Layer0 network infrastructure with a private computing framework. | ([GitHub](https://github.com/Evanesco-Labs)) | live | hidden | anon | - | - | 25% |
| [Dusk Network](https://dusk.network) | Is technology for securities. An open source and secure blockchain (DLT) infrastructure that businesses use to tokenize financial instruments and automate costly processes. | ([GitHub](https://github.com/dusk-network)) | 🚧 | hidden | ([Public](https://dusk.network/pages/team)) | - | - | 50% |
| [Manta Pay](https://app.manta.network/dolphin/transact) | MantaPay is coming to Calamari as the first privacy payment solution in the Kusama ecosystem.✨️**ZK**  | ([GitHub](https://github.com/Manta-Network)) | testnet v3 | hidden | public | [Docs](https://docs.manta.network/docs/Introduction) | - | 75% |
| [Webb](https://app.webb.tools/#/tornado) | an interoperable private bridge ✨️**ZK** | ([GitHub](https://github.com/webb-tools)) | 🚧 | 🚧 unknown | anon | [Docs](https://docs.webb.tools/docs/) | [Audit of the DKG-Substrate pallet](https://blog.webb.tools/webbs-evm-bridge-security-audit-completed-by-veridise/) | 75% |
| [Panther Protocol](https://www.pantherprotocol.io) | is a decentralized privacy metaprotocol enabling confidential, trusted transactions and interoperability with DeFi ✨️**ZK** | ([GitHub](https://github.com/pantherprotocol))  | live | hidden | ([Public](https://www.pantherprotocol.io/)) | [Docs](https://docs.pantherprotocol.io/docs/start-here/panther-protocol-documentation) | 🚩 2021: [ZKP Vesting](https://www.pantherprotocol.io/resources/REP-Panther-ZKP-Vesting.pdf), [ZKP Token](https://www.pantherprotocol.io/resources/REP-Panther-ZKP-Token.pdf) | 100% |
| 🚩 **sunset** [zk.money](https://zk.money) | The private DeFi yield aggregator for Ethereum.✨️**ZK** | ([Docs](https://docs.aztec.network/zk-money/userguide)) | 🚩 | hidden | anon | [Docs](https://docs.aztec.network) | - |  25% |
| [RAILGUN](https://railgun.org) | Private transfers and DeFi infra for Ethereum, Polygon, Binance Smart Chain and Arbitrum.✨️**ZK** | [Github](https://github.com/Railgun-Community) | live | hidden | ([Public](https://railgun.org/#/contributors)) | [Docs](https://docs.railgun.org/developer-guide/cookbook/cookbook-overview) | [5 audits](https://assets.railgun.org/docs/audits/) | 100% |  
| [Umbra](https://app.umbra.cash) |  As a protocol, Umbra defines a simple set of standards, coupled with a singleton smart contract instance, to enable stealth addresses on Ethereum | ([GitHub](https://github.com/ScopeLift/umbra-protocol)) | live | hidden | anon | - | 🚩 2021: [3 audits](https://app.umbra.cash/faq#security) | 50% |
| [Light Shield](https://shield.lightprotocol.com) |  private transactions for Solana. | - | live | hidden | anon | [Docs](https://docs.lightprotocol.com) | 🚩 2022: [Code review](https://github.com/Lightprotocol/light-protocol-v1/blob/main/Audit/Light%20Protocol%20Audit%20Report.pdf) | 50% |
| [Horizon](https://messier.gitbook.io/catalogue-de-messier/messier-applications/horizon) | Decentralized Anonymous Payment Systems ✨️**ZK** | - | 🚧 | hidden as demo | anon | 🚩 **marketing** [Docs](https://messier.gitbook.io/catalogue-de-messier/messier-applications/horizon) | [Messier](https://skynet.certik.com/projects/messier) | 50% |
| [Diva](https://www.diva.exchange/en/) | Free banking technology for everyone: everyone can join in, everyone can use DIVA.EXCHANGE | ([GitHub](https://github.com/diva-exchange)) | 🚧 | 🚧 unknown | ([Public](https://www.diva.exchange/en/team-and-contact/)) | [Docs](https://docs.lightprotocol.com) | - | 75% |
| 🚩 **sunset** [Yellow Submarine](https://ys.finance) | the first and only multichain dApp to offer plug-and-play private DeFi (PriFi) across all EVM-compatible chains | ([Docs](https://yellow-s.gitbook.io/docs/ys-basics/introduction)) | 🚩 | 🚩 | anon | - | - | 25% |
| [BasicSwap](https://basicswapdex.com) | Private Cross-Chain DEX | ([GitHub](https://github.com/tecnovert/basicswap/blob/master/doc/install.md)) | live | hidden | ([anon](https://particl.io/)) | - | - | 50% |
| [Common](https://common.fi) | Common will be a decentralized exchange that mitigates the Maximal Extractable Value (MEV) problem. | - | 🚧 | 🚧 unknown | anon | - | - | 0% |
| 🚩 **sunset** [Sacred](https://sacred.finance) | multi-chain DeFi Platform offers private Yield Bearing Deposits to DeFi users ✨️**ZK* | 🚩 **LOW** ([GitHub](https://github.com/Sacred-Finance)) | 🚩 | 🚩 | anon | - | - | 25% |
| 🚩 **sunset** [Sahara](https://sahara.network) | The first dedicated privacy protocol ecosystem that enables on-platform trade between volatile and stable assets | - | 🚩 | 🚩 | ([Public](https://sahara.network/)) | - | 🚩 2022: [Vesting contract](https://sahara.network/resources/sahara-security-audit.pdf) | 50% |
| 🚩 **sunset** [DeFiner](https://definer.org) | Permission-less and configurable decentralized lending protocol with privacy 100% protected ✨️**ZK** | ([GitHub](https://github.com/DeFinerOrg)) | 🚩 | hidden | anon | [Docs](https://docs.definer.org) | 🚩 2020: [Savings audits](https://docs.definer.org/v/copy-of-definer.org/security/audits) | 75% |
| [Hurricane Protocol](https://hurricane.money) | A fully decentralized protocol offering private transactions on both the Terra & NEAR | 🚩 **no code** ([GitHub](https://github.com/Hurricane-Protocol)) | 🚧 | 🚧 unknown | anon | 🚩 **marketing** [Docs](https://docs.hurricane.money) | - | 50% |
| 🚩 **sunset** [StealthPay](https://www.stealthpay.cash) | a stealth address protocol for Ethereum.| 🚩 **dead** ([GitHub](https://github.com/cryptoadong)) | 🚩 | 🚩 | anon | - | - | 25% |
| [BlackBox](https://blackbox.cash) | collection of tools allowing you send & receive SCRT anonymously | ([GitHub](https://github.com/TriviumNode)) | 🚧 | hidden | anon | - | - | 25% |
| [Hinkal](https://hinkal.pro) | an easy-to-integrate privacy SDK that helps users anonymize transactions.  | - | live | hidden | ([Public](https://hinkal.pro/#section-team)) | - | [Competitive security](https://github.com/Secure3Audit/Secure3Academy/blob/main/audit_reports/Hinkal/Hinkal_final_Secure3_Audit_Report.pdf) | 50% |
| [Conceal Network](https://conceal.network) | privacy-protected DeFi & encrypted comms | ([GitHub](https://github.com/ConcealNetwork)) | live | 🚧 email required | ([anon](https://conceal.network/team/)) | [Docs](https://conceal.network/wiki/doku.php) | - | 50% |
| [CIA protocol](https://ciaprotocol.com) | Building the truest form of DeFi with privacy by default. | - | 🚧 | hidden | anon | - | - | 0% |
| 🚩 **sunset** [CoinBook](https://www.coinbook.app) | Decentralized Multi Chain P2P Order Book | - | 🚩 | 🚩 | anon | - | - | 0% |
| [Seven Seas](https://www.sevenseas.exchange) | No KYC, privacy Focused crypto Exchange | - | 🚧 | 🚧 email required | - | - | - | 0% |
| [NonKYC](https://nonkyc.io) | NonKYC Exchange | - | 🚧 | 🚧 email required | - | - | - |  0% |
| [zkUSD](https://zkusd.money/#Features) | Privacy-Preserving Collateralized Lending & more | 🚩 **no code** ([GitHub](https://github.com/zkUSDLabs)) | 🚩 | hidden | - | 🚩 **marketing** [Docs](https://zkusd.gitbook.io/zkusd-documentation) | - | 50% |
| [Spiral Finance](https://www.spiralfi.io) | non-custodial privacy solution based on ZK-Sync ERA ✨️**ZK** | - | 🚧 | hidden | - | ([Docs](https://docs.spiralfi.io/introduction/spiral-finance)) | - | 25% |
| [Fairy](https://fairyswap.finance/swap) | comprehensive DeFi platform for token swaps, lending, NFT trading, collateralization | 🚩 **dead** ([GitHub](https://github.com/Fairyswap)) | 🚩 | hidden | - | [Docs](https://fairy-swap.gitbook.io/fairyswap-v2/getting-started/about-fairyswap-v2) | 🚩 2022: [Certik](https://skynet.certik.com/projects/fairyswap) | 75% |
| [Shade Cash](https://shade.cash) | A decentralized protocol for private transactions on Fantom Opera | 🚩 **no code** ([GitHub](https://github.com/ShadeCash)) | 🚩 | 🚩 | - | 🚩 **marketing** [Docs](https://shadecash.gitbook.io/shadecash) | - | 50% |

# Post-assesment breakdown

## 100% scoring

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Panther Protocol](https://www.pantherprotocol.io) | ([GitHub](https://github.com/pantherprotocol))  | live | hidden |  ([Public](https://www.pantherprotocol.io/)) | [Docs](https://docs.pantherprotocol.io/docs/start-here/panther-protocol-documentation) | 🚩 2021: [ZKP Vesting](https://www.pantherprotocol.io/resources/REP-Panther-ZKP-Vesting.pdf), [ZKP Token](https://www.pantherprotocol.io/resources/REP-Panther-ZKP-Token.pdf) | 100% |
| [RAILGUN](https://railgun.org) | [Github](https://github.com/Railgun-Community) | live | hidden | ([Public](https://railgun.org/#/contributors)) | [Docs](https://docs.railgun.org/developer-guide/cookbook/cookbook-overview) | [5 audits](https://assets.railgun.org/docs/audits/) | 100% |  

**total**: 2 projects

**Details**:
- 1 red flag 🚩

## 75% scoring

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Firn Protocol](https://app.firn.cash) | ([GitHub](https://github.com/firnprotocol)) | live | hidden | anon | [Docs](https://docs.firn.cash) | [BlockSec](https://github.com/blocksecteam/audit-reports/blob/main/solidity/blocksec_firnprotocol_v1.0-signed.pdf) | 75% |
| [Shade](https://shadeprotocol.io)  | ([GitHub](https://github.com/securesecrets/shade)) | live | hidden | anon | [Docs](https://docs.shadeprotocol.io/shade-protocol/) | 🚩 2022: [2 audits](https://docs.shadeprotocol.io/shade-protocol/research/audit-log) | 75% |
| [Sienna Network](https://sienna.network) | 🚩`LOW` ([GitHub](https://github.com/SiennaNetwork)) | 🚧 | hidden | anon | [Docs](https://docs.sienna.network/main/) | 🚩 2022: [9 audits](https://sienna.network/audits/) | 75% |
| [Elusiv](https://elusiv.io) | ([GitHub](https://github.com/elusiv-privacy)) | live | hidden | ([Public](https://www.linkedin.com/search/results/people/?currentCompany=%5B%2280778213%22%5D&origin=COMPANY_PAGE_CANNED_SEARCH&sid=s_%40)) | 🚩 **marketing** [Docs](https://docs.elusiv.io/) | - | 75% |
| [Manta Pay](https://app.manta.network/dolphin/transact) | ([GitHub](https://github.com/Manta-Network)) | testnet v3 | hidden | public | [Docs](https://docs.manta.network/docs/Introduction) | - | 75% |
| [Webb](https://app.webb.tools/#/tornado) | ([GitHub](https://github.com/webb-tools)) | 🚧 | 🚧 unknown | anon | [Docs](https://docs.webb.tools/docs/) | [Audit of the DKG-Substrate pallet](https://blog.webb.tools/webbs-evm-bridge-security-audit-completed-by-veridise/) | 75% |
| [Diva](https://www.diva.exchange/en/) | ([GitHub](https://github.com/diva-exchange)) | 🚧 | 🚧 unknown | ([Public](https://www.diva.exchange/en/team-and-contact/)) | [Docs](https://docs.lightprotocol.com) | - | 75% |
| 🚩 **sunset** [DeFiner](https://definer.org) | ([GitHub](https://github.com/DeFinerOrg)) | 🚩 | hidden | anon | [Docs](https://docs.definer.org) | 🚩 2020: [Savings audits](https://docs.definer.org/v/copy-of-definer.org/security/audits) | 75% |
| [Fairy](https://fairyswap.finance/swap) | 🚩 **dead** ([GitHub](https://github.com/Fairyswap)) | 🚩 | hidden | - | [Docs](https://fairy-swap.gitbook.io/fairyswap-v2/getting-started/about-fairyswap-v2) | 🚩 2022: [Certik](https://skynet.certik.com/projects/fairyswap) | 75% |

**total**: 9 projects

**Details**:
- 7 red flags 🚩
- 1 sunset

## 50% scoring 

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [CAPE](https://www.espressosys.com/product) | ([GitHub](https://github.com/EspressoSystems/cape)) | testnet | 🚧 real name required | anon | [Docs](https://docs.espressosys.com/sequencer/espresso-sequencer-architecture/readme) | - | 50% |
| [Dusk Network](https://dusk.network) | ([GitHub](https://github.com/dusk-network)) | 🚧 | hidden | ([Public](https://dusk.network/pages/team)) | - | - | 50% |
| [Umbra](https://app.umbra.cash) | ([GitHub](https://github.com/ScopeLift/umbra-protocol)) | live | hidden | anon | - | 🚩 2021: [3 audits](https://app.umbra.cash/faq#security) | 50% |
| [Light Shield](https://shield.lightprotocol.com) |  - | live | hidden | anon | [Docs](https://docs.lightprotocol.com) | 🚩 2022: [Code review](https://github.com/Lightprotocol/light-protocol-v1/blob/main/Audit/Light%20Protocol%20Audit%20Report.pdf) | 50% |
| [Horizon](https://messier.gitbook.io/catalogue-de-messier/messier-applications/horizon) | - | 🚧 | hidden as demo | anon | 🚩 **marketing** [Docs](https://messier.gitbook.io/catalogue-de-messier/messier-applications/horizon) | [Messier](https://skynet.certik.com/projects/messier) | 50% |
| [BasicSwap](https://basicswapdex.com) | ([GitHub](https://github.com/tecnovert/basicswap/blob/master/doc/install.md)) | live | hidden | ([anon](https://particl.io/)) | - | - | 50% |
| 🚩 **sunset** [Sahara](https://sahara.network) | - | 🚩 | 🚩 | ([Public](https://sahara.network/)) | - | 🚩 2022: [Vesting contract](https://sahara.network/resources/sahara-security-audit.pdf) | 50% |
| [Hurricane Protocol](https://hurricane.money) | 🚩 **no code** ([GitHub](https://github.com/Hurricane-Protocol)) | 🚧 | 🚧 unknown | anon | 🚩 **marketing** [Docs](https://docs.hurricane.money) | - | 50% |
| [Hinkal](https://hinkal.pro) | - | live | hidden | ([Public](https://hinkal.pro/#section-team)) | - | [Competitive security](https://github.com/Secure3Audit/Secure3Academy/blob/main/audit_reports/Hinkal/Hinkal_final_Secure3_Audit_Report.pdf) | 50% |
| [Conceal Network](https://conceal.network) | ([GitHub](https://github.com/ConcealNetwork)) | live | 🚧 email required | ([anon](https://conceal.network/team/)) | [Docs](https://conceal.network/wiki/doku.php) | - | 50% |
| [zkUSD](https://zkusd.money/#Features) |  🚩 **no code** ([GitHub](https://github.com/zkUSDLabs)) | 🚧 | hidden | - | 🚩 **marketing** [Docs](https://zkusd.gitbook.io/zkusd-documentation) | - | 50% |
| [Shade Cash](https://shade.cash) | 🚩 **no code** ([GitHub](https://github.com/ShadeCash)) | 🚧 | 🚩 | - | 🚩 **marketing** [Docs](https://shadecash.gitbook.io/shadecash) | - | 50% |

**total**: 12 projects

**Details**:
- 10 red flags 🚩
- 1 sunset

## 25% scoring 

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| 🚩 **sunset** [XATA](https://www.xata.fi) | - | 🚩 | hidden | anon | ([Docs](https://docs.xata.fi)) | - | 25% |
| [Offshift](https://www.offshift.io) | 🚩 **LOW** ([GitLab](https://open.offshift.io/offshiftXFT)) | live | hidden | ([anon](https://offshift.io/#team)) | - | - | 25% |
| [Evanesco](https://evanesco.org) | ([GitHub](https://github.com/Evanesco-Labs)) | live | hidden | anon | - | - | 25% |
| 🚩 **sunset** [zk.money](https://zk.money) | ([Docs](https://docs.aztec.network/zk-money/userguide)) | 🚩 | hidden | anon | [Docs](https://docs.aztec.network) | - |  25% |
| 🚩 **sunset** [Yellow Submarine](https://ys.finance) | ([Docs](https://yellow-s.gitbook.io/docs/ys-basics/introduction)) | 🚩 | 🚩 | anon | - | - | 25% |
| 🚩 **sunset** [Sacred](https://sacred.finance) | 🚩 **LOW** ([GitHub](https://github.com/Sacred-Finance)) | 🚩 | 🚩 | anon | - | - | 25% |
| 🚩 **sunset** [StealthPay](https://www.stealthpay.cash) | 🚩 **dead** ([GitHub](https://github.com/cryptoadong)) | 🚩 | 🚩 | anon | - | - | 25% |
| [BlackBox](https://blackbox.cash) | ([GitHub](https://github.com/TriviumNode)) | 🚧 | hidden | anon | - | - | 25% |
| [Spiral Finance](https://www.spiralfi.io) | - | 🚧 | hidden | - | ([Docs](https://docs.spiralfi.io/introduction/spiral-finance)) | - | 25% |

**total**: 9 projects

**Details**:
- 3 red flags 🚩
- 5 sunsets

## 0% scoring 

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Silent protocol](https://www.silentprotocol.org)  | - | 🚧 | 🚧 real name required | anon | - | - | 0% |
| [Common](https://common.fi) | - | 🚧 | 🚧 unknown | anon | - | - | 0% |
| [CIA protocol](https://ciaprotocol.com) | - | 🚧 | hidden | anon | - | - | 0% |
| 🚩 **sunset** [CoinBook](https://www.coinbook.app) | - | 🚩 | 🚩 | anon | - | - | 0% |
| [Seven Seas](https://www.sevenseas.exchange) | - | 🚧 | 🚧 email required | - | - | - | 0% |
| [NonKYC](https://nonkyc.io) | - | 🚧 | 🚧 email required | - | - | - | 0% |

**total**: 6 projects

**Details**:
- 1 sunset

# Red-flag applicable breakdown

**Note**: 
- 🚩 - represents - 25% of scoring
- sunset - decreases scoring to 0%

## 100% scoring

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [RAILGUN](https://railgun.org) | [Github](https://github.com/Railgun-Community) | live | hidden | ([Public](https://railgun.org/#/contributors)) | [Docs](https://docs.railgun.org/developer-guide/cookbook/cookbook-overview) | [5 audits](https://assets.railgun.org/docs/audits/) | 100% |  

**total**: 1 project

## 75% scoring

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Panther Protocol](https://www.pantherprotocol.io) | ([GitHub](https://github.com/pantherprotocol))  | live | hidden |  ([Public](https://www.pantherprotocol.io/)) | [Docs](https://docs.pantherprotocol.io/docs/start-here/panther-protocol-documentation) | 🚩 2021: [ZKP Vesting](https://www.pantherprotocol.io/resources/REP-Panther-ZKP-Vesting.pdf), [ZKP Token](https://www.pantherprotocol.io/resources/REP-Panther-ZKP-Token.pdf) | 75% |
| [Firn Protocol](https://app.firn.cash) | ([GitHub](https://github.com/firnprotocol)) | live | hidden | anon | [Docs](https://docs.firn.cash) | [BlockSec](https://github.com/blocksecteam/audit-reports/blob/main/solidity/blocksec_firnprotocol_v1.0-signed.pdf) | 75% |
| [Manta Pay](https://app.manta.network/dolphin/transact) | ([GitHub](https://github.com/Manta-Network)) | testnet v3 | hidden | public | [Docs](https://docs.manta.network/docs/Introduction) | - | 75% |
| [Webb](https://app.webb.tools/#/tornado) | ([GitHub](https://github.com/webb-tools)) | 🚧 | 🚧 unknown | anon | [Docs](https://docs.webb.tools/docs/) | [Audit of the DKG-Substrate pallet](https://blog.webb.tools/webbs-evm-bridge-security-audit-completed-by-veridise/) | 75% |
| [Diva](https://www.diva.exchange/en/) | ([GitHub](https://github.com/diva-exchange)) | 🚧 | 🚧 unknown | ([Public](https://www.diva.exchange/en/team-and-contact/)) | [Docs](https://docs.lightprotocol.com) | - | 75% |

**total**: 5 projects

**Details**:
- 1 red flag 🚩

## 50% scoring 

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Shade](https://shadeprotocol.io)  | ([GitHub](https://github.com/securesecrets/shade)) | live | hidden | anon | [Docs](https://docs.shadeprotocol.io/shade-protocol/) | 🚩 2022: [2 audits](https://docs.shadeprotocol.io/shade-protocol/research/audit-log) | 50% |
| [Elusiv](https://elusiv.io) | ([GitHub](https://github.com/elusiv-privacy)) | live | hidden | ([Public](https://www.linkedin.com/search/results/people/?currentCompany=%5B%2280778213%22%5D&origin=COMPANY_PAGE_CANNED_SEARCH&sid=s_%40)) | 🚩 **marketing** [Docs](https://docs.elusiv.io/) | - | 50% |
| [CAPE](https://www.espressosys.com/product) | ([GitHub](https://github.com/EspressoSystems/cape)) | 🚧 | 🚧 real name required | anon | [Docs](https://docs.espressosys.com/sequencer/espresso-sequencer-architecture/readme) | - | 50% |
| [Dusk Network](https://dusk.network) | ([GitHub](https://github.com/dusk-network)) | 🚧 | hidden | ([Public](https://dusk.network/pages/team)) | - | - | 50% |
| [BasicSwap](https://basicswapdex.com) | ([GitHub](https://github.com/tecnovert/basicswap/blob/master/doc/install.md)) | live | hidden | ([anon](https://particl.io/)) | - | - | 50% |
| [Hinkal](https://hinkal.pro) | - | live | hidden | ([Public](https://hinkal.pro/#section-team)) | - | [Competitive security](https://github.com/Secure3Audit/Secure3Academy/blob/main/audit_reports/Hinkal/Hinkal_final_Secure3_Audit_Report.pdf) | 50% |
| [Conceal Network](https://conceal.network) | ([GitHub](https://github.com/ConcealNetwork)) | live | 🚧 email required | ([anon](https://conceal.network/team/)) | [Docs](https://conceal.network/wiki/doku.php) | - | 50% |

**total**: 7 projects

**Details**:
- 2 red flags 🚩

## 25% scoring 

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Sienna Network](https://sienna.network) | 🚩`LOW` ([GitHub](https://github.com/SiennaNetwork)) | 🚧 | hidden | anon | [Docs](https://docs.sienna.network/main/) | 🚩 2022: [9 audits](https://sienna.network/audits/) | 25% |
| [Evanesco](https://evanesco.org) | ([GitHub](https://github.com/Evanesco-Labs)) | live | hidden | anon | - | - | 25% |
| [Umbra](https://app.umbra.cash) | ([GitHub](https://github.com/ScopeLift/umbra-protocol)) | live | hidden | anon | - | 🚩 2021: [3 audits](https://app.umbra.cash/faq#security) | 25% |
| [Light Shield](https://shield.lightprotocol.com) |  - | live | hidden | anon | [Docs](https://docs.lightprotocol.com) | 🚩 2022: [Code review](https://github.com/Lightprotocol/light-protocol-v1/blob/main/Audit/Light%20Protocol%20Audit%20Report.pdf) | 25% |
| [Horizon](https://messier.gitbook.io/catalogue-de-messier/messier-applications/horizon) | - | 🚧 | hidden as demo | anon | 🚩 **marketing** [Docs](https://messier.gitbook.io/catalogue-de-messier/messier-applications/horizon) | [Messier](https://skynet.certik.com/projects/messier) | 25% |
| [BlackBox](https://blackbox.cash) | ([GitHub](https://github.com/TriviumNode)) | 🚧 | hidden | anon | - | - | 25% |
| [Spiral Finance](https://www.spiralfi.io) | - | 🚧 | hidden | - | ([Docs](https://docs.spiralfi.io/introduction/spiral-finance)) | - | 25% |
| [Fairy](https://fairyswap.finance/swap) | 🚩 **dead** ([GitHub](https://github.com/Fairyswap)) | 🚩 | hidden | - | [Docs](https://fairy-swap.gitbook.io/fairyswap-v2/getting-started/about-fairyswap-v2) | 🚩 2022: [Certik](https://skynet.certik.com/projects/fairyswap) | 25% |

**total**: 8 projects

**Details**:
- 7 red flags 🚩

## 0% scoring 

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Silent protocol](https://www.silentprotocol.org)  | - | 🚧 | 🚧 real name required | anon | - | - | 0% |
| 🚩 **sunset** [XATA](https://www.xata.fi) | - | 🚩 | hidden | anon | ([Docs](https://docs.xata.fi)) | - | 0%  |
| [Offshift](https://www.offshift.io) | 🚩 **LOW** ([GitLab](https://open.offshift.io/offshiftXFT)) | live | hidden | ([anon](https://offshift.io/#team)) | - | - | 0%  |
| 🚩 **sunset** [zk.money](https://zk.money) | ([Docs](https://docs.aztec.network/zk-money/userguide)) | 🚩 | hidden | anon | [Docs](https://docs.aztec.network) | - |  0% |
| 🚩 **sunset** [Yellow Submarine](https://ys.finance) | ([Docs](https://yellow-s.gitbook.io/docs/ys-basics/introduction)) | 🚩 | 🚩 | anon | - | - | 0% |
| [Common](https://common.fi) | - | 🚧 | 🚧 unknown | anon | - | - | 0% |
| 🚩 **sunset** [Sacred](https://sacred.finance) | 🚩 **LOW** ([GitHub](https://github.com/Sacred-Finance)) | 🚩 | 🚩 | anon | - | - | 0% |
| 🚩 **sunset** [Sahara](https://sahara.network) | - | 🚩 | 🚩 | ([Public](https://sahara.network/)) | - | 🚩 2022: [Vesting contract](https://sahara.network/resources/sahara-security-audit.pdf) | 0% |
| 🚩 **sunset** [DeFiner](https://definer.org) | ([GitHub](https://github.com/DeFinerOrg)) | 🚩 | hidden | anon | [Docs](https://docs.definer.org) | 🚩 2020: [Savings audits](https://docs.definer.org/v/copy-of-definer.org/security/audits) | 0% |
| [Hurricane Protocol](https://hurricane.money) | 🚩 **no code** ([GitHub](https://github.com/Hurricane-Protocol)) | 🚧 | 🚧 unknown | anon | 🚩 **marketing** [Docs](https://docs.hurricane.money) | - | 0% |
| 🚩 **sunset** [StealthPay](https://www.stealthpay.cash) | 🚩 **dead** ([GitHub](https://github.com/cryptoadong)) | 🚩 | 🚩 | anon | - | - | 0% |
| [CIA protocol](https://ciaprotocol.com) | - | 🚧 | hidden | anon | - | - | 0% |
| 🚩 **sunset** [CoinBook](https://www.coinbook.app) | - | 🚩 | 🚩 | anon | - | - | 0% |
| [Seven Seas](https://www.sevenseas.exchange) | - | 🚧 | 🚧 email required | - | - | - | 0% |
| [NonKYC](https://nonkyc.io) | - | 🚧 | 🚧 email required | - | - | - | 0% |
| [zkUSD](https://zkusd.money/#Features) |  🚩 **no code** ([GitHub](https://github.com/zkUSDLabs)) | 🚩 | hidden | - | 🚩 **marketing** [Docs](https://zkusd.gitbook.io/zkusd-documentation) | - | 0% |
| [Shade Cash](https://shade.cash) | 🚩 **no code** ([GitHub](https://github.com/ShadeCash)) | 🚩 | 🚩 | - | 🚩 **marketing** [Docs](https://shadecash.gitbook.io/shadecash) | - | 0% |

**total**: 17 projects

**Details**:
- 11 red flags 🚩
- 8 sunsets

# 🚧-flag applicable breakdown (exclusion criteria)

**Note**: 
- 🚧 - represents that the project is not live on mainnet or demands user's personal information, which is an exclusion criteria that forces project score to be 0%

## 100% scoring

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [RAILGUN](https://railgun.org) | [Github](https://github.com/Railgun-Community) | live | hidden | ([Public](https://railgun.org/#/contributors)) | [Docs](https://docs.railgun.org/developer-guide/cookbook/cookbook-overview) | [5 audits](https://assets.railgun.org/docs/audits/) | 100% |  

**total**: 1 project

## 75% scoring

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Panther Protocol](https://www.pantherprotocol.io) | ([GitHub](https://github.com/pantherprotocol))  | live | hidden |  ([Public](https://www.pantherprotocol.io/)) | [Docs](https://docs.pantherprotocol.io/docs/start-here/panther-protocol-documentation) | 🚩 2021: [ZKP Vesting](https://www.pantherprotocol.io/resources/REP-Panther-ZKP-Vesting.pdf), [ZKP Token](https://www.pantherprotocol.io/resources/REP-Panther-ZKP-Token.pdf) | 75% |
| [Firn Protocol](https://app.firn.cash) | ([GitHub](https://github.com/firnprotocol)) | live | hidden | anon | [Docs](https://docs.firn.cash) | [BlockSec](https://github.com/blocksecteam/audit-reports/blob/main/solidity/blocksec_firnprotocol_v1.0-signed.pdf) | 75% |
| [Manta Pay](https://app.manta.network/dolphin/transact) | ([GitHub](https://github.com/Manta-Network)) | testnet v3 | hidden | public | [Docs](https://docs.manta.network/docs/Introduction) | - | 75% |

**total**: 3 projects

**Details**:
- 1 red flag 🚩

## 50% scoring 

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Shade](https://shadeprotocol.io)  | ([GitHub](https://github.com/securesecrets/shade)) | live | hidden | anon | [Docs](https://docs.shadeprotocol.io/shade-protocol/) | 🚩 2022: [2 audits](https://docs.shadeprotocol.io/shade-protocol/research/audit-log) | 50% |
| [Elusiv](https://elusiv.io) | ([GitHub](https://github.com/elusiv-privacy)) | live | hidden | ([Public](https://www.linkedin.com/search/results/people/?currentCompany=%5B%2280778213%22%5D&origin=COMPANY_PAGE_CANNED_SEARCH&sid=s_%40)) | 🚩 **marketing** [Docs](https://docs.elusiv.io/) | - | 50% |
| [BasicSwap](https://basicswapdex.com) | ([GitHub](https://github.com/tecnovert/basicswap/blob/master/doc/install.md)) | live | hidden | ([anon](https://particl.io/)) | - | - | 50% |
| [Hinkal](https://hinkal.pro) | - | live | hidden | ([Public](https://hinkal.pro/#section-team)) | - | [Competitive security](https://github.com/Secure3Audit/Secure3Academy/blob/main/audit_reports/Hinkal/Hinkal_final_Secure3_Audit_Report.pdf) | 50% |

**total**: 4 projects

**Details**:
- 2 red flags 🚩

## 25% scoring 

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Evanesco](https://evanesco.org) | ([GitHub](https://github.com/Evanesco-Labs)) | live | hidden | anon | - | - | 25% |
| [Umbra](https://app.umbra.cash) | ([GitHub](https://github.com/ScopeLift/umbra-protocol)) | live | hidden | anon | - | 🚩 2021: [3 audits](https://app.umbra.cash/faq#security) | 25% |
| [Light Shield](https://shield.lightprotocol.com) |  - | live | hidden | anon | [Docs](https://docs.lightprotocol.com) | 🚩 2022: [Code review](https://github.com/Lightprotocol/light-protocol-v1/blob/main/Audit/Light%20Protocol%20Audit%20Report.pdf) | 25% | ([Docs](https://docs.spiralfi.io/introduction/spiral-finance)) | - | 25% |
| [Fairy](https://fairyswap.finance/swap) | 🚩 **dead** ([GitHub](https://github.com/Fairyswap)) | 🚩 | hidden | - | [Docs](https://fairy-swap.gitbook.io/fairyswap-v2/getting-started/about-fairyswap-v2) | 🚩 2022: [Certik](https://skynet.certik.com/projects/fairyswap) | 25% |

**total**: 4 projects

**Details**:
- 4 red flags 🚩

## 0% scoring 

| Project  | GitHub | Product-readiness | Personal Information | Team | Docs | Audit | Score |
| ------------- |------------- |------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [Silent protocol](https://www.silentprotocol.org)  | - | 🚧 | 🚧 real name required | anon | - | - | 0% |
| 🚩 **sunset** [XATA](https://www.xata.fi) | - | 🚩 | hidden | anon | ([Docs](https://docs.xata.fi)) | - | 0%  |
| [Sienna Network](https://sienna.network) | 🚩`LOW` ([GitHub](https://github.com/SiennaNetwork)) | 🚧 | hidden | anon | [Docs](https://docs.sienna.network/main/) | 🚩 2022: [9 audits](https://sienna.network/audits/) | 0% |
| [Offshift](https://www.offshift.io) | 🚩 **LOW** ([GitLab](https://open.offshift.io/offshiftXFT)) | live | hidden | ([anon](https://offshift.io/#team)) | - | - | 0%  |
| [CAPE](https://www.espressosys.com/product) | ([GitHub](https://github.com/EspressoSystems/cape)) | 🚧 | 🚧 real name required | anon | [Docs](https://docs.espressosys.com/sequencer/espresso-sequencer-architecture/readme) | - | 0% |
| [Dusk Network](https://dusk.network) | ([GitHub](https://github.com/dusk-network)) | 🚧 | hidden | ([Public](https://dusk.network/pages/team)) | - | - | 0% |
| [Webb](https://app.webb.tools/#/tornado) | ([GitHub](https://github.com/webb-tools)) | 🚧 | 🚧 unknown | anon | [Docs](https://docs.webb.tools/docs/) | [Audit of the DKG-Substrate pallet](https://blog.webb.tools/webbs-evm-bridge-security-audit-completed-by-veridise/) | 0% |
| 🚩 **sunset** [zk.money](https://zk.money) | ([Docs](https://docs.aztec.network/zk-money/userguide)) | 🚩 | hidden | anon | [Docs](https://docs.aztec.network) | - |  0% |
| [Horizon](https://messier.gitbook.io/catalogue-de-messier/messier-applications/horizon) | - | 🚧 | hidden as demo | anon | 🚩 **marketing** [Docs](https://messier.gitbook.io/catalogue-de-messier/messier-applications/horizon) | [Messier](https://skynet.certik.com/projects/messier) | 0% |
| [Diva](https://www.diva.exchange/en/) | ([GitHub](https://github.com/diva-exchange)) | 🚧 | 🚧 unknown | ([Public](https://www.diva.exchange/en/team-and-contact/)) | [Docs](https://docs.lightprotocol.com) | - | 0% |
| 🚩 **sunset** [Yellow Submarine](https://ys.finance) | ([Docs](https://yellow-s.gitbook.io/docs/ys-basics/introduction)) | 🚩 | 🚩 | anon | - | - | 0% |
| [Common](https://common.fi) | - | 🚧 | 🚧 unknown | anon | - | - | 0% |
| 🚩 **sunset** [Sacred](https://sacred.finance) | 🚩 **LOW** ([GitHub](https://github.com/Sacred-Finance)) | 🚩 | 🚩 | anon | - | - | 0% |
| 🚩 **sunset** [Sahara](https://sahara.network) | - | 🚩 | 🚩 | ([Public](https://sahara.network/)) | - | 🚩 2022: [Vesting contract](https://sahara.network/resources/sahara-security-audit.pdf) | 0% |
| 🚩 **sunset** [DeFiner](https://definer.org) | ([GitHub](https://github.com/DeFinerOrg)) | 🚩 | hidden | anon | [Docs](https://docs.definer.org) | 🚩 2020: [Savings audits](https://docs.definer.org/v/copy-of-definer.org/security/audits) | 0% |
| [Hurricane Protocol](https://hurricane.money) | 🚩 **no code** ([GitHub](https://github.com/Hurricane-Protocol)) | 🚧 | 🚧 unknown | anon | 🚩 **marketing** [Docs](https://docs.hurricane.money) | - | 0% |
| 🚩 **sunset** [StealthPay](https://www.stealthpay.cash) | 🚩 **dead** ([GitHub](https://github.com/cryptoadong)) | 🚩 | 🚩 | anon | - | - | 0% |
| [BlackBox](https://blackbox.cash) | ([GitHub](https://github.com/TriviumNode)) | 🚧 | hidden | anon | - | - | 0% |
| [Conceal Network](https://conceal.network) | ([GitHub](https://github.com/ConcealNetwork)) | live | 🚧 email required | ([anon](https://conceal.network/team/)) | [Docs](https://conceal.network/wiki/doku.php) | - | 0% |
| [CIA protocol](https://ciaprotocol.com) | - | 🚧 | hidden | anon | - | - | 0% |
| 🚩 **sunset** [CoinBook](https://www.coinbook.app) | - | 🚩 | 🚩 | anon | - | - | 0% |
| [Seven Seas](https://www.sevenseas.exchange) | - | 🚧 | 🚧 email required | - | - | - | 0% |
| [NonKYC](https://nonkyc.io) | - | 🚧 | 🚧 email required | - | - | - | 0% |
| [zkUSD](https://zkusd.money/#Features) |  🚩 **no code** ([GitHub](https://github.com/zkUSDLabs)) | 🚩 | hidden | - | 🚩 **marketing** [Docs](https://zkusd.gitbook.io/zkusd-documentation) | - | 0% |
| [Spiral Finance](https://www.spiralfi.io) | - | 🚧 | hidden | - | ([Docs](https://docs.spiralfi.io/introduction/spiral-finance)) | - | 0% |
| [Shade Cash](https://shade.cash) | 🚩 **no code** ([GitHub](https://github.com/ShadeCash)) | 🚩 | 🚩 | - | 🚩 **marketing** [Docs](https://shadecash.gitbook.io/shadecash) | - | 0% |

**total**: 26 projects

**Details**:
- 14 🚧
- 14 red flags 🚩
- 8 sunsets

# Findings

## DeFi category

1. 38 projects
2. 21 🚩red flags
3. 14 🚧
4. 8 sunsets

**Before 🚧 criteria has been applied**

_high-risk category_
- 44.7% of the projects scored 0%
- 21.1% scored 25%
- 65.8% of the total projects - high-risk category (0-25%)

_low-risk category_
- 2.6% of the projects hit 100%
- 13.2% hit 75%
- 15.8% combined - low-risk category

_moderate risk-category_
- 21.1% - moderate risk-category

**GitHub**
- 23 projects (60.5%) have public GitHub repos, 1 (2.6%) has a GitLab repo
- 7 projects (30.4% among them) have dead or inactive GitHub (6 months +)

**security audits**
- 13 projects (34.2%) have third-party audits
- 8 projects have outdated audits (1 year+) - 61.5% (among those attested by a third party)

**docs**
- 21 projects (55.3%) have docs 
- 5 projects (23.8% among them) = marketing docs

**After 🚧 criteria has been applied**
- 36.8% - 🚧
- 68.4% - 0%
- 10.5% - 25%
- 10.5% - 50%
- 7.9% - 75%

**Basic assessment, 🚩& 🚧 criterias applicability comparison**

| Observation | Basic | 🚩 | 🚧 | 
| ------------- | ------------- | ------------- | ------------- | 
| 100% | 5.3% | 2.6% | 2.6% | 
| 75% | 23.7% | 13.2% | 7.9% | 
| 50% | 31.6% | 18.4% | 10.5% | 
| 25% | 23.7% | 21.1% | 10.5% | 
| 0% | 15.8% | 44.7% | 68.4% | 
