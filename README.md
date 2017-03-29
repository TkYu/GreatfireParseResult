# GreatfireParseResult
This is a [Greatfire](https://en.greatfire.org/analyzer) clawer,
U can view code at [https://github.com/TkYu/BlocksiteList](https://github.com/TkYu/BlocksiteList)

## About
Four files:
*   [AutoProxy file](https://raw.githubusercontent.com/TkYu/GreatfireParseResult/master/greatfirelist.txt) - U can import to SwitchyOmega.
*   ['bad words' list](https://raw.githubusercontent.com/TkYu/GreatfireParseResult/master/blackwords.txt) - base64 encoded
*   [PAC file](https://raw.githubusercontent.com/TkYu/GreatfireParseResult/master/pac.pac) - pac file (proxy 127.0.0.1:1080 default)
*   [PAC file with vlink ppc](https://raw.githubusercontent.com/TkYu/GreatfireParseResult/master/vlink.pac) - see [this](https://vnet.link/project/programmer), (proxy 127.0.0.1:1080 default)

## If u r using shadowsocks-windows
1.  download pac file and rename it to 'pac.txt'
2.  open this file and replace ```PROXY 127.0.0.1:1080;``` with ```__PROXY__```
3.  put this file into your shadowsocks.exe directory (and delete/rename 'user-rule.txt')