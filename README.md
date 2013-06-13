py-wetransfer
=============

Python script for downloading wetransfer files (https://www.wetransfer.com/) in command line mode

Usage
=====

You should have a we transfer address similar to https://www.wetransfer.com/downloads/XXXXXXXXXX/YYYYYYYYY/ZZZZZZZZ
If your link is shorter https://www.wetransfer.com/downloads/XXXXXXXXXX/YYYYYYYYY you just need to add a / between X and Y

So execute:

    python wetransfer.py -u https://www.wetransfer.com/downloads/XXXXXXXXXXXXXXXXXXXXXXXXX/YYYYYYYYYYYYYYYYYYYYYYYYYYYYYYY/ZZZZZ

And download it! :)

Requirements
=============

python

requests

    pip install requests
