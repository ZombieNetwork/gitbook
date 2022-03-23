# 개발팀 KYC 및 컨트랙트 Audit

### 개발팀 KYC 인증

좀비 네트워크는 Assure DeFi ([https://www.assuredefi.io/](https://www.assuredefi.io))에서 KYC 인증을 받았습니다.&#x20;

좀비 네트워크 팀은 프로젝트에 대한 커뮤니티의 신뢰를 구축하는 것을 최우선 목표로 하며 좀비 네트워크 서비스의 더 나은 발전과 지속 가능성을 위해 항상 노력하겠습니다.&#x20;

Assure DeFi에서 인증한 KYC 내역은 다음 사이트에서 확인하실 수 있습니다.  [https://www.assuredefi.io/projects/zombie-network](https://www.assuredefi.io/projects/zombie-network/)

다음 이미지는 Assure DeFi 발행한 좀비 네트워크 KYC 인증 NFT 이미지 입니다.

![](<../.gitbook/assets/Zombie Network NFT.gif>)

### 좀비 네트워크 컨트랙트 Audit

좀비네트워크의 비즈니스 로직 및 컨트랙트 부분은 드립 네트워크와 동일합니다. 사용한 코드도 드립네트워크의 오픈소스를 수정없이 사용했습니다. 해당 컨트랙트는 이미 Certik를 통해 Audit을 받은 코드 입니다. 드립 네트워크와 차이가 나는 부분은 BR34P Token을 NFT 로 대체한 부분입니다. NFT 관련 컨트랙트 역시 Audit을 받은 오픈 소스의 컨트랙트를 참조하여 개발하였고, 좀비네트워크 연동 부분에서는 개수 참조 정도로만 사용되어있습니다. 따라서 현재 좀비 네트워크 컨트랙트 코드들은 모두 Audit을 받은 코드 입니다.

비록 Audit을 거친 컨트랙트 코드들이라 하더라도 전체적으로 Audit을 다시 받을 수 있다면 더 안심할 수 있긴 하겠지만, 동일한 코드에 대해 중복해서 별도의 Audit을 받는 것은 일정과 비용 효율상 다소 불필요하다고 판단하고 있습니다. 다만, 향후 좀비 네트워크 서비스 확장 시 고유한 신규 컨트랙트 기능이 추가될 것입니다. 이 때 넉넉한 일정으로 전문 컨트랙트 감사 업체를 통 전체적으로 Audit을 받을 계획입니다.
