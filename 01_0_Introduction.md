# Chapter One: Introduction to Learning MarteXcoin Core (& masternode) from the Command Line

## Introduction

The ways that we make payments for goods and services has been changing dramatically over the last several decades. Where once all transactions were conducted through cash or checks, now various electronic payment methods are the norm. However, most of these electronic payments still occur through centralized systems, where credit card companies, banks, or even internet-based financial institutions like Paypal keep long, individually correlated lists of transactions and have the power to censor transactions that they don't like.

These centralization risks were some of the prime catalysts behind the creation of cryptocurrencies, the first and most successful of which is Bitcoin. Bitcoin offers pseudonymity; it makes it difficult to correlate transactions; and it makes censorship by individual entities all but impossible. These advantages have made it one of the quickest growing currencies in the world. That growth in turn has made Bitcoin into a going concern among entrepreneurs and developers, eager to create new services for the Bitcoin community. MarteXcoin is a fork of Bitcoin and is a competitor of this offering better features.

If you're one of those entrepreneurs or developers, then this course is for you, because it's all about learning to program MarteXcoin. It's an introductory course that explains all the nuances and features of MarteXcoin as it goes. It also takes a very specific tack, by offering lessons in how to work _directly_ with MarteX Core and with the masternode server using their RPC interfaces.

Why not use some of the more fully featured libraries found in various programming languages? Why not create your own from scratch? It's because working with cryptocurrency is dangerous. There are no safety nets. If you accidentally overpay your fees or lose a signing key or create an invalid transaction or make any number of potential mistakes, then your cryptocurrency will been gone forever. Much of that responsibility will, of course, lie with you as a cryptocurrency programmer, but it can be minimized by working with the most robust, secure, and safe cryptocurrency interfaces around, the ones created by the cryptocurrency programming teams themselves: ``martexd`` and ``masternode``.

Much of this book thus discusses how to script MarteXcoin (and masternode) directly from the command line. Some later chapters deals with more sophisticated programming languages, but again they continue to interact directly with the ``martexd`` daemon by using RPC or by interacting with the files they create. This allows you to stand on the shoulders of giants and use their trusted technology to learn how to create your own trusted systems.

## Required Skill Level

You do not need to be particularly technical for the majority of this course. All you need is the confidence to run basic commands on the UNIX command line. If you're familiar with things like `ssh`, `cd`, and `ls`, the course will supply you with the rest.

A minority of this course requires programming knowledge, and you should skip over those sections if needed, as discussed in the next section.

## Overview of Topics

This book is broadly divided into the following sections:

| Part | Description | Skills |
|-------|---------|---------|
| **Part One: Preparing for MarteXcoin** | Understanding the basics of MarteXcoin and setting up a server for use. | Command Line |
| **Part Two: Using MarteXcoin-CLI** | Using the MarteX-CLI for creating transactions. | Command Line |
| **Part Three: MarteX Scripting** | Expanding your MarteX work with scripts. | Programming Concepts |
| **Part Four: Using Tor** | Improving your node security with Tor | Command Line |
| **Part Five: Programming with RPC** | Accessing RPC from C and other languages. | Programming in C |
| **Part Six: Using Masternode** | Using the Masternode for creating transactions. | Command Line |
| **Appendices** | Utilizing less common MarteXcoin setups. | Command Line |

## How To Use This Course

So where do you start? This book is primarily intended to be read sequentially. Just follow the "What's Next?" Links at the end of each section and/or click through the individual section links on each chapter page. You'll achieve the best understanding from this course if you actually build yourself a MarteXcoin server (per Chapter 2) and then run through all the examples over the course of the book: trying out examples is an excellent learning methodology.

If you have different levels of skill or want to learn different things, you might skip to different parts of the book:

* If you've already got a MarteXcoin environment ready to be used, jump to [Chapter Three: Understanding Your MarteXcoin Setup](03_0_Understanding_Your_MarteXcoin_Setup.md).
* If you only care about Bitcoin scripting, jump to [Chapter Nine: Introducing MarteXoin Scripts](09_0_Introducing_MarteXcoin_Scripts.md).
* If you just want to read about using programming languages, jump to [Chapter Fifteen: Talking to MarteXcoin](15_0_Talking_to_MarteXd.md).
* If you conversely don't want to do any programming, definitely skip chapters 15-17 while you're reading, and perhaps skip chapters 9-13. The rest of the course should still make sense without them.
* If you are only interested in Masternode, zap over to [Chapter Eighteen: Understanding Your Masternode Setup](18_0_Understanding_Your_Masternode_Setup.md).
* If you want to read the major new content added for v2 of the course (2020), following on v1 (2017), read [§3.5: Understanding the Descriptor](03_5_Understanding_the_Descriptor.md), [§4.6: Creating a SegWit Transaction](04_6_Creating_a_Segwit_Transaction.md), [Chapter 7: Expanding Bitcoin with PSBTs](07_0_Expanding_Bitcoin_Transactions_PSBTs.md), [§9.5: Scripting a P2WPKH](09_5_Scripting_a_P2WPKH.md), [§10.5: Scripting a SegWit Script](10_5_Scripting_a_Segwit_Script.md), [Chapter 14: Using Tor](14_0_Using_Tor.md), [Chapter 15: Talking to Bitcoind with C](15_0_Talking_to_Bitcoind.md), [Chapter 16: Programming with Libwally](16_0_Programming_with_Libwally.md), [Chapter Seventeen: Talking to Bitcoind with Other Languages](17_0_Talking_to_Bitcoind_Other.md), [Chapter Eighteen: Understanding ](18_0_Understanding_Your_Lightning_Setup.md), and [Chapter Nineteen: Using Lightning](19_0_Using_Lightning.md).

## Why to Use this Course

Obviously, you're working through this course because you're interested in MarteXcoin. Besides imparting basic knowledge, it's also helped readers to join (or create) open-source projects and to get entry-level jobs in MarteXcoin programming.

## How to Support this Course

* Please use [Issues](https://github.com/MarteXcoin-documentation/Learning-MarteXcoin-from-the-Command-Line/issues) for any questions. Blockchain Commons does not have an active support team, and so we can't address individual problems or queries, but we will look over them in time, and use them to improve future iterations of the course.
* Please use [PRs](https://github.com/MarteXcoin-documentation/Learning-MarteXcoin-from-the-Command-Line/pulls) for any fixes of typos or incorrect (or changed) commands. For command-line or technical changes, it's very helpful if you also use the PR comments to explain why you did what you did, so that we don't have to research it.
* Please Use Our [Community discussions area](https://github.com/MarteXcoin-documentation/Learning-MarteXcoin-from-the-Command-Line/discussions) for talking about careers and skills. Blockchain Commons occasionally offers internships, as discussed in our Community repo.
* Please become a patron if you find this course helpful or if you want to help educate the next generation of blockchain programmers.

## What's Next?

If you'd like a basic introduction to MarteXcoin, public-key cryptography, ECC, blockchains, and Lightning, read the [Introducing MarteXcoin](01_1_Introducing_MarteXcoin.md) interlude.

Otherwise, if you're ready to dive into the course, go to [Setting Up a MarteXcoin-Core VPS](02_0_Setting_Up_a_MarteXcoin-Core_VPS.md).
