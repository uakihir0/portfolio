---
title: "TwGallery (2022-)"
weight: 5
resources:
  - src: ss1.png
    params:
      weight: -100
---

**[Twitter Illustration Gallery](https://tw-gallery.vercel.app/)** は Twitter でお気に入りが一定数以上集まったイラストについて、ギャラリー形式で紹介をするサイトになっています。Twitter の検索機能を使って投稿を探し、それがイラストで一定以上のクオリティーを持っているかどうか？ は機械学習を用いて判別しています。[Zenn の記事](https://zenn.dev/uakihir0/articles/220628-gallery)にて、簡単にこのサイトについて解説を行っています。

##### 使用技術

- クライアント: TypeScript, React.js, Next.js, Chakra-UI, Vercel
- データ生成部: Kotlin, GitHub Actions, TensorFlow
