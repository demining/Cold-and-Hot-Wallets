

<figure class="aligncenter size-large"><img decoding="async" width="1024" height="576" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/030-1024x576.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1813" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/030-1024x576.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/030-300x169.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/030-768x432.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/030.png 1280w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<p>In the last article: <a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener">“Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts”</a> we reviewed all known attacks on the blockchain, in this article we will talk about crypto threats again and we will talk about identifying <a href="https://cryptodeeptech.ru/cold-and-hot-wallets" target="_blank" rel="noreferrer noopener">vulnerabilities for Cold wallets, as well as for Hot wallets</a>. Blockchain is the underlying tech layer made up of a decentralized ledger, and a very secure data structure as there are a lot of distributed nodes that participate in the consensus algorithm. In order to hack the blockchain, hackers should exploit vulnerabilities in a lot of decentralized nodes.</p>



<p>The basic security assumption of blockchain is that it is impossible to hack so many nodes to change the state of the blockchain.</p>



<h2><strong>If blockchain tech is so secure, how could it be hacked?</strong></h2>



<p>The Achilles Heal of the technology is the centralized nature of institutional users that manage large amounts of crypto assets (money) for their clients, while the only thing that stays between the money and the hackers is the&nbsp;<em>private key</em>. The private key should be used to sign, on blockchain transactions, the same way that a manual signature could be used to sign traditional checks. If someone steals the institutions’ private key they can create a transaction on their behalf and steal the money. Unlike bank systems – once a hacked transaction is created there is no way to reverse it – the money is literally stolen.&nbsp;</p>



<h2>Why is it important to store and safeguard your private key?</h2>



<p>Whoever holds the private keys has complete control over the assets associated with that key. Because blockchain transactions are instantaneous and irrevocable, users aim to keep their private key secret. The private key is only generated once, so misplacing a private key effectively renders useless all the crypto assets associated with that address.</p>



<p>Although the optimal custody scenario has yet to be defined, it is undisputed that control of the private key is of paramount concern. In fact, the private key is, in essence, the real asset. It’s intrinsic properties and powers mean there is no way to truly safeguard it without exception.&nbsp;</p>



<p><strong>Cold wallets</strong>&nbsp;“The vault of institutional custodians” are hardware devices that store Bitcoin or other cryptocurrencies initially, internet isolated, device. In theory, the cold wallet solution is reported to be the most secure way to store cryptocurrency. Some cryptocurrency users prefer to keep their&nbsp;<a href="https://cryptodeeptech.ru/cold-and-hot-wallets/#/news-room/what-is-asset-management/">digital assets</a>&nbsp;in a physical “wallet,” most often a device that looks like a USB stick; they can only be accessed by being plugged directly into a computer and require an internet connection in order for a user to access and move their cryptocurrency funds.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="916" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/hot-vs-cold-wallet-1-1024x916.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1804" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-vs-cold-wallet-1-1024x916.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-vs-cold-wallet-1-300x268.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-vs-cold-wallet-1-768x687.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-vs-cold-wallet-1-1536x1374.png 1536w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-vs-cold-wallet-1.png 1921w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>There are several popular cold wallets for commercial use such as Trezor, Ledger Nano S and for enterprise and institutional investors some other devices use a combination of:&nbsp;</p>



<ol>
<li>USB</li>



<li>Ethernet</li>



<li>SD card</li>



<li>External thumb drives</li>



<li>Dedicated air gapped machine with HSM</li>
</ol>



<p>Problems associated with the above hardware is usability and to gain access to the crypto asset you need to connect the cold wallet to a computer and therefore it is exposed to the internet. By doing so you are compromising the cold wallet system through the Internet connection, thus exposing it to <a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener">potential attack vectors</a> and eventually potential cyber theft.&nbsp;</p>



<p>Using cold wallet storage is a necessary security precaution, especially when dealing with large amounts of Bitcoin and other crypto-assets. For example, a cryptocurrency exchange or crypto fund custodian would typically offer instant withdrawals and might be responsible for hundreds of thousands of Bitcoins and other crypto assets. To minimize the ability that hackers could steal the entire reserve in a security breach, the financial services operator would follow a standard protocol, by keeping the majority of the reserve in&nbsp;<em>cold storage</em>, while holding a smaller percentage of the assets available for day to day trade activity.&nbsp;&nbsp;</p>



<p>Essentially they would not store the majority of digital assets’ private keys on their server or any other connected computer. The only amount kept on the server is the minimum required to cover anticipated customer withdrawals.&nbsp;</p>



<p><strong>Methods used to secure private keys for digital assets:</strong></p>



<ol>
<li>Data encryption that protects wallets with a strong password</li>



<li>Backups for digital wallets in case of computer crashes or fraud</li>
</ol>



<p>Cold wallets are not truly secure as, at some point, they need to send funds and by doing so they rely on bi-directional communication and are connected to the internet. This is when they can be compromised and be infected with malicious data and <a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener">extremely vulnerable to attacks</a>. Therefore all cold wallets become hot wallets dispelling the theory of total security for institutional custodians.&nbsp;</p>



<p><strong>Hot wallets</strong>&nbsp;today have an important role as they are capable of providing easy access to funds and processing automatic transactions, however private keys of the hot wallets are stored in a method that requires that they are always connected to the internet. There are different type’s of hot wallets that take a different approach on how to store private keys. In mathematical perspective, some duplicate private keys between different participants and other divide a private key between the participant. In other words, hot wallets today tackle the security risk by distributing private keys.&nbsp;</p>



<p>The Hot wallets participants maintain control of their private keys, so the cryptocurrency assets in the hot wallet remain under the holder’s control. However, the assets remain vulnerable to hacking, as a malicious person or group which gains access to your computer or smartphone would theoretically also be able to drain your wallet via getting access to the private key.&nbsp;</p>



