### Software Engineer (Remote, Contract)

**idOS Network**
_September 2025 – December 2025_

#### Responsibilities

- Designed and developed a Kotlin Multiplatform SDK for the idOS decentralized identity platform, targeting Android, iOS, JVM, and JavaScript from a single codebase.
- Implemented a full KWIL protocol client with JSON-RPC transport, transaction signing, challenge-response authentication, and nonce-based ordering.
- Built a dual-mode encryption layer supporting both password-based (Scrypt KDF + NaCl Box) and MPC-based (Shamir's Secret Sharing) key management.
- Ensured cryptographic consistency across platforms using platform-specific bindings (Lazysodium on JVM/Android, libsodium C interop on iOS, tweetnacl on JS).
- Developed iOS interoperability using SKIE for seamless Kotlin-to-Swift async/throws bridging and libsodium XCFramework integration.
- Set up multi-channel distribution: Maven Central (Android AAR, JVM JAR), npm (JS/TS), Swift Package Manager, and GitHub Releases.
- Built fully functional reference apps for both Android and iOS, showcasing the idOS credential system and SDK integration.
- Wrote end-to-end and integration tests across all platform targets using Kotest.

#### Technical Skills

Kotlin Multiplatform, Ktor, kotlinx.serialization, NaCl/libsodium, Scrypt, EIP-712, KWIL, Gradle, SKIE, Swift, TypeScript, Android (Compose, EncryptedFile, WalletConnect)

#### Soft Skills

Independent delivery, cross-platform problem-solving, remote collaboration, thorough documentation

#### Summary

Contracted to build the official idOS SDK as a Kotlin Multiplatform project, enabling developers on Android, iOS, JVM, and web to integrate decentralized identity services — including encrypted credential storage, access grant management, and wallet operations. The core challenge was achieving cryptographic consistency and API parity across four platform targets while implementing a custom KWIL protocol client and a dual-mode encryption system (local and MPC). Delivered a production-ready SDK with automated publishing pipelines, comprehensive platform-specific test coverage, and fully functional reference apps for Android and iOS demonstrating the credential system end-to-end.

---
