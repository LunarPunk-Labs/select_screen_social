
# Select Screen Social

WIP dApp to dynamically generate banners based on social NFT claims.  

```mermaid 
sequenceDiagram
 
Profile ->> Publication: Create event banner 
Publication ->> Profile: List progenetor profile
Publication ->> NFT Module: List chairs available
Profile ->> NFT Module: Claim chair
NFT Module ->> Profile: Issue chair NFT
NFT Module ->> Publication: Add claiming profile to banner (DD)

```



## [Template generated from Nuxt 3 Awesome Starter ](https://github.com/viandwi24/nuxt3-awesome-starter/
a 
## License
This project is licensed under the MIT license, Copyright (c) 2022 Alfian Dwi Nugraha. For more information see the [LICENSE](LICENSE.md) file.
