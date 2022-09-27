# Solana_cli

## 설치

```
sh -c "$(curl -sSfL https://release.solana.com/v1.14.3/install)"
```

```
$ brew install solana
```

## 계정생성

```
solana-keygen new
```

## Solana CLI 클라이언트를 구성

```
solana config set --keypair /root/.config/solana/id.json
```

## 클라이언트를 Solana 네트워크에 바인딩

```
solana config set --url <network_url>
```

```
(dev net -- development)        https://api.devnet.solana.com
(test net -- staging)           https://api.testnet.solana.com
(main net -- production)        https://api.mainnet-beta.solana.com
```

## 서버실행

```
solana logs
```

## 잔액확인

```
solana balance

```

## 에어드롭 :dev서버에서 배포하기위해 sol요청

- dev서버에서만 가능
- 서명확인가능

```
solana airdrop 1
```

```
solana balance
```

## 솔라나 총 공급량
