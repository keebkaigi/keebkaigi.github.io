# KeebKaigi

"Kaigi" for Keyboard Enthuiasits ⌨️

- 🏯 [2023](https://keebkaigi.org/2023/) - May 10, Matsumoto, Nagano, Japan
- ⚔️ [2024 KeebWorld Conference](https://keebkaigi.org/2023/) - Dec. 12, Matsue, Shimane, Japan


# トークのタイトル、プロフィールの入力・編集方法

- このリポジトリをCloneする
- `/data/year_2024/schedule.yml` からご自分のトークを探して編集
- <img width="701" alt="keeb-readme" src="https://github.com/user-attachments/assets/af20ffe0-933a-4f71-831b-51bd17004757">
- プルリクエストを送ってください 🙏
- こんな感じでサイトに反映されます
  - <img width="1206" alt="keeb-readme-sample" src="https://github.com/user-attachments/assets/96755c04-70ea-4e61-85cf-80b09c1fa033">


## ローカル確認方法 (Optional)

見た目の確認は運営の方でもやりますので、ローカル環境での確認は任意で、Yamlの方だけ編集いただければ大丈夫です。興味のある方は以下の方法でご確認ください。  
[Middleman](https://middlemanapp.com/jp/) で作ってます。

- `$ gem install middleman`
- `$ cd keebkaigi.github.io`
- `$ bundle install`
- `$ bundle exec middleman`
- See -> `https://localhost:4567/2024/`