<p>Hot wallet’s primary advantage is that it can be used for automatic and fast access transactions. Individuals looking to actually make purchases with their cryptocurrency assets might choose to use a hot wallet, for instance, as the holdings in that wallet can be transferable across the internet and in general, the number of crypto assets is at a high enough value, therefore it is not worth the time and money that hackers would invest to steal. On the other hand, hot wallets are definitely vulnerable to security breaches as they have ongoing access to the internet.</p>



<p><strong>Different types of hot wallets all store the private keys on internet connected applications:</strong></p>



<ol>
<li>Basic Hot wallet – Direct connection of the private key on the Internet&nbsp;</li>



<li>Multisig Native Wallet – duplicates private keys – you only need to compromise two participants in order to gain access</li>



<li>Multiparty computation (MPC) – Distributes private key between 2-5 participants</li>
</ol>



<p>If we look at the Multisig method even with 2-3 people or entities having to confirm a particular transaction, hacker groups will spend millions on institutional targets and they only <a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener">require attack vectors</a> for 2 out of 3 in order to compromise the security. Hacker groups are willing to do this as they stand to gain hundreds of millions in stolen crypto assets.</p>



<p>Even the MPC methodology is vulnerable to a variety of attack vectors. With the MPC approach, multiple non-trusting computers can each conduct computation on their own unique fragments of a larger data set to collectively produce a desired common outcome without any one node knowing the details of the others’ fragments. The private key that executes the transaction is then, a collectively generated value; the proponents of MPC maintain that at no point is a single computer responsible for an actual key.&nbsp;<a href="https://cryptodeeptech.ru/cold-and-hot-wallets/#/product/">MPC based wallets</a>&nbsp;are said to be a better solution to any hardware or<a href="https://en.bitcoin.it/wiki/Multisignature">&nbsp;multisig wallets</a>&nbsp;in the market. They are mathematically proven to be safer, completely off-chain, providing higher flexibility and are generally ledger agnostic.&nbsp;</p>



<p>Unfortunately, even with the fragments on multiple devices, it is still not an entirely safe solution because sophisticated hackers might be able to linger within a cluster of machines long enough to trace and reconstruct a key. If they manage to compromise one single employee machine or server they will be able to move laterally in the network and compromise other devices which are a part of the signature method. So this can also be proved false as hacker groups are sophisticated enough to find the vulnerabilities in this method and are willing to spend millions to steal billions.&nbsp;</p>



<p>Using the above solutions could essentially prevent a rogue employee from stealing keys on-site, or from a cold-storage facility, or from any hardware device managed entirely by the company. There are mpc wallet providers that try to limit an attacker or a rogue employee from entering a single network and collecting all of the cryptographic information they would need to authorize and sign an illegal transaction, however, this solution is also not 100% secure and merely<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener"> mitigating attack vectors</a> is just not an option when billions are at stake.</p>



<h2><strong>Why should the industry care?&nbsp;</strong></h2>



<p>As of writing this article the total market cap for cryptocurrencies has exceeded $218 billion and is now in the 10th year of existence. In this past 10 years there have been many notable hacks. All institutions with custody of large amounts of crypto assets have a responsibility to their investors to ensure the most robust security options are deployed throughout their enterprise.&nbsp;</p>



<p>Furthermore, the hacks also lead to various other cyber damage</p>



<ol>
<li>Theft of assets – irreversible</li>



<li>Reputation damage</li>



<li>Theft of private customer data</li>



<li>Loss of jobs</li>



<li>Closing down the business</li>
</ol>



<p>But that’s a different article…</p>



<p>Although there is a lot of volatility in the market which in part is driven by FOMO and media hype, it is critical to acknowledge that a major factor is the security of digital assets and this can affect the value of a cryptocurrency or an exchange asset valuation fundamentally altering the entire ecosystem.&nbsp;</p>



<h3>Key Takeaways:</h3>



<ul>
<li>A hot wallet is always connected to the internet; hence it’s prone to online attacks – but it’s more convenient for daily use.</li>



<li>A cold wallet is mostly not connected to the internet; hence, it’s less prone to online attacks – but it’s less convenient for regular use.</li>



<li>When choosing a wallet, you should consider the security, convenience, fees, supported coins, and insurance factors.</li>
</ul>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p>If you are planning to buy digital assets, deciding how and where to store them is not an option, it’s a necessity. Unlike fiat currencies,&nbsp;<a href="https://www.coingecko.com/" target="_blank" rel="noreferrer noopener">cryptocurrencies</a>&nbsp;live on the&nbsp;<a href="https://www.coingecko.com/learn/what-is-a-blockchain" target="_blank" rel="noreferrer noopener">blockchain</a>&nbsp;and require a proper storage platform known as a wallet. These wallets give you access to your crypto holdings through&nbsp;<a href="https://www.coingecko.com/learn/what-are-public-and-private-keys" target="_blank" rel="noreferrer noopener">public and private keys</a>.</p>



<p>You use a public key to send and receive cryptocurrencies and a private key to confirm transactions and prove ownership of a crypto wallet. You can think of your public key as your bank account number and your private key as your pin. The main difference between hot vs. cold wallets is that the former stores private keys online while the latter stores them offline.&nbsp;&nbsp;&nbsp;</p>



<p>This article takes a deep dive into the hot and cold wallet debate, considerations when choosing a wallet, and using both hot and cold wallets to manage your crypto portfolio.&nbsp;&nbsp;</p>



<h2 id="1">What is a Hot Wallet?</h2>



<p>A hot wallet is a software wallet that stores public and private keys online. You can access it through your computer or smartphone when connected to the internet. Hot wallets are more convenient for daily use as you don’t have to plug them in and out to use them – you just need an internet connection. They are also typically free to download and use, complete with&nbsp; a user-friendly interface that makes it easy for anyone to get started.&nbsp;</p>



