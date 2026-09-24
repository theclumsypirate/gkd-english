# gkd-english

<p align="center">
<a href="https://gkd.li/"><img src="https://e.gkd.li/2a0a7787-f2dd-4529-a885-93f3b8c857c3" alt="GKD.LI" width="40%" /></a>
</p>

Custom screen-tap Android app based on [advanced selectors](https://gkd.li/guide/selector) + [subscription rules](https://gkd.li/guide/subscription) + [snapshot inspection](https://github.com/gkd-kit/inspect)

Through custom rules, on specified interfaces, when specified conditions are met (such as specific text existing on screen), tap specific nodes or positions or perform other actions

- **Quick actions**

  Helps you simplify some repetitive processes, such as certain software automatically confirming computer login

- **Skip flows**

  Some software may have annoying flows during startup. This app can help you tap to skip the flow

## Disclaimer

**This project is open source under [GPL-3.0-only](/LICENSE) and is for learning and exchange only. Commercial or illegal use is prohibited.**

## Install

<a href="https://gkd.li/guide/"><img src="https://e.gkd.li/f23b704d-d781-494b-9719-393f95683b89" alt="Download from GKD.LI" width="32%" /></a><a href="https://play.google.com/store/apps/details?id=li.songe.gkd"><img src="https://e.gkd.li/f63fabeb-0342-4961-a46d-cac61b0f8856" alt="Download from Google Play" width="32%" /></a><a href="https://github.com/gkd-kit/gkd/releases"><img src="https://e.gkd.li/c1ef2bb9-7472-46d5-9806-81b4c37e5b4d" alt="Download from GitHub releases" width="32%" /></a>

If you encounter issues, please first check the [FAQ](https://gkd.li/guide/faq)

## Screenshots

|                                                               |                                                               |                                                               |
| ------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------- |
| ![img](screen-1.png)                                          | ![img](screen-2.png)                                          | ![img](screen-3.png)                                          |
| ![img](screen-4.png)                                          | ![img](screen-5.png)                                          | ![img](screen-6.png)                                          |

## Subscription

GKD **does not provide rules by default**. You need to add local rules yourself, or obtain remote rules through subscription links

You can also quickly build your own remote subscription through [subscription-template](https://github.com/gkd-kit/subscription-template)

Third-party subscription lists can be viewed at <https://github.com/topics/gkd-subscription>

To join this list, click the settings icon in the top right corner of the repository homepage and add `gkd-subscription` in Topics

<details>
<summary>Example image - Add to Topics (click to expand)</summary>

![image](https://e.gkd.li/9e340459-254f-4ca0-8a44-cc823069e5a7)

</details>

## Selector

A selector similar to a CSS selector, which can relate to node context information, making it easier and more precise to find the target node

<https://gkd.li/guide/selector>

[@[vid="menu"] < [vid="menu_container"] - [vid="dot_text_layout"] > [text^="ad"]](https://i.gkd.li/i/14881985?gkd=QFt2aWQ9Im1lbnUiXSA8IFt2aWQ9Im1lbnVfY29udGFpbmVyIl0gLSBbdmlkPSJkb3RfdGV4dF9sYXlvdXQiXSA-IFt0ZXh0Xj0i5bm_5ZGKIl0)

<details>
<summary>Example image - Selector path view (click to expand)</summary>

[![image](https://e.gkd.li/a2ae667b-b8c5-4556-a816-37743347b972)](https://i.gkd.li/i/14881985?gkd=QFt2aWQ9Im1lbnUiXSA8IFt2aWQ9Im1lbnVfY29udGFpbmVyIl0gLSBbdmlkPSJkb3RfdGV4dF9sYXlvdXQiXSA-IFt0ZXh0Xj0i5bm_5ZGKIl0)

</details>

## Derivatives

Derivative projects during development that are being used by gkd, which may be helpful to you

- [kotlin-json5](https://github.com/lisonge/kotlin-json5)
- [kotlin-codeorigin](https://github.com/lisonge/kotlin-codeorigin)
- [android-api-diff](https://github.com/android-cs/android-api-diff)
- [remap](https://github.com/lisonge/remap)
- [priv-kit](https://github.com/priv-kit/priv-kit)

## Donate

If GKD is useful to you, you can support the project through the following links

<https://github.com/lisonge/sponsor>

Or go to [Google Play](https://play.google.com/store/apps/details?id=li.songe.gkd) and leave a good review
