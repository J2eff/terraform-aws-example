# Create VPC Using terraform without remote state ( local state )

## Before VPC
---

### 사전지식

- [리전과 가용영역](https://kangmin517.tistory.com/92)


### What is vpc

VPC는 가상의 사설 네트워크 공간을 의미
- [AWS 공식 문서](https://docs.aws.amazon.com/ko_kr/vpc/latest/userguide/what-is-amazon-vpc.html)

- [읽어볼 만한 글1](https://medium.com/harrythegreat/aws-%EA%B0%80%EC%9E%A5%EC%89%BD%EA%B2%8C-vpc-%EA%B0%9C%EB%85%90%EC%9E%A1%EA%B8%B0-71eef95a7098)

- [읽어볼 만한 글2](https://inpa.tistory.com/entry/AWS-%F0%9F%93%9A-VPC-%EC%82%AC%EC%9A%A9-%EC%84%9C%EB%B8%8C%EB%84%B7-%EC%9D%B8%ED%84%B0%EB%84%B7-%EA%B2%8C%EC%9D%B4%ED%8A%B8%EC%9B%A8%EC%9D%B4-NAT-%EB%B3%B4%EC%95%88%EA%B7%B8%EB%A3%B9-NACL-Bastion-Host)

## IaC using terraform for aws cloud operation
```
terraform init
```

필요한 provider , 모듈 등 다운로드


```
terraform plan
```
실제 terraform 코드의 전 단계 생성, 변경, 삭제될 결과물을 미리 보여줌

```
terraform apply 
```
terraform 코드의 실제 적용

```
terraform destroy 
```
적용된 테라폼 코드의 삭제