<p>Hot wallets are<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener"> vulnerable to attacks </a>because they store public and private keys online, which exposes you to risks like phishing and other&nbsp;<a href="https://www.coingecko.com/learn/complete-guide-to-bitcoin-scams" target="_blank" rel="noreferrer noopener">scams</a>.</p>



<h2>Types of Hot Wallets</h2>



<p>There are two types of hot wallets – exchange-based, where a user opens an account with a centralized exchange that acts as the custodian of the users’ funds in their care, and non-custodial software hot wallets.</p>



<h3 id="2">Exchange-Based Wallets</h3>



<p>Exchange-based wallets are part of a centralized exchange. Centralized exchanges are custodial institutions that hold the private keys to their users’ addresses. This means that customers of such custodial financial platforms are not in total custody of their assets, as these are deposited into hot and cold wallets held by the institution.&nbsp;</p>



<p>Unfortunately, this exposes users to the risk of the exchange engaging in certain activities that result in the loss of customers’ funds, as seen in the case of FTX in November 2022. Moving forward, there is an industry wide push for more transparency and to hold custodial institutions accountable for their customers’ tokens with the introduction of&nbsp;<a href="https://www.coingecko.com/learn/what-is-proof-of-reserves-por" target="_blank" rel="noreferrer noopener">Proof of Reserves</a>.</p>



<p>While there is an overall drop in centralized exchange activity, exchange-based wallets are still popular, especially with retail investors, as they make it easy for users to buy and sell cryptocurrency with fiat money. Also, in the event you lose your log-in details, access to your wallet can be restored by contacting the exchange’s customer service.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="673" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/Main-Table-4-1024x673.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1786" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-4-1024x673.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-4-300x197.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-4-768x504.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-4-1536x1009.png 1536w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-4.png 1600w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<h3 id="3">Non-Custodial Software Hot Wallets</h3>



<p>Non-custodial software hot wallets can be accessed through mobile, browser or desktop applications.. Most of the time, they’re available across all three. In the case of these hot wallets, users are responsible for their own private keys and have full control over their funds. While this means your funds are safe in the event of a bank run, as they’re not stored in a custodial institution, if you lose your seed phrase, you will no longer be able to access your wallet and the crypto stored within.</p>



<h4 id="4">What is&nbsp;a Seed Phrase?</h4>



<p>A seed phrase is also known as a recovery phrase. This is a random list of 12, 18, or 24 words that can be used as a master key to recover crypto assets on-chain. Seed phrases generate the private key, which in turn are used to generate the public key.&nbsp; Wallet software typically generates a seed phrase, instructing the user to write it down before storing it safely. The seed phrase acts as a master key to unlock the user’s access to their wallet, so it must be stored safely and never online.&nbsp;</p>



<p>When it comes to storing your seed phrase, don’t just write it on a piece of paper, which will fade over time or possibly be destroyed by water and fire. Instead, use crypto steel to record your seed phrase, and make multiple copies as backup.</p>



<p>Never store your seed phrase on a password manager or anywhere online or on your devices. That includes not taking a photo of it, or putting it in a google doc or note.&nbsp;</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="800" height="526" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/content_Main_Table_12.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1788" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/content_Main_Table_12.png 800w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/content_Main_Table_12-300x197.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/content_Main_Table_12-768x505.png 768w" sizes="(max-width: 800px) 100vw, 800px"></figure></div>


<h2 id="5">Examples of Hot Wallets</h2>



<h3>MetaMask – Best for Exploring the Ethereum Ecosystem&nbsp;</h3>



<p><a href="https://www.coingecko.com/learn/complete-beginners-guide-to-metamask" target="_blank" rel="noreferrer noopener">MetaMask</a>&nbsp;is one of the most popular hot wallets in the crypto space and supports all&nbsp;<a href="https://www.coingecko.com/learn/ethereum-virtual-machine-evm" target="_blank" rel="noreferrer noopener">EVM-compatible</a>&nbsp;tokens. It’s easy to use and is available on desktop and mobile devices. Besides, it has extra in-built features for swapping, sending, and receiving crypto and collecting&nbsp;<a href="https://www.coingecko.com/en/nft" target="_blank" rel="noreferrer noopener">non-fungible tokens (NFTs)</a>&nbsp;across networks.</p>



<h3>Exchange-Based Wallets – Easy Fiat On-Ramp</h3>



<p>Exchange-based hot wallets are similar to MetaMask, mostly supporting desktop and mobile devices. Exchange-based wallets connect to most banks to ensure easy onboarding, allowing new crypto users to directly buy crypto using their bank accounts instead of brokers. You may (or may not) have to open an account with the exchange to use their wallet services.&nbsp;</p>



<p>However, as mentioned above, these exchange-based wallets are custodial, which means the exchange essentially holds your private key and your coins, promising you that you’ll be able to withdraw your coins when you want to.&nbsp;</p>



<h3>Exodus – Best for Desktop</h3>



<p><a href="https://www.exodus.com/" rel="noreferrer noopener" target="_blank">Exodus</a>&nbsp;is the best hot wallet for desktops due to its high transaction speed, ease of use, and diverse client functionalities it provides. It’s one of the most visually appealing and intuitive wallets in the crypto space. It started as a desktop-only wallet but has expanded to support mobile devices. However, the Exodus desktop app for Windows, Linux, and Mac operating systems, is still the wallet’s primary offering.&nbsp;</p>



<h2 id="6">What is a Cold Wallet?&nbsp;</h2>



<p>A cold or hardware wallet is a physical device that stores your private keys offline, costing anywhere between $50 and $250. Cold wallets are the most secure type of crypto wallet, as they are not connected to the internet and are therefore unlikely to be compromised by hackers (unless they have access to your private keys AND the hardware wallet).&nbsp;</p>



