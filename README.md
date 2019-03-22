# LiveCalc

## RTA条件
* Homebrewがインストールされている
* Xcode最新版がインストールされている
* Brewfile実行済
* anyenvがインストールされている
* anyenv rbenvがインストールされている
* direnvがインストールされている
* githubにssh鍵が登録されている

## 攻略チャート
* githubでリポジトリ作成
* Xcodeで~/gitにプロジェクト作成
* git initしてremoteセット
* echo "2.5.1" > .ruby-version
* Gemfile作成(cocoapods, fastlane)
* bundle install --path vendor/bundle
* vi .envrc: FASTLANE_PASSOWRD=AppleIDのパスワード, FASTLANE_USER=AppleID, MATCH_PASSWORD=match用の任意のパスフレーズ
* Podfile作成
* bundle exec pod install
* .gitignoreをcurlで取得
* bundle exec fastlane init
* bundle exec fastlane match; fastlane match development
* bundle exec fastlane add_plugin appicon
* Fastfile編集, lane :test, :beta, :icon
* Simple View Project
* Main.Storyboard編集
* ViewController編集
