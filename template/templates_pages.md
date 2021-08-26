---
theme: uncover
marp: true
paginate: true
---

<style scoped>
section { 
    font-size: 400%; 
}
</style>

HTMLタグを使いたい場合は、ページ右肩の真ん中のボタン（Marp のマークのボタン）を押して、［Open extension settings］を選ぶ。そして、「Enable HTML」のチェックボックスにチェックを入れる。

---

文字サイズを変更したいページの冒頭に、以下の内容を入れる。これで、文字サイズは4倍になる。style scoped を設定すると、その領域だけにWebページのスタイルが適用になる。

```
<style scoped>
section { 
    font-size: 400%; 
}
</style>
```

---

<style>
@import url('https://fonts.googleapis.com/css?family=Noto Sans JP&display=swap');
section {
    font-family: 'Noto Sans JP', serif;
}
</style>


scoped でなければ全ページに適用


---

<style scoped>
section {
    background-color: ivory;
}
</style>

# おおお

---

<style scoped>
section {
    background: linear-gradient(to right, #16a085, #f4d03f); 
    color: white;
}
</style>

# かっこいい
