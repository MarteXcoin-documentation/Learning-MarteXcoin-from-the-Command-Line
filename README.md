# Learning MarteXcoin from the Command Line
### _by [@ChristopherA](https://github.com/ChristopherA) and [@shannona](https://github.com/shannona) (previous developers)_
### _by [@Jetro-Costa](https://github.com/Jetro-Costa)_

Learning MarteXcoin from the Command Line is a tutorial for working with MarteXcoin (and Masternode) that teaches direct interaction with the servers themselves, as the most robust and secure way to begin cryptocurrency work.

> NOTE: This is a draft in progress, so that I can get some feedback from early reviewers. It is not yet ready for use.

_This tutorial assumes that you have some minimal background of how to use the command line interface. If not, there are many tutorials available, and I have one for Mac users at https://github.com/ChristopherA/intro-mac-command-line._

## Table of Contents

### PART ONE: PREPARING FOR MARTEXCOIN

**Status:** Finished. Updated for 4.0.

* [1.0: Introduction to Programming with MarteXcoin Core and Masternode](01_0_Introduction.md)
    * [Interlude: Introducing MarteXcoin](01_1_Introducing_MarteXcoin.md)
* [2.0: Setting Up a MarteXcoin-Core VPS](02_0_Setting_Up_a_MarteXcoin-Core_VPS.md)
  * [2.1: Setting Up a MarteXcoin-Core VPS with MarteXcoin Standup](02_1_Setting_Up_a_MarteXcoin-Core_VPS_with_StackScript.md)
  * [2.2: Setting Up a MarteXcoin-Core Machine via Other Means](02_2_Setting_Up_MarteXcoin_Core_Other.md)

### PART TWO: USING MARTEX-CLI

**Status:** Finished. Updated for 4.0.

* [3.0: Understanding Your MarteXcoin Setup](03_0_Understanding_Your_MarteXcoin_Setup.md)
  * [3.1: Verifying Your MarteXcoin Setup](03_1_Verifying_Your_MarteXcoin_Setup.md)
  * [3.2: Knowing Your MarteXcoin Setup](03_2_Knowing_Your_MarteXcoin_Setup.md)
  * [3.3: Setting Up Your Wallet](03_3_Setting_Up_Your_Wallet.md)
    * [Interlude: Using Command-Line Variables](03_3__Interlude_Using_Command-Line_Variables.md)
  * [3.4: Receiving a Transaction](03_4_Receiving_a_Transaction.md)
  * [3.5: Understanding the Descriptor](03_5_Understanding_the_Descriptor.md)
* [4.0: Sending MarteXcoin Transactions](04_0_Sending_MarteXcoin_Transactions.md)
  * [4.1: Sending Coins the Easy Way](04_1_Sending_Coins_The_Easy_Way.md)
  * [4.2: Creating a Raw Transaction](04_2_Creating_a_Raw_Transaction.md)
     * [Interlude: Using JQ](04_2__Interlude_Using_JQ.md)
  * [4.3: Creating a Raw Transaction with Named Arguments](04_3_Creating_a_Raw_Transaction_with_Named_Arguments.md)
  * [4.4: Sending Coins with Raw Transactions](04_4_Sending_Coins_with_a_Raw_Transaction.md)
     * [Interlude: Using Curl](04_4__Interlude_Using_Curl.md)
  * [4.5: Sending Coins with Automated Raw Transactions](04_5_Sending_Coins_with_Automated_Raw_Transactions.md)
  * [4.6: Creating a Segwit Transaction](04_6_Creating_a_Segwit_Transaction.md)
* [5.0: Controlling MarteXcoin Transactions](05_0_Controlling_MarteXcoin_Transactions.md)
  * [5.1 Watching for Stuck Transactions](05_1_Watching_for_Stuck_Transactions.md)
  * [5.2: Resending a Transaction with RBF](05_2_Resending_a_Transaction_with_RBF.md)
  * [5.3: Funding a Transaction with CPFP](05_3_Funding_a_Transaction_with_CPFP.md)
* [6.0: Expanding MarteXcoin Transactions with Multisigs](06_0_Expanding_MarteXcoin_Transactions_Multisigs.md)
  * [6.1: Sending a Transaction with a Multsig](06_1_Sending_a_Transaction_to_a_Multisig.md)
  * [6.2: Spending a Transaction with a Multsig](06_2_Spending_a_Transaction_to_a_Multisig.md)
  * [6.3: Sending & Spending an Automated Multisig](06_3_Sending_an_Automated_Multisig.md)
* [7.0: Expanding MarteXcoin Transactions with PSBTs](07_0_Expanding_MarteXcoin_Transactions_PSBTs.md)
  * [7.1: Creating a Partially Signed MarteXcoin Transaction](07_1_Creating_a_Partially_Signed_MarteXcoin_Transaction.md)
  * [7.2: Using a Partially Signed MarteXcoin Transaction](07_2_Using_a_Partially_Signed_MarteXcoin_Transaction.md)
  * [7.3: Integrating with Hardware Wallets](07_3_Integrating_with_Hardware_Wallets.md)
