# Frequently asked questions

[Back to the overview](../README.en.md) · [简体中文](FAQ.zh-CN.md)

## Can I download and install it now?

Not yet. This repository is being prepared for release and currently contains product information, preview images, and animated demonstrations, with no installer or executable. Verified installation and update instructions will be published alongside an installer.

## What if I see a security warning during installation?

Current test installers are not Windows code-signed, so Windows may show an unknown-publisher or reputation warning. Microsoft explains that signing status, publisher reputation, and file reputation affect SmartScreen decisions. Even new signed apps can trigger warnings. [Microsoft’s explanation of SmartScreen reputation](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation).

A reputation warning is not itself a virus detection, and it does not prove that a file is safe. Check the file’s source. If a virus or Trojan is explicitly reported, pause installation and keep the security software name, detection name, file version, and alert screenshot for investigation. Do not dismiss the detection or disable protection.

AVO’s current theming functionality does not rewrite Codex’s original installation files; themes load at runtime. Signing status and verification information for official installers will be provided in the corresponding release notes.

## Which product does it work with?

AVOROVA provides themes, skins, and desktop customization for the ChatGPT desktop app / Codex on Windows. OpenAI now calls the desktop application ChatGPT, with Codex still available inside it. See the [official desktop app overview](https://learn.chatgpt.com/docs/app) and [Windows documentation](https://learn.chatgpt.com/docs/windows/windows-app).

The themes and demonstrations here focus on the desktop app's Codex interface. AVO is not a browser skin extension for chatgpt.com. Supported Windows and desktop app versions will be listed in the release notes. Compatibility with every version is not promised.

## Can I use a third-party API relay service?

Yes. AVO offers Codex theme mode and Codex++ mode. Users who connect to a third-party API relay service through Codex++ can also use AVO themes.

Install Codex++ separately and configure your service endpoint, API key, and available models there. Then select Codex++ mode in AVO. Service and model availability depend on Codex++ and your relay provider; AVO does not supply a relay service or API credits. Codex theme mode does not require Codex++.

The quota battery shows Codex plan quota. Third-party API relay balances are not displayed yet.

## What kinds of themes are available?

The theme library groups themes into types such as video, image, motion, and glass. The animation at the top of the README shows three themes inside complete Codex window demonstrations. Full-size stills let you inspect interface details.

## Can I interact with these animations?

No. They are short loops recorded from the website's interface demonstrations, not desktop recordings or themes running inside GitHub. The Brainstorm and quota battery animations explain the workflows using sample conversations and quota data.

## How does Brainstorm work?

Select text in a Codex conversation and choose “Save to Brainstorm.” Continue writing, paste images, and save changes automatically on your computer. Open existing notes from the title-bar entry. When the original message can be located, return to its conversation for context.

## Does the quota battery add usage or spend reset cards?

No. It displays the remaining Codex plan quota, reset information, and reset-card count available from the account. It is a read-only display and does not increase or reset limits. Third-party API relay balances are not displayed yet.

## Why do the previews show 74%, 63%, and ×2?

Those values are sample data used to explain the interface. They are not a real user's account status or an allowance included with the product.

## Can I apply a theme directly from the website?

That flow requires an installed AVO version that supports website theme application and has registered the appropriate protocol. Your browser may also ask you to confirm opening AVO. The installer is not yet published, and the full installation-to-application flow still needs release validation.

## Can I submit themes to a community?

The theme community and community submissions are not open at this stage.

## Will this repository include the application source?

This repository is for product information, documentation, and future release materials. It does not provide the AVO application source code or Codex source code.

## Is AVOROVA an official OpenAI product?

No. AVOROVA is an independent project and is not affiliated with or endorsed by OpenAI.