<p>Hardware wallets are physical devices that may resemble a USB stick or hard drives, which work by storing your pass codes, PINs and private keys on the device itself. In fact, even if the computer is infected with malware, the cold wallet remains safe as its private keys are held in a chip that never connects to the internet. So even if your computer is hacked or your online wallet is compromised, your coins will still be safe… unless your passcode and device are stolen.&nbsp;</p>



<p>However, as cold wallets are physical objects, that also opens them up to the risk of loss through careless handling. In the unfortunate event that your crypto hardware wallet is lost or stolen, you can use your seed phrase to regenerate your private keys. So remember to keep your seed phrases safe, offline, and on hard copy.</p>



<p>As cold wallets are ideal for long-term crypto storage, they’re better suited for hodling crypto than trading funds.&nbsp;</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="673" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/Main-Table-9-1024x673.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1790" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-9-1024x673.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-9-300x197.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-9-768x504.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-9-1536x1009.png 1536w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-9.png 1600w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<h3 id="7">&nbsp;</h3>



<h3>Ledger</h3>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="800" height="229" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/content_image_265.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1792" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/content_image_265.png 800w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/content_image_265-300x86.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/content_image_265-768x220.png 768w" sizes="(max-width: 800px) 100vw, 800px"></figure></div>


<p>Source: Ledger Nano X</p>



<p><a href="https://gcko.io/ledger">Ledger</a>&nbsp;is one of the most popular crypto hardware wallet providers, offering the Ledger Nano X, Ledger Nano S and the Ledger Nano S plus wallets. These devices are about the size of a thumb drive, running on the Ledger operating system called the Blockchain Open Ledger Operating System. It also has an in-built clear OLED display screen interface, and two navigation buttons for confirming transactions.</p>



<p>Ledger comes complete with a Ledger Live mobile app and a high level of security with its secure element chip used to store cryptographic data. Their flagship model, the Ledger Nano X, offers cryptocurrency compatibility of more than 5,500 tokens.</p>



<h3>Trezor</h3>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="375" height="375" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/10712964857906.jpg" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1793" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/10712964857906.jpg 375w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/10712964857906-300x300.jpg 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/10712964857906-150x150.jpg 150w" sizes="(max-width: 375px) 100vw, 375px"></figure></div>


<p><a href="https://shop.trezor.io/product/trezor-model-t?offer_id=15&amp;aff_id=1143">Trezor</a>&nbsp;is another well-known hardware wallet that offers the Trezor One and Trezor Model T. The Trezor Model T offers compatibility with 1,456 coins and tokens, and comes with the desktop, browser and Android Trezor Suite.</p>



<p>Trezor Suite is a user interface which lets you search and buy cryptocurrencies, manage your holdings, and send crypto securely. While this improves the user experience, there is the potential to introduce security vulnerabilities as you are using internet-enabled devices.</p>



<h2 id="8">Considerations When Choosing a Wallet</h2>



<p>Depending on your needs, you may opt for a hot wallet, a cold wallet, or both. We’ve summed up how the three types of wallets covered above compare against each other in this table:</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="436" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/Main-Table-11-1024x436.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1794" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-11-1024x436.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-11-300x128.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-11-768x327.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-11-1536x654.png 1536w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Main-Table-11.png 1600w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<h3>Security</h3>



<p>Security is a core feature when choosing a crypto wallet. Blockchain technology is known for its secure and immutable nature; ensuring your wallet has the best security features is necessary. Cold wallets are more secure than hot wallets since they are not always connected to the internet with exposure to potential cybersecurity risks like phishing or other hacks and scams. Besides, ensure your wallet has two-factor authentication (2FA) functionality to prevent unauthorized access to your assets.&nbsp;</p>



<h3>Convenience&nbsp;</h3>



<p>Since cold wallets store private keys offline, they involve plugging in physical devices and linking to web-based accounts to transfer funds. On the other hand, hot wallets live online; hence they are much easier to use for everyday transactions, like day trading.&nbsp;</p>



<h3>Additional Transaction Fees</h3>



<p>You’ll be still subjected to gas fees, regardless of whichever wallet you’re using. However, exchange-based wallets may include an additional charge that is derived from gas prices, although this fee may be waived if you are holding or staking the exchange’s native token. Before downloading or purchasing any wallet, check their service charges first.&nbsp;</p>



<h3>Supported Coins</h3>



<p>The wallet you plan to use may not support the coin you want to invest in. Some wallets support only one coin! Consider&nbsp;<a href="https://wallet.mycelium.com/" rel="noreferrer noopener" target="_blank">Mycelium</a>, for instance. Despite having exceptional functionalities, it only supports Bitcoin. Therefore, be sure to check the wallet’s list of supported coins and tokensbefore using it to avoid disappointments.&nbsp;</p>



<h3>Insurance</h3>



<p>Some custodians provide asset insurance for users who incur losses through a technical problem or theft. Custodians differ in insurance policies, but selecting one that insures your assets in collaboration with a financial institution is advisable. For example, Binance provides insurance for USD deposits of up to $250,000 for U.S. customers. It has partnered with the&nbsp;<a href="https://www.fdic.gov/" rel="noreferrer noopener" target="_blank">Federal Deposit Insurance Corporation (FDIC)</a>&nbsp;to implement this policy.</p>



<h2 id="9">Using Hot and Cold Wallets to Manage Your Crypto Portfolio</h2>



<p>Hot wallets are more convenient for daily use than cold wallets. On the other hand, cold wallets guarantee maximum security than hot wallets. Both wallets support a broad range of cryptocurrencies. Therefore, the ideal wallet for you relies on whether you prioritize the safety of your funds over the convenience of using a wallet regularly.&nbsp;</p>