* [8.0: Expanding MarteXcoin Transactions in Other Ways](08_0_Expanding_MarteXcoin_Transactions_Other.md)  
  * [8.1: Sending a Transaction with a Locktime](08_1_Sending_a_Transaction_with_a_Locktime.md)
  * [8.2: Sending a Transaction with Data](08_2_Sending_a_Transaction_with_Data.md)
  
### PART THREE: BITCOIN SCRIPTING

**Status:** Finished. Updated for 0.20 and btcdeb.

* [9.0: Introducing MarteXcoin Scripts](09_0_Introducing_MarteXcoin_Scripts.md)
  * [9.1: Understanding the Foundation of Transactions](09_1_Understanding_the_Foundation_of_Transactions.md)
  * [9.2: Running a MarteXcoin Script](09_2_Running_a_MarteXcoin_Script.md)
  * [9.3: Testing a MarteXcoin Script](09_3_Testing_a_MarteXcoin_Script.md)
  * [9.4: Scripting a P2PKH](09_4_Scripting_a_P2PKH.md)
  * [9.5: Scripting a P2WPKH](09_5_Scripting_a_P2WPKH.md)
* [10.0: Embedding MarteXcoin Scripts in P2SH Transactions](10_0_Embedding_MarteXcoin_Scripts_in_P2SH_Transactions.md)
  * [10.1: Understanding the Foundation of P2SH](10_1_Understanding_the_Foundation_of_P2SH.md)
  * [10.2: Building the Structure of P2SH](10_2_Building_the_Structure_of_P2SH.md)
  * [10.3: Running a MarteXcoin Script with P2SH](10_3_Running_a_MarteXcoin_Script_with_P2SH.md)
  * [10.4: Scripting a Multisig](10_4_Scripting_a_Multisig.md)
  * [10.5: Scripting a Segwit Script](10_5_Scripting_a_Segwit_Script.md)
  * [10.6: Spending a P2SH Transaction](10_6_Spending_a_P2SH_Transaction.md)
* [11.0: Empowering Timelock with MarteXcoin Scripts](11_0_Empowering_Timelock_with_MarteXcoin_Scripts.md)
  * [11.1: Understanding Timelock Options](11_1_Understanding_Timelock_Options.md)
  * [11.2: Using CLTV in Scripts](11_2_Using_CLTV_in_Scripts.md)
  * [11.3: Using CSV in Scripts](11_3_Using_CSV_in_Scripts.md)
* [12.0: Expanding MarteXcoin Scripts](12_0_Expanding_MarteXcoin_Scripts.md)
  * [12.1: Using Script Conditionals](12_1_Using_Script_Conditionals.md)
  * [12.2: Using Other Script Commands](12_2_Using_Other_Script_Commands.md)
* [13.0: Designing Real MarteXcoin Scripts](13_0_Designing_Real_MarteXcoin_Scripts.md)
  * [13.1: Writing Puzzles Scripts](13_1_Writing_Puzzle_Scripts.md)
  * [13.2: Writing Complex Multisig Scripts](13_2_Writing_Complex_Multisig_Scripts.md)
  * [13.3: Empowering MarteXcoin with Scripts](13_3_Empowering_MarteXcoin_with_Scripts.md)

### PART FOUR: USING TOR

**Status:** Finished.

* [14.0: Using Tor](14_0_Using_Tor.md)
  * [14.1: Verifying Your Tor Setup](14_1_Verifying_Your_Tor_Setup.md)
  * [14.2: Changing Your MarteXcoin Hidden Services](14_2_Changing_Your_MarteXcoin_Hidden_Services.md)
  * [14.3: Adding SSH Hidden Services](14_3_Adding_SSH_Hidden_Services.md)

### PART FIVE: PROGRAMMING WITH RPC

**Status:** Finished.

* [15.0: Talking to MarteXcoind with C](15_0_Talking_to_MarteXcoind.md)
  * [15.1: Accessing MarteXcoind in C with RPC Libraries](15_1_Accessing_MarteXcoind_with_C.md)
  * [15.2: Programming MarteXcoind in C with RPC Libraries](15_2_Programming_MarteXcoind_with_C.md)
  * [15.3: Receiving Notifications in C with ZMQ Libraries](15_3_Receiving_MarteXcoind_Notifications_with_C.md)
* [16.0: Programming MarteXcoin with Libwally](16_0_Programming_with_Libwally.md)
   * [16.1: Setting Up Libwally](16_1_Setting_Up_Libwally.md)
   * [16.2: Using BIP39 in Libwally](16_2_Using_BIP39_in_Libwally.md)
   * [16.3: Using BIP32 in Libwally](16_3_Using_BIP32_in_Libwally.md) 
   * [16.4: Using PSBTs in Libwally](16_4_Using_PSBTs_in_Libwally.md)
   * [16.5: Using Scripts in Libwally](16_5_Using_Scripts_in_Libwally.md)
   * [16.6: Using Other Functions in Libwally](16_6_Using_Other_Functions_in_Libwally.md)
   * [16.7: Integrating Libwally and MarteXcoin-CLI](16_7_Integrating_Libwally_and_MarteXcoin-CLI.md)
