# CSE 427 · Week 6 worksheet

Student number: 2022123457  Surname: yilmaz
Parameters: L = 157  H = 3  B = 64  Card = 4  p = 0.95
Resource: /sensors/yilmaz
msp430-size  wsn-server: text __ data __ bss __   wsn-client: text __ data __ bss __

## Identity map
| Identifier | Your value | Layer | Same after parent change? | Same after hardware swap? |
|---|---|---|---|---|
| Human label | | | | |
| CoAP resource | | | | |
| MQTT-SN topic | | | | |
| IPv6 address | | | | |
| 802.15.4 address | | | | |

## E1 · Hop by hop (Token: __)
| Hop | 802.15.4 src | 802.15.4 dst | IPv6 src | IPv6 dst | Hop Limit | Uri-Path | 6LoWPAN hdr bytes |
|---|---|---|---|---|---|---|---|
| 1 | | | | | | | |
| 2 | | | | | | | |
| 3 | | | | | | | |
Prediction (before capture):
Answers:

## E2 · IPHC decode
| Field | Hop 1 bits | Hop 1 meaning | Middle hop bits | Middle hop meaning |
|---|---|---|---|---|
| IPHC bytes (hex) | | | | |
| TF | | | | |
| NH | | | | |
| HLIM | | | | |
| CID SAC SAM | | | | |
| M DAC DAM | | | | |
| Inline bytes | | | | |
| UDP NHC | | | | |
| Total IPv6+UDP on air | | | | |
Measured MAC header: __ bytes  →  M = __

## E3 · Fragmentation
| Quantity | Predicted | Observed | How |
|---|---|---|---|
| CoAP response size | | | |
| Uncompressed datagram size | | | |
| Compressed datagram size | | | |
| N (no alignment) | | | |
| N (8-byte alignment) | | | |
| FRAGN offsets | | | |
| Tag hop 1 / last hop | | | |
| p^N | | | |
Answers:

## E4 · Separate response
| # | Time | Direction | Type | Code | MID | Token |
|---|---|---|---|---|---|---|
| 1 | | | | | | |
| 2 | | | | | | |
| 3 | | | | | | |
Answers:

## E5 · Block-Wise vs fragments
| Quantity | Config B | Config A |
|---|---|---|
| CoAP exchanges | | |
| Data frames on air | | |
| Total bytes | | |
| Fragmentation header? | | |
| Block2 values | | |
| Resent after one loss | | |

## Scenario card 4
1.
2.
3.
4.
5.