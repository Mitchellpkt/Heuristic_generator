# Heuristic_generator

![https://raw.githubusercontent.com/Mitchellpkt/Heuristic_generator/master/images/v1_image.png](https://raw.githubusercontent.com/Mitchellpkt/Heuristic_generator/master/images/v1_image.png)

Notes:

D := data, includes both
- metadata 
  - fee
  - weight
  - number of inputs
  - number of outputs
  - tx_extra
  - unlock_time
- engineered features
  - tx_extra (e.g. length and Levenshtein string distances)
  - decoy selection (e.g. offset-corrected median age)
  - transaction tree periodicity
  - transaction tree distances (times or hops)
  - change chains
- on-chain data (e.g. signer scalars)
- network-layer data (e.g. originating IP address)
