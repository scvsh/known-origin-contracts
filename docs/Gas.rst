Appendix: Gas Usage
===================

.. code-block:: shell

  ·------------------------------------------------------------|---------------------------|-------------|-----------------------------------·
  |            Solc version: 0.4.24+commit.e67f0147            ·  Optimizer enabled: true  ·  Runs: 200  ·  Block limit: 17592186044415 gas  │
  ·····························································|···························|·············|····································
  |  Methods                                                                                                                                 │
  ······························|······························|·············|·············|·············|··················|·················
  |  Contract                   ·  Method                      ·  Min        ·  Max        ·  Avg        ·  # calls         ·  gbp (avg)     │
  ······························|······························|·············|·············|·············|··················|·················
  |  KnownOriginDigitalAssetV2  ·  createActiveEdition         ·     344702  ·     374702  ·     359702  ·             130  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  KnownOriginDigitalAssetV2  ·  mint                        ·     244538  ·     289538  ·     259538  ·             390  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  KnownOriginDigitalAssetV2  ·  setApprovalForAll           ·      46696  ·      46760  ·      46758  ·             195  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  KnownOriginDigitalAssetV2  ·  transferFrom                ·          -  ·          -  ·      95151  ·               1  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  KnownOriginDigitalAssetV2  ·  updateArtistCommission      ·          -  ·          -  ·      28256  ·              11  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  KnownOriginDigitalAssetV2  ·  updateOptionalCommission    ·          -  ·          -  ·      66284  ·              76  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  Migrations                 ·  setCompleted                ·          -  ·          -  ·      26908  ·               1  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  acceptBid                   ·     145138  ·     153468  ·     150688  ·              36  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  buyToken                    ·          -  ·          -  ·     139866  ·               9  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  delistToken                 ·          -  ·          -  ·      18996  ·               2  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  disableAuction              ·          -  ·          -  ·      57007  ·               1  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  listToken                   ·          -  ·          -  ·      68861  ·              11  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  pause                       ·          -  ·          -  ·      28401  ·               4  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  placeBid                    ·      72620  ·      84389  ·      82077  ·              56  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  rejectBid                   ·          -  ·          -  ·      36544  ·               6  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  setArtistRoyaltyPercentage  ·          -  ·          -  ·      29595  ·              65  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  setKoCommissionAccount      ·          -  ·          -  ·      29808  ·              65  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  setPlatformPercentage       ·          -  ·          -  ·      29089  ·              71  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2         ·  withdrawBid                 ·          -  ·          -  ·      35646  ·               6  ·             -  │
  ······························|······························|·············|·············|·············|··················|·················
  |  Deployments                                               ·                                         ·  % of limit      ·                │
  ·····························································|·············|·············|·············|··················|·················
  |  ArtistAcceptingBids                                       ·          -  ·          -  ·    2357148  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  ArtistAcceptingBidsV2                                     ·          -  ·          -  ·    3625383  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  ArtistEditionBurner                                       ·          -  ·          -  ·     782249  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  ArtistEditionControls                                     ·          -  ·          -  ·     827058  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  ArtistEditionControlsV2                                   ·          -  ·          -  ·    1055278  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  KnownOriginDigitalAsset                                   ·          -  ·          -  ·    3143524  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  KnownOriginDigitalAssetV2                                 ·          -  ·          -  ·    5750155  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  Migrations                                                ·          -  ·          -  ·     224195  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  SelfServiceAccessControls                                 ·          -  ·          -  ·     392667  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  SelfServiceEditionCuration                                ·          -  ·          -  ·    1446605  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  SelfServiceEditionCurationV2                              ·          -  ·          -  ·    1552973  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  SelfServiceEditionCurationV3                              ·          -  ·          -  ·    1460062  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  SelfServiceEditionCurationV4                              ·          -  ·          -  ·    2528671  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  SelfServiceFrequencyControls                              ·          -  ·          -  ·    1064190  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  TokenMarketplace                                          ·          -  ·          -  ·    2440829  ·             0 %  ·             -  │
  ·····························································|·············|·············|·············|··················|·················
  |  TokenMarketplaceV2                                        ·    3313871  ·    3313935  ·    3313931  ·             0 %  ·             -  │
  ·------------------------------------------------------------|-------------|-------------|-------------|------------------|----------------·