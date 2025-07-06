# EVM Wallet Message Signer

이 프로젝트는 Rabby, MetaMask와 같은 EVM 기반 지갑을 이용해 사용자가 특정 메시지에 서명할 수 있도록 도와주는 간단한 웹페이지입니다.  
본인 지갑 소유 증명(예: 거래소 인증, KYC 등)이 필요할 때 활용 가능합니다.

## 특징
- 지갑 연결(Rabby/MetaMask)
- 메시지 입력 및 서명
- 생성된 서명 결과 출력 및 복사 용이

## 사용 방법

1. [index.html](./index.html) 파일을 브라우저에서 실행하세요.
2. 'Connect Wallet' 버튼을 클릭해 Rabby 또는 MetaMask 지갑에 연결합니다.
3. 'Enter the message to sign' 입력창에 증명할 메시지를 입력하세요.
4. 'Sign' 버튼을 클릭하면, 지갑에서 서명 요청이 뜹니다.
5. 서명 후, 결과(Signature)를 확인할 수 있습니다.

## 필요 환경

- 브라우저(Chrome, Firefox 등)
- MetaMask, Rabby 등 EVM 호환 브라우저 지갑

## 주의사항

- 서명은 개인키를 사용하는 민감한 작업이니, 신뢰할 수 있는 환경에서만 사용하세요.
- 이 프로젝트는 테스트/개인 용도로만 사용하세요.

## 라이선스
MIT

---

# EVM Wallet Message Signer (English)

This project is a simple web page that helps users sign arbitrary messages using EVM-based wallets such as Rabby or MetaMask.  
You can use it to prove wallet ownership to parties like exchanges (e.g. for verification or KYC purposes).

## Features
- Connect EVM wallets (Rabby/MetaMask)
- Enter and sign any message
- Display and easily copy the generated signature

## How to Use

1. Open the [index.html](./index.html) file in your web browser.
2. Click the 'Connect Wallet' button to connect your Rabby or MetaMask wallet.
3. Enter the message to sign in the input box.
4. Click the 'Sign' button. Your wallet will ask you to confirm the message signing.
5. After signing, your signature will be displayed in the result area.

## Requirements

- Web browser (Chrome, Firefox, etc.)
- EVM-compatible browser wallet such as MetaMask or Rabby

## Notes

- Signing a message uses your private key; do this only in a trusted environment.
- This project is intended for testing or personal use only.

## License
MIT