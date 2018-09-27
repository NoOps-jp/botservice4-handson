# Bot Builder v4 によるチャットボット開発: 超入門

## ハンズオンのゴール

このハンズオンでは、以下を理解することをゴールとしています。

- プロジェクト構成の理解
- ステート管理の基本
- WaterfallStep による会話フローの基本

## 前提

このハンズオンでは、以下を前提としています。

- OS: Windows 10 / Visual Studio 2017 (version 15.8.5)
- 開発言語: C#
- [Nuget パッケージ: Microsoft.Bot.Builder](https://www.nuget.org/packages/Microsoft.Bot.Builder/) Version 4.0.7 以上
- [Bot Builder V4 SDK Template for Visual Studio](https://marketplace.visualstudio.com/items?itemName=BotBuilder.botbuilderv4) Version 4.0.6.6

## 概要

2018 年 9 月 24 日に開催された [Microsoft Ignite 2018](https://www.microsoft.com/en-us/ignite) にて Bot Builder v4 (Bot Framework V4) の GA が発表されました。

- https://azure.microsoft.com/ja-jp/updates/microsoft-bot-framework-v4-sdk-is-now-generally-available/

新しくなった Bot Framework による基本機能のハンズオンとなります。

以下図の会話フローの実装を元に、基本機能を学びます。

![image](images/flow.png)

## ハンズオンの構成

| セクション                                                  | 概要                                                                                                     |
| ----------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| [00_Preparation.md](./00_Preparation.md)                    | 開発に必要な環境を準備します。                                                                           |
| [01_Create_Project.md](./01_Create_Project.md)              | プロジェクトテンプレートからプロジェクトを作成し、プロジェクトの構成やデバッグでの実行方法を確認します。 |
| [02_WelcomeMessage](./02_WelcomeMessage.md)                 | ウェルカムメッセージの表示を実装します。                                                                 |
| [03_Basic_State_Management](./03_Basic_State_Management.md) | ステート管理と、シンプルな Prompt の実装をします。                                                       |
| [04_WaterfallSteps](./04_WaterfallSteps.md)                 | WaterfallStep による会話フローの実装をします。                                                           |
| [Summary](./99_Summary.md)                                  | 本ハンズオンのまとめ。                                                                                   |