<p>You can enjoy both benefits by combining both methods. For instance, you can hold a small percentage of funds in a hot wallet for trading purposes and keep the rest of your funds in a cold wallet as a long-term investment.&nbsp;</p>



<p>As a blockchain network participant, o party can rely on so-called “wallets” to manage its accounts and interaction with the blockchain. A party has multiple keys.</p>



<p><strong>Problem</strong></p>



<p>A party’s wallet is vulnerable to <a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener">malicious attacks</a> leading to key theft. If compromised, an attacker can use the key to issue transactions in that party’s identity. How to prevent the compromisation of keys?</p>



<p><strong>Forces:</strong></p>



<ul>
<li>Security – A key may be hacked when being stored in a device, especially when connected to the Internet.</li>



<li>Usability – Some keys may be frequently used by blockchain participants while other keys may be used infrequently or might act as backup.</li>
</ul>



<p><strong>Solution</strong></p>



<p>Users can choose to store keys in 2 types of wallets, namely&nbsp;<em>hot wallet</em>&nbsp;and&nbsp;<em>cold wallet</em>. Hot wallet typically refers to the blockchain gateways that are connected to the Internet.</p>



<p><a href="https://i0.wp.com/research.csiro.au/blockchainpatterns/wp-content/uploads/sites/249/2020/06/hot-cold.png?ssl=1"></a></p>



<p id="caption-attachment-311">Hot and Cold Wallet Storage Pattern</p>



<p>Through a hot wallet, a user is able to directly issue transactions to the blockchain. Hence, a hot wallet typically holds frequently used keys. Cold wallet refers to key storage that is kept off-line to minimise potential attacks. Thus, a clod wallet typically contains rarely used keys. A cold wallet can be any device disconnected from the Internet or even a paper recording an entity’s keys.</p>



<p>When a key stored in the cold wallet is required to sign a transaction, the user needs to connect the cold wallet device to a computer and copy-paste the key in the relevant field. It is also possible to automate the migration of keys between the 2 wallets based on their frequency of use, e.g., least recently used and most frequently used. Also, a certain key can be marked as critical such that it primarily stays in the cold wallet. When it is required to sign a transaction it can be copied to the hot wallet. However, as soon as the transaction is signed it should be deleted from the hot wallet. In certain application settings, blockchain platforms, and wallet implementations, it is also possible to sign transactions entirely on the cold wallet and use the hot wallet to issue/relay the signed transactions to the blockchain.</p>



<p><strong>Benefits</strong></p>



<ul>
<li>Secure storage – Cold wallets are isolated from the Internet; hence, provide secure storage for keys.</li>



<li>Usability – Such a secure storage also preserves the usability of keys, as once a cold wallet is connected to the Internet (either directly or via a middleware), a party can utilise those keys.</li>
</ul>



<p><strong>Drawbacks</strong></p>



<ul>
<li>Security – Hot wallets store one’s secret keys online hence are more vulnerable to theft. A cold wallet becomes more vulnerable as soon as it is connected to the hot wallet to copy/migrate a key.</li>



<li>Usability – Cold wallets are more secure than hot wallets but less convenient to use, as the user has to connect to the cold wallet.</li>
</ul>



<p><strong>Related patterns</strong></p>



<ul>
<li>In&nbsp;<a href="https://research.csiro.au/blockchainpatterns/master-sub-key/">master and sub key generation</a>&nbsp;pattern master key can be kept in the cold wallet while sub-keys can be stored in hot wallet.</li>



<li><a href="https://research.csiro.au/blockchainpatterns/general-patterns/self-sovereign-identity-patterns/key-management-patterns/key-sharding/">Key sharding</a>&nbsp;pattern could be used in a wallet application to split and merge a key to minimise its compromise.</li>



<li>When being integrated into wallet applications, predefined delegates in&nbsp;<a href="https://research.csiro.au/blockchainpatterns/general-patterns/self-sovereign-identity-patterns/update-by-delegates/">delegate list</a>&nbsp;pattern can replace key ownership of a compromised key.</li>
</ul>



<p><strong>Known uses</strong></p>



<ul>
<li><a href="https://www.myetherwallet.com/">MyEtherWallet</a>&nbsp;is a hot wallet with a graphical interface for instant payment and withdrawal in Ethereum.</li>



<li><a href="https://trezor.io/">Trezor</a>&nbsp;is a cryptocurrency hardware wallet, designed to store and encrypt users’ coins, passwords, and other digital keys. It is a single-purpose computer with independent memory to save all private data.</li>



<li><a href="https://www.ledger.com/">Ledger</a>&nbsp;provides hardware wallet products to stores users’ private keys in a secure hardware device, protecting the cryptocurrencies.</li>
</ul>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2 id="0391">Explore the different crypto storage options</h2>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="576" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/image-72-1024x576.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1796" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-72-1024x576.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-72-300x169.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-72-768x432.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-72.png 1060w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p id="df6c"><strong>What are the pros and cons of each wallet</strong>?</p>



<p id="3fd8">A hot wallet refers to any cryptocurrency wallet connected to the internet. Generally, hot wallets are easier to set up, access, and accept more tokens. But they are also more <a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener">vulnerable to hacker attacks</a>, possible regulations, and other technical vulnerabilities.</p>



<p id="fa90">Cold Storage refers to any cryptocurrency wallet that is not connected to the internet. Overall, a cold wallet is more secure, but it doesn’t accept as many cryptocurrencies as hot wallets.</p>



<h1 id="2ad2">Should I Get a Cold Wallet?</h1>



<p id="5080">If you are going to own Bitcoin, Ethereum, or other cryptocurrencies worth more than $100, you could buy a cold wallet right now — this is how much it costs.</p>



<p id="c451">Maybe you’ve heard people say, “Bitcoin gives you this opportunity of being your own bank”? There are advantages and disadvantages to this responsibility. Generally, cryptocurrencies have fewer middleman fees, less messy banking regulations, etc. Still, it is your responsibility to ensure the safety of your assets.</p>



