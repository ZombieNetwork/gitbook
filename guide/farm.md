---
description: >-
  BLOOD Reservoir: BLD-KLAY 유동성 Pool 풀에 유동성을 공급하고 수익을 얻을 수 있는 기능 입니다. KLAY 코인으로
  BLD-KLAY LP 토큰을 구매하면 자동으로 유동성 풀에 예치됩니다. 다양한 수익원을 통해 창출된 배당금을 유동성 참여 비율에 따라
  KLAY 코인으로 분배 받으실 수 있습니다.
---

# Farm

![](../.gitbook/assets/Farm-deposit-redeposit.png)

### Data

{% hint style="info" %}
**Available Rewards:** BLD-KLAY 유동성을 제공한 대가로 받은 KLAY 코인 수량 중 Compound(재예치, 유동성 추가 제공) 또는 Claim (인출) 등의 처리를 하지 않은 수량 입니다. BLD-KLAY 유동성 보상금은 배당금 풀에서 유동성 공급자의 예치 지분율에 따라 지급됩니다. 유동성 배당금 풀은 유동성 공급 및 해제 시 부과되는 거래세(Transaction Tax)를 통해 구성됩니다.

**Total BLD-KLAY:** 참여자가 KLAY 토큰으로 BLOOD 토큰을 구매하여 BLD-KLAY 풀 유동성 제공 시, BLD-KLAY LP 토큰이 생성되어 지급됩니다. 참여자가 보유하고 있는 전체 BLD-KLAY LP 토큰 수량이 표시됩니다. Rewards에 남아 있는 KLAY 수량을 Compound 할 경우 해당 KLAY 수량에 상응하는 BLD-KLAY LP 토큰 수량이 추가 됩니다.

**Stake:** BLD-KLAY LP 토큰 전체 수량 대비 참여자가 보유한 수량 비율입니다. Rewards(유동성 풀 제공 보상금) 발생 시 BLD-KLAY LP 토큰 보유자들에게 이 보유 비율을 기준으로 분배됩니다.

**Total Withdrawn:** 유동성 풀 해제로 돌려받은 KLAY 누적 수량 입니다.
{% endhint %}

### Deposit: BLD-KLAY 유동성 공급 기능

BLOOD-KLAY 유동성 풀에 대한 유동성 공급은 KLAY 코인으로 BLOOD 토큰을 구매하면서 BLD-KLAY 페어를 구성하는 형태로 이루어집니다. 현재 지갑에 보유하고 있는 KLAY 수량 중에서 유동성 공급에 예치할 KLAY 수량을 입력하면, 하단에 BLD-KLAY LP 토큰 예상 구매량이 표시됩니다. 구매를 실행하시려면 BUY(구매) 버튼을 클릭하시면 됩니다.

유동성 공급 시 10%의 거래세(Transaction Tax)가 부과됩니다. BLD-KLAY LP 토큰을 구매하는 데 사용된 KLAY의 2%는 즉시 유동성 공급자들에게 유동성 공급 비율대로 분배하여 지급됩니다. 5%는 Farm 계약 배당금 풀로 이동하는데, Farm 계약 배당금풀에 쌓인 전체 금액 중 2%를 매일 유동성 공급자들에 분배하여 지급합니다. 나머지 3%는 BLD-KLAY 유동성풀에 잠기게(Lock in) 됩니다.

유동성 공급을 통해 얻는 수익은 배당금 풀을 통한 Rewards 이외에도 Swap 메뉴에서 거래가 일어나는 경우 Swap fee (토큰 교환 수수료) 1%가 별도 부과 되는데 이 금액 역시 유동성 공급자들에게 에치 지분율에 따라 지급 됩니다.

### Withdraw: BLD-KLAY 유동성 공급 해제 기능

BLD-KLAY LP 토큰 형태로 유동성을 공급하고 있다가 이를 해제하고 KLAY로 돌려받을 수 있는 기능입니다. 유동성을 해제하고 싶은 BLD-KLAY LP 토 수량을 입력한 후 Withdraw(해제) 버튼을 누르시면 됩니다. 유동성 공급 해제 시에도 10%의 거래세가 부과되어 차감된 후 BLOOD 토큰으로 반환됩니다.&#x20;

### Compound

Rewards로 얻은 KLAY 코인을 인출하지 않고 BLD-KLAY 풀에 유동성을 추가로 제공할 수 있는 기능입니다. 재예치 시 해당 KLAY 수량에 상응하는 BLD-KLAY LP 토큰이 Total BLD-KLAY 수량에 더해져 표시됩니다.

### Claim

Rewards(유동성 풀 제공 보상금)으로 얻은 KLAY를 지갑으로 인출하는 기능입니다.