# Stratum V2 Spec


## Overview

Stratum V2 data transfers are 2-3 times more efficient than V1, decreasing data loads for miners and pools. V2 also eliminates the incentive for empty block mining. Authenticated encryption with associated data (AEAD) is used in V2 to prevent eavesdropping and hashrate hijacking, two security vulnerabilities in V1 which were extra harmful due to the fact that they aren’t easily detectable. In addition, Stratum V2 aims to improve Bitcoin’s decentralization by allowing miners in pools to construct their own block templates rather than this being done only by pools and solo miners. You can read about further benefits at stratumprotocol.org.

source: [slush pool documentation](https://help.slushpool.com/en/support/solutions/articles/77000434907-what-are-the-benefits-of-stratum-v2-over-v1-)

## Endpoints

Slush Pool Servers Location

- General
  stratum2+tcp://v2.stratum.slushpool.com/u95GEReVMjK6k5YqiSFNqqTnKU4ypU2Wm8awa6tmbmDmk1bWt

- Europe
  stratum2+tcp://v2.eu.stratum.slushpool.com/u95GEReVMjK6k5YqiSFNqqTnKU4ypU2Wm8awa6tmbmDmk1bWt

- USA East Coast
  stratum2+tcp://v2.us-east.stratum.slushpool.com/u95GEReVMjK6k5YqiSFNqqTnKU4ypU2Wm8awa6tmbmDmk1bWt

- Russia Moscow
  stratum2+tcp://v2.ru-west.stratum.slushpool.com/u95GEReVMjK6k5YqiSFNqqTnKU4ypU2Wm8awa6tmbmDmk1bWt