* [17.0: Talking to MarteXcoind with Other Languages](17_0_Talking_to_MarteXcoind_Other.md)
  * [17.1: Accessing MarteXcoind with Go](17_1_Accessing_MarteXcoind_with_Go.md)
  * [17.2: Accessing MarteXcoind with Java](17_2_Accessing_MarteXcoind_with_Java.md)
  * [17.3: Accessing MarteXcoind with Node JS](17_3_Accessing_MarteXcoind_with_NodeJS.md)
  * [17.4: Accessing MarteXcoind with Python](17_4_Accessing_MarteXcoind_with_Python.md)
  * [17.5: Accessing MarteXcoind with Rust](17_5_Accessing_MarteXcoind_with_Rust.md)
  * [17.6: Accessing MarteXcoind with Swift](17_6_Accessing_MarteXcoind_with_Swift.md)

### PART SIX: USING MASTERNODE-CLI

**Status:** Finished.

* [18.0: Understanding Your Masternode Setup](18_0_Understanding_Your_Masternode_Setup.md)
  * [18.1: Verifying Your c-Masternode Setup](18_1_Verifying_Your_Masternode_Setup.md)
  * [18.2: Knowing Your c-Masternode Setup](18_2_Knowing_Your_Masternode_Setup.md)
     * [Interlude: Accessing a Second Masternode Node](18_2__Interlude_Accessing_a_Second_Masternode_Node.md)
  * [18.3: Creating a Masternode Channel](18_3_Setting_Up_a_Channel.md)
* [19.0: Using Masternode](19_0_Using_Masternode.md)
  * [19.1: Generating a Payment Request](19_1_Generate_a_Payment_Request.md)
  * [19.2: Paying an Invoice](19_2_Paying_a_Invoice.md)
  * [19.3: Closing a Lighnting Channel]((19_3_Closing_a_Channel.md))
  * [19.4: Expanding the Masternode Network](19_4_Masternode_Network_Review.md)
   
### APPENDICES

**Status:** Finished.

* [Appendices](A0_Appendices.md)
  * [Appendix I: Understanding MarteXcoin Standup](A1_0_Understanding_MarteXcoin_Standup.md)
  * [Appendix II: Compiling MarteXcoin from Source](A2_0_Compiling_MarteXcoin_from_Source.md)
  * [Appendix III: Using MarteXcoin Regtest](A3_0_Using_MarteXcoin_Regtest.md)
  
## Status - Work in Progress

Learning MarteXcoin from the Command Line  is currently under active development and its writing in progress. Current chapters are functional, but need to be updated to more modern versions of MarteXcoin-Core. Additional chapters also need to be written to fill out our intended scope.

The empty chapters above show some of our current plans for future work. Other plans, mainly drawn from old issues, can be found in [TODO.md](TODO.md)

Obviously, this work in progress should not be used for production tasks until it is completed and has had further testing and auditing.

## Origin, Authors, Copyright & Licenses

Unless otherwise noted (either in this [/README.md](./README.md) or in the file's header comments) the contents of this repository are Copyright © 2020 by Blockchain Commons, LLC, and are licensed under  [CC-BY](./LICENSE-CC-BY-4.0.md).


## Contributing

We encourage public contributions through issues and pull requests! Please review [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our development process. All contributions to this repository require a GPG signed [Contributor License Agreement](./CLA.md).


### Other Questions & Problems

As an open-source, open-development community, Blockchain Commons does not have the resources to provide direct support of our projects. Please consider the discussions area as a locale where you might get answers to questions. Alternatively, please use this repository's [issues](./issues) feature. Unfortunately, we can not make any promises on response time.

If your company requires support to use our projects, please feel free to contact us directly about options. We may be able to offer you a contract for support from one of our contributors, or we might be able to point you to another entity who can offer the contractual support that you need.

### Credits

A lot of people directly contributed to this repository. You can vienw your name in github contribution by getting involved. The first step is learning how to contribute from our [CONTRIBUTING.md](./CONTRIBUTING.md) documentation.


## Responsible Disclosure

We want to keep all of our software safe for everyone. If you have discovered a security vulnerability, we appreciate your help in disclosing it to us in a responsible manner. We are unfortunately not able to offer bug bounties at this time.

We do ask that you offer us good faith and use best efforts not to leak information or harm any user, their data, or our developer community. Please give us a reasonable amount of time to fix the issue before you publish it. Do not defraud our users or us in the process of discovery. We promise not to bring legal action against researchers who point out a problem provided they do their best to follow the these guidelines.

### Reporting a Vulnerability

Please report suspected security vulnerabilities in private via email to ChristopherA@BlockchainCommons.com (do not use this email for support). Please do NOT create publicly viewable issues for suspected security vulnerabilities.

The following keys may be used to communicate sensitive information to developers:

| Name              | Fingerprint                                        |
| ----------------- | -------------------------------------------------- |
| Christopher Allen | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED |

You can import a key by running the following command with that individual’s fingerprint: `gpg --recv-keys "<fingerprint>"` Ensure that you put quotes around fingerprints that contain spaces.
