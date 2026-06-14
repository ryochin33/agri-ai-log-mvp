# agri-ai-log-mvp

農業AIログのMVPです。

## 目的

農家さんがLINEに音声で農作業内容を送ると、AIが作業内容を整理し、Googleスプレッドシートに保存し、LINEに整理結果を返信する仕組みを作ります。

## 技術構成

LINE音声入力  
↓  
Webhook  
↓  
GAS（TypeScript）  
↓  
Gemini  
↓  
Googleスプレッドシート保存  
↓  
LINE返信  

## MVPで検証すること

- 音声入力なら農家さんが記録を続けられるか
- AIの整理結果が実用的か
- 翌年見返せる農作業ログになるか

## 使う技術

- LINE Messaging API
- Google Apps Script
- TypeScript
- Gemini API
- Google スプレッドシート
