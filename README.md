# Sentiric SIP Client SDK

**Description:** A client SDK for connecting to the Sentiric SIP Server, enabling SIP communication (softphone, mobile applications, WebRTC in browsers).

**Core Responsibilities:**
*   Implementing the SIP protocol to register with `sentiric-sip-server`, make, and receive calls.
*   Handling RTP/SRTP media stream sending and receiving.
*   Providing a user-friendly API for developers to integrate SIP functionality into their applications.
*   (If applicable) Implementing WebRTC for browser-based real-time communication.

**Technologies:**
*   JavaScript/TypeScript (for WebRTC/Web SDK)
*   Swift (for iOS SDK) / Kotlin (for Android SDK)
*   SIP/WebRTC libraries for chosen language.

**API Interactions (As a Protocol Client):**
*   Communicates directly with `sentiric-sip-server` via SIP and RTP/SRTP protocols.

**Local Development:**
1.  Clone this repository: `git clone https://github.com/sentiric/sentiric-sip-client-sdk.git`
2.  Navigate into the directory: `cd sentiric-sip-client-sdk`
3.  Install dependencies: `npm install` (for JS/TS) or relevant build tools for native languages.
4.  Run tests or a sample application: `npm test` or `npm run example`.

**Configuration:**
Refer to SDK documentation and sample code for client-side configuration, including SIP server details and authentication.

**Deployment:**
Distributed as a package (npm, Maven, Cocoapods) or compiled executable/library.

**Contributing:**
We welcome contributions! Please refer to the [Sentiric Governance](https://github.com/sentiric/sentiric-governance) repository for coding standards and contribution guidelines.

**License:**
This project is licensed under the [MIT License](LICENSE).
