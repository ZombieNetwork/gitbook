---
description: >-
  BLOOD Center: BLOOD 토큰($BLD)을 Deposit 하고 이자 수익을 관리하는 기능입니다. BLOOD 토큰을 예치하면 하루
  1%의 이자가 실시간으로 생성됩니다. 이자 수익은 언제든지 Compound(재예치) 또는 Claim(인출) 하실 수 있습니다.
---

# Staking

![](<../.gitbook/assets/blood center.PNG>)

### Data

{% hint style="info" %}
**Available Rewards:** 처분 가능 이자 수량입니다. 총 예치금 (Deposits) 기준 하루에 1%의 이자가 발생하며, 실시간으로 이자가 더해져서 표시되는 BLOOD 토큰 수량입니다. 하단에 현 USDT 시세 기준으로 현재 금액 가치가 표시되어 있습니다. 오늘 하루 쌓인 이자 수량을 표시하는 것이 아니라 현재까지 발생한 이자 중 재예치(Compound)나 인출(Claim) 처리를 하지 않고 쌓여 있는 전체 수량입니다. 여기에 표시되는 수량만큼 언제든지 재예치 또는 인출을 수행하실 수 있습니다. 단, 재예치 또는 인출 시 표시된 수량 전체에 대해 수행되며, 수량을 나누어 재예치 또는 인출을 할 수는 없습니다. Whale Tax(고래세)를 적용 받는 경우 매일 발생하는 이자 수익은 Whale Tax(고래세) 만큼 차감된 후에 처분 가능 이자 (Available Rewards) 수량에 더해 집니다.

**Deposits:** 누적 예치 수량으로 현재까지 누적된 예치금 전체의 BLOOD 토큰 수량입니다. 하단에 현 USDT 시세 기준으로 현재 금액 가치가 표시되어 있습니다. 이 수량에는 참여자가 직접 예치한 수량, 재예치한 수량, Airdrop으로 받은 수량, 추천인 보상금으로 받은 수량 등이 모두 합산되어 총 BLOOD 토큰 예치금(Deposits) 수량으로 표시됩니다. 이 수량을 기준으로 하루 1%의 이자가 실시간으로 계산됩니다.

**Claimed:** 누적 인출 수량으로 서비스 참여 후 발생한 총 누적 이자 수량 중 재예치 또는 인출을 수행한 누적 BLOOD 토큰 수량입니다. 재예치 기능의 경우 처분 가능 이자(Available Rewards) 수량을 우선 인출한 후 다시 예치하는 방식으로 이루어지며 누적 인출 수량(Claimed)에 합산됩니다.

**Rewarded:** 추천인 보상 제도를 통해 보상 받은 BLOOD 토큰 누적 수량입니다. 추천인 보상 제도를 통해 보상을 받기 위해서는 사전에 추천인 보상용 NFT를 필요한 수량만큼 지갑에 보유하고 있어야 합니다. [(\[참고\] 추천인 보상제도)](../undefined-1/undefined-1.md)
{% endhint %}

### Deposit: BLOOD 토큰 Staking (단일 예치) 기능

지갑에 보유하고 있는 BLOOD 토큰을 좀비 네트워크에 예치할 수 있는 기능입니다. 예치하고자 하는 수량을 입력하신 후 Deposit(예치) 버튼을 클릭하시면 됩니다. Deposit(예치) 기능 수행 시 예치하고자 하는 수량의 10%는 세금이 부과되어 차감되며, 90%의 수량만큼만 예치되게 됩니다[(\[참고\] 좀비 네트워크 특징 > Tax 시스템)](../undefined-1/tax-whale-tax.md). BLOOD 토큰을 예치하는 즉시 하루 1% 이자 지급이 개시됩니다.

### Compound: Available Rewards에 대한 재예치 기능

Available Rewards(처분 가능 이자 수량)을 재예치하여 예치금(Deposits) 총량을 늘리고 복리 이자 수익을 얻을 수 있는 기능입니다. 재예치 시에는 5%의 세금이 부과되어 차감된 후 재예치 하고자 하는 Available Rewards의 95% 만큼만 예치 됩니다[(\[참고\] 좀비 네트워크 특징 > Tax 시스템)](../undefined-1/tax-whale-tax.md). 재예치 후 화면 상의 예치금(Deposits)은 해당 수량(5% 세금 차감 후 수량)만큼 증가하며, Max Payouts(최대 인출 가능 수량)은 예치금 수량 증가분의 365%에 해당하는 만큼 수량이 증가합니다. 동시에 누적인출수량(Claimed)은 재예치한 Available Rewards 수량(5% 세금 차감 전)만큼 증가합니다. 재예치한 금액 역시 예치금(Deposits)이기 되기 때문에 다른 예치금과 마찬가지로 인출할 수 없습니다. Available Rewards 남아 있다면 하루 중 언제든지 수시로 실행이 가능합니다.

### Claim: Available Rewards에 대한 인출 기능

Available Rewards(처분 가능 이자 수량)을 인출하는 기능입니다. 인출(Claim) 시에는 10%의 세금이 부과되어 차감된 후 인출 하고자 하는 Available Rewards의 90% 만큼만 인출되어 지갑에 전송되게 됩니다[(\[참고\] 좀비 네트워크 특징 > Tax 시스템)](../undefined-1/tax-whale-tax.md). 인출 후 화면 상의 예치금(Deposits)과 Max Payout(최대 인출 가능 수량)은 변화가 없으며, 누적인출수량(Claimed)은 인출한 Available Rewards 수량(10% 세금 차감 전)만큼 증가합니다. Available Rewards가 남아 있다면 하루 중 언제든지 수시로 실행이 가능합니다. 인출하여 지갑에 전송된 BLOOD 토큰은 판매(Sell)를 하여 KLAY 코인으로 교환할 수 있으며 Airdrop 전송을 할 수도 있습니다. &#x20;

