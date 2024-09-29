# Angularとは
TypeScriptを採用したフルスタックなフレームワーク
Google製、2016~v2としてリリース、旧作はAngularJS
大規模なアプリケーション開発向け
RxJS（Reactive Extensions for JavaScript）を採用、非同期処理を簡単に記述可能
非常に構造化、コンポーネント指向、厳密な型付け
厳密に仮想DOMを使用していませんが、直接DOM操作とも異なる
→変更検出メカニズム（Change Detection）を用い、変更が発生した際に効率的にDOMを再描画
→開発者がDOM操作を明示的に管理することはないが、最適化されたDOM操作

# 01_AngularをDockerコンテナ上で動作させる
docker compose up -d

