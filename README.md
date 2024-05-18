# Discord-Guild-Authentication
Discordの特定ギルドに属しているユーザーかを外部のクライアントが意識することなく認証認可できるようにするやつ。

DiscordのOAuth2からユーザーがツール側で指定したギルドIDに属しているか判定。  
属していればツール側で新たにトークンを生成し返すことでクライアント側で認証認可を実現できるようにする。