<p id="45fe">Overall, as a rule, you should leave as much money in your hot wallet as you would with a traditional leather wallet that you keep in your pocket. Think of it this way, if a thief was about to steal your regular wallet, you would only lose the money you have in your pocket, not the money in your bank account.</p>



<p id="45b5">In short, here’s an analogy that can help you: a hot wallet can be thought of as a pocket wallet that you walk around town with; a cold wallet is a bank deposit.</p>



<h1 id="7996">Pros &amp; Cons of Hot Wallets</h1>



<h1 id="ef48">Using a hot wallet will give you the following benefits:</h1>



<ul>
<li>By entering your pin and access number into the wallet, you quickly access your coins.</li>



<li>The investment cost is lower.</li>



<li>It has an extensive portfolio of applications or software that function as a hot wallet.</li>



<li>You need to set a PIN code or a security code to use it.</li>



<li>They allow you to connect to any platform so you can operate and trade.</li>
</ul>



<h1 id="d294">Using one of these wallets may have the following disadvantages:</h1>



<ul>
<li>Higher risk of theft as money is stored in the cloud and is more vulnerable to cyber crooks.</li>



<li>It needs to be connected to the internet all the time. Otherwise, it can’t be supported, so it could be a big problem if the internet connection fails.</li>
</ul>



<h1 id="d041">Pros &amp; Cons of Cold Wallets</h1>



<h1 id="2510">Using this wallet will give you the following benefits:</h1>



<ul>
<li>This type of wallet works without the internet, giving you a high level of security since many thefts take place on the internet.</li>



<li>A cold wallet supports ERC20 or other tokens standards, which can support an unlimited number of tokens..</li>



<li>You need to set a PIN code or a security code to use it.</li>



<li>You can take your device anywhere.</li>
</ul>



<h1 id="c4a5">Using one of these wallets may generate the following disadvantages:</h1>



<ul>
<li>There is a risk of losing your device.</li>



<li>You cannot trade with these types of devices.</li>



<li>You need to invest around $100 to get it.</li>



<li>Like any physical device, it is prone to failure, corruption, or reading problems.</li>
</ul>



<p id="a37a">Remember that if you want to trade, a hot wallet is the better option. Still, we recommend encrypting it as best you can and choosing the best software for the most significant security. On the other hand, if you are a non-trading investor and want the highest level of protection, a cold wallet will be a better choice.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p>Hot and cold wallets are both necessities for safely storing your crypto assets. When the former is used to send and receive crypto tokens, the latter securely holds your accumulating cryptocurrencies without vulnerabilities. As hot wallets require an internet connection to send and receive tokens, they are largely at risk of crypto attacks that prove to be hugely expensive. So, it cannot hold a large sum of tokens. Here is where the usage of cold wallets comes into play. Utilizing both hot and cold wallets is a safe practice in crypto vulnerability management, leaving no loopholes for attackers.</p>



<p>Let us understand the hot and cold wallet architecture and how it should be set up to mitigate the risk of vulnerabilities.</p>



<ul>
<li><a href="https://www.leewayhertz.com/hot-and-cold-wallet-architecture/#What-are-hot-wallets?">What are hot wallets?</a></li>



<li><a href="https://www.leewayhertz.com/hot-and-cold-wallet-architecture/#What-are-cold-wallets?">What are cold wallets?</a></li>



<li><a href="https://www.leewayhertz.com/hot-and-cold-wallet-architecture/#Hot-wallet-vs-Cold-Wallet-Differences">Hot wallet vs Cold Wallet: Differences</a></li>



<li><a href="https://www.leewayhertz.com/hot-and-cold-wallet-architecture/#Hot-and-cold-wallet-setupns?">Hot and cold wallet setup</a></li>



<li><a href="https://www.leewayhertz.com/hot-and-cold-wallet-architecture/#How-does-hot-and-cold-wallet-interact?">How does hot and cold wallet interact?</a></li>



<li><a href="https://www.leewayhertz.com/hot-and-cold-wallet-architecture/#How-do-hot-and-cold-wallet-setups-in-big-systems-work?">How do hot and cold wallet setups in big systems work?</a></li>
</ul>



<h2 id="What-are-hot-wallets?">What are hot wallets?</h2>



<p>Hot wallets are crypto wallets that are always connected to the internet and are more easily accessible for users than cold wallets. They can be mobile, desktop or web-based wallets, and are user-friendly and facilitate easy transfer of currencies between crypto users.</p>



<p>Private keys are kept and encrypted on the app itself in hot wallets and stored online. It has hidden vulnerabilities, and hackers can target it to break into the system. Due to its ease of use, it is the most preferred wallet for buying and trading cryptocurrencies or cashing out assets after a while.</p>



<h3><strong>How does a hot wallet storage work?</strong></h3>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="1000" height="375" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/hot-wallet-storage-work.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1798" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-wallet-storage-work.png 1000w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-wallet-storage-work-300x113.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-wallet-storage-work-768x288.png 768w" sizes="(max-width: 1000px) 100vw, 1000px"></figure></div>


<p>When you install a hot wallet storage into your computer or device, it allows you to buy, send and receive crypto assets without really holding any crypto. Rather it holds the private keys using which a user can initiate transactions. This is possible, as it interacts with the blockchain storing your assets.</p>



<p>Metamask is one of the most popular hot wallets available today. So, we will explain how a hot wallet works using Metamask.</p>



<p>Metamask is available as a web browser extension that acts as a bridge between the blockchain, especially Ethereum, and your browser. When you download and install Metamask and add it as your browser extension, you will be asked to either ‘import wallet’ or ‘create a wallet.’ Import wallet allows you to add an existing wallet by typing a secret recovery phrase, while the latter enables creating a new crypto wallet.</p>



