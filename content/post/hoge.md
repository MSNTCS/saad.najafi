+++
author = "Saad"
comments = false
date = "2016-01-01"
draft = false
image = ""
menu = ""
share = false
slug = "test"
title= "How to delegate"
+++

First, you need to install `ccstake`. 

```bash
yarn global add codechain-stakeholder-cli
```

After a successful installation, you can use `ccstake`  and delegate as follows:  

```bash
ccstake delegate \
    --account $YOUR_ACCOUNT
    --delegatee cccq9gqyn3xwelyegl362083a3wv20zrz2k2g5hf8jn
    --quantity $AMOUNT
    --fee $FEE
```
Thanks, you could delegate `AMOUNT` from `YOUR_ACCOUNT` to my address. 