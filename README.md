# ECS

## 작업순서
- IAM CLI 사용 가능한 사용자 생성 (MFA 인증 사용)
- AWS CLI 설치 및 Credentail 등록 with 세션토큰(default등록)
- 도커 이미지 생성
- ECR 생성 (AWS CLI로 생성)
- ECR을 사용할 수 있게 사용자에게 권한 부여
- ECR에 PUSH (AWS CLI로 푸시)
- AWS Fargate