## Well-Architected Framework
클라우드 환경에서 안전하고, 안정적이며, 성능이 뛰어나고, 비용 효율적인 애플리케이션 및 워크로드를 설계하고 운영하기 위한 AWS(Amazon Web Services)의 모범 사례, 지침 및 핵심 원칙 집합

config
계정이랑 사용자 차이가 뭔지 정확히 이해하기!

## IAM 핵심 구성
### 인증 Authentication -> who?
### 인가 Authorization  -> what?
### IAM은 사용자(Users), 그룹(Groups), 역할(Roles), 정책(Policies)로 구성됨
## 사용자(Users)

## 그룹(Groups)
사용자들의

## 정책(Policies) 
권한을 부여하는 기능 

policy는 JSON파일로 구성 되어 있으며 여러 요소로 구성된다.

인라인 정책 (Inline Policy 

관리형 정책 (Managed Policy)

사용자단위 권한, 리소스단위 권한

리소스가 사용자



## 역할(Roles)
API호출할때 인증과 권한이 필요한데 그때 roles가 필요함
굳이 API가 필요 없으면 roles가 필요없음
권한을 임시로 줌

모자 개념이랑 비슷함 모자를 쓰면 다른권한은 사용 못하고 모자에 있는 권한만 사용 가능

대신 모자를 벗으면 다시 원래 있던 권한을 사용 가능

그룹한테 부여는 못함 



권한정책


신뢰정책

IAM는 




STS 내부 서비스

--------------------------------------------------------------------------
## VPC

리소스 격리는 계정>VPC>sabmut
vpc는 리전안에서 만드는 것

서브넷
서브넷은 모두 Private이고 Public으로 바꾸고싶으면 3가지 충족하면 가
Private Subnet
Public Subnet


리전 vpc az 서브넷 
























