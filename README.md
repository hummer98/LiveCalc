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
* buddle exec
* echo "2.5.1" > .ruby-version
* Gemfile作成(cocoapods, fastlane)
* bundle install --path vendor/bundle
* Podfile作成
* bundle exec pod install
* .gitignoreをcurlで取得
* fastlane init
* fastlane match; fastlane match development
* Fastfile編集
* Simple View Project
* Main.Storyboard編集
* ViewController編集
