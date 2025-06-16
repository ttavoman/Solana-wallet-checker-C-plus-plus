# Solana Wallet Checker C++: Powerful and Customizable Tool

**SolanaChecker** is a C++ tool designed for interacting with the Solana blockchain, providing users with a range of functions for checking wallet status and managing their digital assets. Written in C++, this project allows you to build and customize your own Solana wallet checker.

<p align="left">
    <img src="/exports/load.webp" />
</p>

## Program Features, Built with C++

1.  **Check Solana Address Balance:** Quickly check the current Solana balance on any specified address.

<p align="left">
    <img src="/exports/small.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess the security of tokens.

<p align="left">
    <img src="/exports/footer.webp" />
</p>

3.  **Track Solana Addresses:** Get notifications via a Telegram bot.

4.  **Wallet Data from Mnemonic Phrase:** Extract wallet information from the seed phrase.

<p align="left">
    <img src="/exports/close.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate a new Solana wallet.

<p align="left">
    <img src="/exports/visual.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (for Research):** A brute-force function (for educational purposes only).

<p align="left">
    <img src="/exports/tall.webp" />
</p>

## Setting Up Telegram

Configure Telegram.

## Getting Started: Download or Build

Download a pre-compiled build or build the project in C++.

## Building the Project with C++

Building from source enables customization.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** if you haven't.
2.  Add vcpkg to your PATH.
3.  Run:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build the project.

### Building via Visual Studio:

1.  Open the solution in Visual Studio.
2.  Ensure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed via **vcpkg**.
2.  Compile (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: C++ Control

Use the command line:

1.  **-s / -search**: Brute-force.
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: Generate.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info.
5.  **-b / -balance (ADDRESS)**: Check balance.

## Notes

-   Use responsibly.
-   Protect your data.

## License

This project is licensed under the [MIT License](/LICENSE).

Update:  Monday 16 June 2025 Resolved dead links in migration guide