# nadokarc-example

examples of nadokarc

## nadoka-ccvps.rc

`nadoka-ccvps` is IRC Server running for nadoka-san.

You can connect to the server with following server setting:

```ruby
  Servers = [
    {
      :host => 'nadoka-ccvps.n-z.jp',
      :port => 6697,
      :pass => 'nadokapass',
      :ssl_params => {
        :ca_cert => 'cacert.org.crt',
     },
    },
  ]
```

<div style="width:360px; height:80px; margin:0; padding:0;"><a href="http://www.cloudcore.jp/vps/?utm_source=ad&utm_medium=ad&utm_content=dev&utm_campaign=vps" target="_blank" rel="nofollow"><img src="http://www.cloudcore.jp/vps/develop/links/images/360x80_white.gif" alt="CloudCore" style="border:0; margin-bottom:4px;" /></a></div>
