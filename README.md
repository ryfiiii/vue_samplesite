# vue_samplesite
vue.js3で作成した簡単なウェブサイト

# Source
ルートディレクト上のindex.html内の#app上にvueで作成したhtml, js, cssを上乗せしている形になります。

src/App.vue すべてのコンポーネントを読み込み、配置しています

src/components 表示内容を小分けしています。AppHeader.vueでページの切り替えの処理を実装しています。

src/router.js ここで指定したリンクにアクセスがあった時に表示する内容を振り分けています。
