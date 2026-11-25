# 拡張子
## 1.プログラムを書く拡張子
### `.tsx`(TypeScript + JSX)
Reactの画面と動きを書くファイル。  
HTMLのようなタグ(`<div>,<br>`)をプログラムの中に直接かけるのが特徴。  
ex. App.tsx,main.tsx
### `.ts`(TypeScript)
画面の見た目を含まない裏側の処理を書くファイル。  
API通信の処理や、バックエンド(Hono)、データベースの設計図(Drizzle)などに使う。  
ex. index.ts,schema.ts  

## 2.データ保存・設定の拡張子
### `.json`
設定ファイルやデータのやり取りに使う拡張子。APIがフロントエンドにメモのデータを渡すときもJSON形式。  
ex. package.json(プロジェクトにどんなライブラリを入れるか記録)  
　　tsconfig.json(TypeScriptの設定をする)
### `.sqlite`
データベース本体のファイル。入力したメモのデータがすべて1つのファイルの中に保存される。  
ex. app.sqlite  
### `.sql`
データベースに「テーブルを作って」「データを追加して」と命令するための言語が書かれたファイル。Drizzle ORMが自動で生成してくれる。  

## 3.見た目・解説書の拡張子
### `.css`
画面のデザイン（色・大きさ・配置）を整えるファイル。  
ex. style.css
### `.html`
Webページの土台となるファイル。  
Reactでは最初に1枚だけ用意され、その中身を`.tsx`が書き換えて画面を作る。  
ex. index.html
### `.md`
説明書やメモ書きのファイル。  
ex. README.md
