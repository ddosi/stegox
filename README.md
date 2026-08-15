# StegoX 深层隐写术 / StegoX Deep Steganography

> 🔗 **在线地址 / Project URL:** [https://www.ddosi.org/stegox/](https://www.ddosi.org/stegox/)
>
> 🌐 **语言切换 / Language Toggle:** [中文](#chinese) | [English](#english)

---
<img width="1720" height="1366" alt="图片" src="https://github.com/user-attachments/assets/ea85720f-da25-4b38-aa6e-1cadf6ad72dc" />

<a id="chinese"></a>

## 🇨🇳 中文描述

**项目名称：** StegoX 深层隐写术
**开发者/来源：** 🔰雨苁ℒ🔰 (www.ddosi.org)

### 项目简介
StegoX 是一款专注于隐私保护的本地数据隐写工具。它允许用户将敏感信息（文本或文件）加密并隐藏到普通的载体文件中（如图片、视频、文档或可执行文件），生成的新文件在外观和大小上与原载体几乎完全一致，从而实现隐蔽传输或存储。

### 核心功能与特点
-   **纯本地处理：** 所有加密和解密操作均在浏览器本地完成，**绝不上传**任何数据到服务器，确保隐私安全。
-   **灵活的密钥机制：** 支持使用强密码字符串作为密钥，也支持使用任意文件（限100MB内）作为“密钥文件”，增加了破解难度。
-   **广泛的格式支持：** 载体文件支持任意格式，最大可达 5GB；隐藏内容支持文本与文件混合嵌入。
-   **无损提取：** 解密时可完美还原隐藏的原始数据。

### 技术细节
-   **加密算法：** 采用 AES-256-GCM 进行高强度加密。
-   **哈希算法：** 使用 SHA-512 进行密钥派生与完整性校验。
-   **运行模式：** 自动识别内存模式或流式模式以适配不同大小的文件处理。

[⬆️ 返回顶部 / Back to Top](#stegox-深层隐写术--stegox-deep-steganography)

---

<a id="english"></a>

## 🇬🇧 English Description

**Project Name:** StegoX Deep Steganography
**Developer/Source:** 🔰雨苁ℒ🔰 (www.ddosi.org)

### Project Overview
StegoX is a privacy-focused, local steganography tool designed to securely hide sensitive data (text or files) within ordinary carrier files such as images, videos, documents, or executables. The resulting stego-file appears identical to the original carrier, enabling covert storage or transmission of secret information.

### Key Features
-   **100% Local Processing:** All encryption and decryption operations are performed entirely in the user's browser. **No data is ever uploaded** to any server, guaranteeing maximum privacy.
-   **Flexible Key Options:** Users can secure their hidden data with either a strong text password or a dedicated key file (up to 100MB), providing versatile security layers.
-   **Broad Compatibility:** Supports any file format as a carrier (up to 5GB) and allows mixing text and files as hidden payloads.
-   **Lossless Extraction:** Hidden content can be perfectly restored without any data loss during decryption.

### Technical Specifications
-   **Encryption:** Utilizes AES-256-GCM for robust symmetric encryption.
-   **Hashing:** Employs SHA-512 for key derivation and integrity verification.
-   **Processing Modes:** Automatically switches between memory mode and streaming mode to efficiently handle files of varying sizes.

[⬆️ 返回顶部 / Back to Top](#stegox-深层隐写术--stegox-deep-steganography)
