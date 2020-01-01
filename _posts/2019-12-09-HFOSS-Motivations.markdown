---
layout: post
title:  "H/F/OSS Motivations - bitpay"
date:   2019-12-09 11:51:00 -0500
categories: seminar bitpay
---
When working with or on open source projects, there’s is a collective, social handshake that, in theory, maintains trust for all those who are working on the project. This, in hope, should ensure that all who contribute, use and support the project work with the best interest of the collective community and not themself. While this is the hope, there are horror stories such as that of the bitpay/copay wallet which was supposed to be a secure crypto wallet. With a few short emails and messages, a rogue developer was able to ask to maintain a component and inject malicious code to siphon off coins from the wallet as reported by [Ryan Whitwam of Extreme Tech](https://www.extremetech.com/internet/281312-rogue-developer-uses-popular-open-source-project-to-steal-bitcoins). While this attack could and should be investigated further, the aim of this post is to not do that. Rather, a complement question should be asked: who’s at fault?

As we have started with this situation, why not continue with the lens of this. To begin, we can look to the bitpay/copay GitHub repository. From a brief visit, one finds that it is produced under the MIT license. In this license, there are clauses that note the exemption from any liability from the malicious action or any other use. The license states:

[THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.](https://github.com/bitpay/copay/blob/master/LICENSE)

In this relatively brief paragraph, the project is without fault for the project or those who maintain it. From an investigation, it appears the hacker who perpetrated the attack maintained anonymity. Herein lies an interesting dilemma: should someone be at fault? Is this theft? A follow-up question could simply be if it had destroyed the coins or changed the keys to the wallet, would this be perceived in the same light?

Ultimately, it seems too difficult to tell at this point but is absolutely a point for further exploration.
