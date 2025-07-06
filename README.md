# EVM Wallet Message Signer

이 프로젝트는 Rabby, MetaMask와 같은 EVM 기반 지갑을 이용해 사용자가 특정 메시지에 서명할 수 있도록 도와주는 간단한 웹페이지입니다.  
본인 지갑 소유 증명(예: 거래소 인증, KYC 등)이 필요할 때 활용 가능합니다.

## 특징
- 지갑 연결(Rabby/MetaMask)
- 메시지 입력 및 서명
- 생성된 서명 결과 출력 및 복사 용이

## 사용 방법

1. 터미널에서 프로젝트 폴더로 이동하세요.
2. [http-server](https://www.npmjs.com/package/http-server) 패키지를 설치하지 않았다면 먼저 설치합니다.
   ```bash
   npm install -g http-server
   ```
3. 다음 명령어로 로컬 서버를 실행합니다.
   ```bash
   http-server .
   ```
4. 브라우저에서 `http://localhost:8080` 주소로 접속하세요.
5. 'Connect Wallet' 버튼을 클릭해 Rabby 또는 MetaMask 지갑에 연결합니다.
6. 'Enter the message to sign' 입력창에 증명할 메시지를 입력하세요.
7. 'Sign' 버튼을 클릭하면, 지갑에서 서명 요청이 뜹니다.
8. 서명 후, 결과(Signature)를 확인할 수 있습니다.

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

1. Open a terminal and navigate to your project folder.
2. If you haven't installed [http-server](https://www.npmjs.com/package/http-server), install it:
   ```bash
   npm install -g http-server
   ```
3. Start the local server:
   ```bash
   http-server .
   ```
4. Open your browser and go to `http://localhost:8080`.
5. Click the 'Connect Wallet' button to connect your Rabby or MetaMask wallet.
6. Enter the message to sign in the input box.
7. Click the 'Sign' button. Your wallet will ask you to confirm the message signing.
8. After signing, your signature will be displayed in the result area.

## Requirements

- Web browser (Chrome, Firefox, etc.)
- EVM-compatible browser wallet such as MetaMask or Rabby

## Notes

- Signing a message uses your private key; do this only in a trusted environment.
- This project is intended for testing or personal use only.

## License
MIT