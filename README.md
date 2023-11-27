# ECS

## 작업순서
- IAM CLI 사용 가능한 사용자 생성 (MFA 인증 사용)
- AWS CLI 설치 및 Credentail 등록 with 세션토큰(default등록)
- 도커 이미지 생성
- ECR을 사용할 수 있게 사용자에게 권한 부여
- ECR 생성 (AWS CLI로 생성)
- ECR에 PUSH (AWS CLI로 푸시)
- AWS Fargate (다른 이미지로 테스트해봄)
- ECR에 올라간 이미지를 ECS에서 사용하는 방법을 배워야 함(코파일럿으로 해봄)
- 코파일럿 매니페스트 && 커멘드 (공부해야함 - 진행중)
https://aws.github.io/copilot-cli/en/docs/manifest/overview/
https://aws.github.io/copilot-cli/en/docs/commands/docs/