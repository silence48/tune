Tune Core 
===============================

TUNE is experimental cryptocurrency for incubating and investing new cryptocurrency.
TUNE have three main features
1st : Variable Masternode Price
2nd : Profit Sharing (Weekly, Bitcoin base)
3rd : Transparent Funding Operation (All address will be opend (include BTC wallet))
And one more thing. We will announce all progress not only roadmap but also weekly plan and result.

       
Name of Coin : TUNE

Tiker : TUN

PoW Algorithem : neoscrypt

Block Time : 90 sec (960 Block per day)

Masternode Reward : 50% ( 5 per Block, From 3840 Block)

Profit Share : 30% of Weekly Income from TUNE fund will be distributed to Registered Masternode Holder

[POW Reward]
 - 1 per Block (~ 3k Block, for slow start, beta test)
 - 10 per Block (From 3k Block ~)
 - 5 per Block after Masternodes Run.
[Masternode Price]
 - 1000 TUN ( 0 ~ 10,000 Block)
 - 1500 TUN ( 10,001 ~ 20,000 Block)
 - Every 10k Block, Masternode Price will rise 500 TUN
[Premine]
 - Total 300,000 (about 30 days reward of POW)
 - 5,000 : to the dev team. masternode test and incentive
 - 5,000 : to old TUNE holders
 - 290,000 : to the TUNE fund


----------------------------------------
Restart Guide
----------------------------------------

Unfortunately, Some technical problem occured in the 1st start up.
We decided to restart the full chain from the beginning.

- If you have any old-TUNE in your wallet, take a screen-shot.
- delete your daemon, qt, tunecore folder (.tunecore in linux)
  (You can find tunecore folder at C:\Users\"your windows id"\AppData\Roaming\TuneCore)
- addnode in your tunecore/tune.conf
  addnode = tunecrypto.com
- download new wallet, or compile, and run

----------------------------------------
Compiling Guide
----------------------------------------

1) Basic environment requirements (on linux)

sudo apt-get install -y curl g++ git-core pkg-config autoconf libtool automake faketime bsdmainutils mingw-w64 g++-mingw-w64 nsis zip ca-certificates python 

you need to login by id that have authority to control /root/ directory.

2) For automatic setup (on linux)

Run compile-l.sh

3) For windows 32bit (on linux)

Run compile-w32.sh

4) For windows 64bit (on linux)

Run compile-w64.sh

