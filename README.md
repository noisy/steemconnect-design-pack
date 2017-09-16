# SteemConnect Design Pack

This Design Pack is prepared to speed up integration of [SteemConnect](https://steemconnect.com/) with your project.

# 6 Different Styles

<p align="center">
  <img src="https://steemitimages.com/0x0/https://steemitimages.com/DQmZZWPnhL7qHCtHprHn9XE2a3LDes62Nfzt9M498kHUbUE/Selection_121.png" />
</p>

# Icon Font with Steem logo inside!

In this package there is also an icon font:

<p align="center">
  <img src="https://steemitimages.com/DQmcQCQbLxPRt8HpBfEEFdXt1xRL7befu72ehHhp4kJAp9a/Selection_122.png" />
</p>

thanks to that, whenever you will need scale-able steem logo, you can use a this font with couple lines of styling :)

```
<style>
    @font-face {
        font-family: 'icon-font';
        src:  url('fonts/icon-font.eot');
    }
    .icon-steem:before {
        content: "\e900";
    }
    .icon:before {
        /* color: #ff0000; */
        /* font-size: 9000px; */
    }
</style>
<span class="icon icon-steem">
    Login with SteemConnect
</span>
```

# Useful links

* SteemConnect demos:
  * https://social-auth-steemconnect-demo.krzysztofszumny.pl/
  * https://sc2-angular.herokuapp.com/
* https://github.com/noisy/python-social-auth-steemconnect
* https://github.com/noisy/python-social-auth-steemconnect-examples