<p>If you create a new wallet, you need to set a new Metamask password to secure the app or platform on your device. This password can be a string of characters, face recognition, or even a fingerprint that you can regularly use to access the app, instead of a secret recovery phrase.</p>



<p>Once you create a password, you must copy the secret backup phrase and paste it or write it down in a safe place. For each account you have in your Metamask wallet, you will be provided with a private key. You can unlock your cryptocurrencies using this private key.</p>



<h2 id="What-are-cold-wallets?">What are cold wallets?</h2>



<p>Cold wallets are hardware-based and exist offline. Although a cold wallet is not as convenient to use as a hot wallet, it is far more secure. Using this offline wallet keeps your keys entirely protected from online hackers. Cold wallets can be paper wallets or hardware devices.</p>



<p>A paper wallet is a traditional way of keeping private and public keys written down or printed on paper. It is a safe way to store keys as it is not prone to phishing attacks. Hardware wallets are external devices in the form of a USB or Bluetooth device that stores your keys. As they offer less liquidity, cold wallets are best for people planning to buy and hold their crypto assets for a long period.</p>



<p>To do transactions between an offline cold wallet and an online hot wallet, you need to connect the hardware device to another device with internet accessibility, mostly a computer, using a plug, then transfer the required amount from the cold wallet to the hot wallet.</p>



<h3><strong>How does a cold wallet storage work?</strong></h3>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="1000" height="375" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/hot-wallet-storage-work-1.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1800" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-wallet-storage-work-1.png 1000w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-wallet-storage-work-1-300x113.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-wallet-storage-work-1-768x288.png 768w" sizes="(max-width: 1000px) 100vw, 1000px"></figure></div>


<p>A cold wallet, on its own, cannot connect to a blockchain and complete a transaction. When a user wants to use a cold wallet for transactions, it needs to be connected to a device with an internet connection. However, this does not put your private key under security threat. Let us see how it works.</p>



<p>A cold wallet storage can be roughly divided into two components, a cold wallet core and a cold gateway. While a cold wallet core has no internet access and is completely air-gapped, a cold gateway is connected to the internet. A transaction is created in the cold gateway in a cold wallet, which is then signed in the offline cold wallet core. So, if a user wants to send x number of tokens to another wallet, the transaction will be created in the cold gateway with an internet connection, but the transaction signing will be done offline. After the transaction is signed, it is disclosed or broadcast online in the cold wallet core.</p>



<p>Let us take the example of the cold wallet ELLIPAL to understand this better. ELLIPAL is an air-gapped hardware wallet that is essentially a secure cold wallet. It is entirely isolated from the internet and is designed to prevent unauthorized access, hacks, malware and other online attacks. So, to initiate transactions, the users need to install the ELLIPAL mobile app, acting as a proxy for it to connect to the blockchain. The whole process of transactions via an ELLIPAL wallet can be summarized into the following steps:</p>



<ol>
<li>The user initiates a transaction on the app.</li>



<li>The app asks for confirmation from the cold wallet.</li>



<li>The hardware wallet signs the transaction via a private key.</li>



<li>After approval, the app completes the transaction</li>
</ol>



<h2 id="Hot-wallet-vs-Cold-Wallet-Differences">Hot wallet vs Cold Wallet: Differences</h2>



<figure class="wp-block-table"><table><thead><tr><th scope="col"></th><th scope="col"><strong>Hot Wallet</strong></th><th scope="col">Cold Wallet</th></tr></thead><tbody><tr><td><strong>Internet Connectivity</strong></td><td>Online</td><td>Offline</td></tr><tr><td><strong>Accessibility</strong></td><td>Easily accessible</td><td>Low accessibility</td></tr><tr><td><strong>Tangibility</strong></td><td>Software-based wallets; so, intangible</td><td>Physical wallets; so, tangible</td></tr><tr><td><strong>Types</strong></td><td>Mobile, web or desktop wallets</td><td>Paper or hardware wallets</td></tr><tr><td><strong>Safety</strong></td><td>Prone to hacking and attacks. So, less secure.</td><td>Less threat from hacking and attacks. So, more secure</td></tr><tr><td><strong>Convenience</strong></td><td>Easy and convenient</td><td>Less convenient</td></tr><tr><td><strong>Cost</strong></td><td>Less expensive</td><td>More expensive</td></tr><tr><td><strong>Usability</strong></td><td>Best to store a small amount of crypto</td><td>Best to store large amounts of cryptocurrency</td></tr></tbody></table></figure>



<h2 id="Hot-and-cold-wallet-setupns?">Hot and cold wallet setup</h2>



<p>Although using a hot wallet for transactions is easy and convenient, it cannot be used to keep a large number of cryptocurrencies due to security threats. It is advisable to store your large amount of cryptocurrencies in cold wallets as they are the least vulnerable to security threats, such as malware attacks and phishing.</p>



<p>One important way of setting up wallets to avoid risks is to combine both hot and cold wallets, which reduces your funds’ online exposure. In this, each wallet is set up for different purposes. The hot wallets serve as the receiving wallet and sending wallet. The receiving wallet will manage the funds coming to the exchange, while the sending wallet will be used to send cryptos for transactions and trade.</p>



<p>As both the sending and receiving wallets will be hosted on online servers, the number of funds kept in both wallets should be minimized to reduce the risks of crypto vulnerability. The rest of the cryptos should be stored in your cold wallet. Doing this can ensure that most of your asset is safe in case of any security compromises.</p>



<h2 id="How-does-hot-and-cold-wallet-interact?">How does hot and cold wallet interact?</h2>



