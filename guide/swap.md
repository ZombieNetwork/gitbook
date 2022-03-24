---
description: >-
  BLOOD Store: BLOOD 토큰($BLD)을 거래(Buy & Sell) 할 수 있는 기능입니다. BLOOD 토큰을
  Deposit(예치) 하려면 여기서 Buy 기능을 이용하여 BLOOD 토큰을 구매하셔야 합니다. 이자 수익을 Claim(인출) 한 후
  Sell 기능을 이용하여 KLAY 토큰으로 교환하실 수 있습니다.
---

# Swap

![](<../.gitbook/assets/swap (1).PNG>)

### Data

{% hint style="info" %}
**Price:** USDT 기준 금액입니다.&#x20;

**KLAY Balance:** 현재 연결된 지갑의 KLAY 잔고입니다.&#x20;

**BLD Balance:** 현재 연결된 지갑의 BLD 잔고입니다.
{% endhint %}

### Buy BLD: BLOOD 토큰 구매 기능

BLOOD 토큰을 구매할 수 있는 기능입니다. BLOOD 토큰은 KLAY 코인을 이용해서 구매할 수 있습니다. KLAY를 이용해 BLOOD 토큰을 구매하시면 지갑에서 해당 수량만큼 KLAY 코인 수량이 차감되고 BLOOD 토큰 수량이 증가합니다. 구매에 사용될 KLAY 코인 수량을 입력하시면 하단에 받을 수 있는 BLOOD 토큰 수량이 표시됩니다. 구매를 진행하려면 구매(Buy) 버튼을 클릭하시면 됩니다.

좀비 네트워크 사이트에서 BLOOD 토큰 구매 시에는 별도의 세금이 부과되지 않습니다만, 타 SWAP 사이트에서 BLOOD 토큰 구매 시에는 10%의 세금이 부과되어 차감된 후 90%의 수량만 지갑에 전송됩니다. [(\[참고\] 좀비 네트워크 특징> Tax 시스템)](../features/tax.md)

### Sell BLD: BLOOD 토큰 판매 기능

지갑에 보유하고 있는 BLOOD 토큰을 판매할 수 있는 기능입니다. BLOOD 토큰을 KLAY 코인으로 Swap 하는 형태로 판매가 이루어집니다. 판매하고자 하는 BLOOD 토큰 수량을 입력하시면 하단에 교환 받을 수 있는 KLAY 코인 예상 수량이 표시됩니다. 판매를 실행하려면 판매(Sell) 버튼을 클릭하시면 됩니다.

BLOOD 토큰을 판매하게 되면 지갑에서 해당 수량만큼 BLOOD 토큰 수량이 감소하고, KLAY 코인 수량이 증가합니다.

BLOOD 토큰 판매 시 10%의 거래세(Transaction Tax)가 부과됩니다. 판매하신 BLOOD 토큰 수량에서 10%를 거래세로 차감하고 90%에 해당하는 수량만 KLAY 코인으로 Swap 되어 지갑으로 전송됩니다.  [(\[참고\] 좀비 네트워크 특징> Tax 시스템)](../features/tax.md)

### Swap Fee (토큰 교환 수수료) &#x20;

BLOOD 토큰 구매 또는 판매 시 BLD-KLAY 유동성 풀을 이용해서 Swap 거래로 이루어집니다. 따라서 유동성 공급자들에게 보상을 제공하기 위해 Swap fee (토큰 교환 수수료) 1%가 부과됩니다. 이는 일 1% 예치 이자를 제공하는 Tax Pool 구성을 위한 거래세(Transaction Tax) 부과와는 별도로 운영됩니다.