<p>As all of the funds that are transferred to you come to your receiving wallet, there are chances of crypto accumulation in your receiving wallet, resulting in crypto vulnerabilities. So, you need to send most of it to the cold wallet and some to the sending wallet. You need to have a minimum amount in your receiving wallet to transfer to the sending wallet once it falls short of cryptos, and this ensures that the sending wallet has enough cryptos whenever needed. However, suppose funds are not reliably coming to the receiving wallet, and the sending wallet urgently needs currencies. In that case, you can transfer the required amount from the cold wallet to the sending wallet.</p>



<h2 id="Content:HotandColdWalletArchitecture-Howtomitigatecryptovulnerability?">How to mitigate crypto vulnerability?</h2>



<p>Assume that you have a total of 200 ETH in your possession, and at any time, you want to avoid risking more than 30% of your funds. Based on this calculation, you need to set maximum and minimum thresholds per wallet to reduce the severity of any malware attack. So, the receiving wallet should have a minimum of 10 ETH and a maximum of 20 ETH. Similarly, the sending wallet should possess at least 20 ETH and up to 40 ETH. The rest of your assets should be kept in the cold wallet.</p>



<p>If you set a threshold for your sending and receiving wallets, adhere to it and ensure that the set amount does not exceed or drop down the limit. Excess funds are prone to vulnerabilities, and you cannot produce the required amount when needed if it is below the limit. So, always maintain an adequate amount of funds</p>



<h2 id="How-do-hot-and-cold-wallet-setups-in-big-systems-work?">How do hot and cold wallet setups in big systems work?</h2>



<p>Hot and cold wallet setups vary, and each setup is designed based on the developer’s requirements and thought process. Through the following infographics, let us understand how hot and cold wallet setups are designed in big systems.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="696" height="1024" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/hot-and-cold-wallet-setups-in-big-systems-work-696x1024.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1802" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-and-cold-wallet-setups-in-big-systems-work-696x1024.png 696w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-and-cold-wallet-setups-in-big-systems-work-204x300.png 204w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-and-cold-wallet-setups-in-big-systems-work-768x1130.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hot-and-cold-wallet-setups-in-big-systems-work.png 1000w" sizes="(max-width: 696px) 100vw, 696px"></figure></div>


<p>In the above-given infographic, if a person wants to send x number of tokens to another user, they input a request in the front end of the application, which is fetched in the API layer or the backend of the app. The backend transfers the input request to the wallet server. In a typical wallet architecture, a wallet server handles multiple microservices like managing nodes, databases, APIs or transaction services. As the user input, in this case, is related to the transaction service, the request is sent to this microservice.</p>



<p>The transaction service then sends the request to the wallet microservices, which handle all services related to the wallet. The wallet microservices can vary from platform to platform. In the above infographic, the wallet microservices include the following:</p>



<ul>
<li><strong>Fund management for the hot wallet –&nbsp;</strong>It ensures that it always sticks to its threshold without crypto overflow or deficit to prevent risk exposure.</li>



<li><strong>Whitelisted IPs –&nbsp;</strong>It limits the number of people who can access your domain or server to a few trusted IP addresses permitted by you.</li>



<li><strong>Token –&nbsp;</strong>It manages and keeps track of your tokens, like x number of ETH or x number of SOL.</li>



<li><strong>Service monitoring –&nbsp;</strong>This microservice checks whether all services are working without glitches.</li>



<li><strong>Thresholds –&nbsp;</strong>These ensure that you have the required amount in your wallet or not to send it to others.</li>



<li><strong>2-step authentication –&nbsp;</strong>It is a security process where you have to verify your identity twice before accessing the wallet ecosystem.</li>



<li><strong>Notifications –&nbsp;</strong>It alerts users on important matters like successful transaction completion notifications.</li>



<li><strong>KMS –&nbsp;</strong>Key management system or KMS helps create, store, and manage it safely.</li>



<li><strong>Rotate hot wallet&nbsp;</strong></li>
</ul>



<p>When the transaction input is transferred from the transaction service to the wallet microservices, all of the above microservices are carried out. Once all the services are done, and it is ascertained that your hot wallet has enough number of tokens, the x number of tokens is sent to the receiver. The transaction is, then, said to be successfully completed.</p>



<h2>Conclusion</h2>



<p class="has-background" style="background-color:#f78da812">Merging both hot and cold wallets can help mitigate the risk of crypto attacks for both the users and the service providers. It acts as a comfortable middle ground by offering the benefits of both wallets, where one is used for crypto trading, and the other is used to hold the cryptos safely. Even though only hot wallets were popular during the initial days of crypto emergence, usage of cold wallets is getting more popular these days. Moreover, blending hot and cold wallets is gradually gaining prominence among crypto experts and service providers, owing to its huge benefits. Using just one wallet is, thus, outdated, and people gradually realize the advantages of combining both hot and cold wallets as an additional security measure.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p><strong><a href="https://github.com/demining/Cold-and-Hot-Wallets" target="_blank" rel="noreferrer noopener">GitHub</a></strong></p>



<p><strong><a href="https://t.me/cryptodeeptech" target="_blank" rel="noreferrer noopener">Telegram:&nbsp;https://t.me/cryptodeeptech</a></strong></p>



<p><a href="https://youtu.be/" target="_blank" rel="noreferrer noopener"><strong>Video: https://youtu.be/</strong></a></p>



<p><strong><a href="https://cryptodeeptech.ru/cold-and-hot-wallets" target="_blank" rel="noreferrer noopener">Source: https://cryptodeeptech.ru/cold-and-hot-wallets</a></strong></p>



<hr class="wp-block-separator has-alpha-channel-opacity">


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="576" src="./Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain - «CRYPTO DEEP TECH»_files/030-1-1024x576.png" alt="Cold Wallets and Hot Wallets how to find vulnerabilities and eliminate various attacks on the Blockchain" class="wp-image-1817" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/030-1-1024x576.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/030-1-300x169.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/030-1-768x432.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/030-1.png 1280w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>	</div><!-- .entry-content -->


