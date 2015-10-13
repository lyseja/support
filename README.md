support
=======

『すごいErlang ゆかいに学ぼう！』のサポートページです。

正誤表
======

p.37 サンプルコード
-------------------

誤）

```erlang
5> functions:valid_time({{2013,12,12}, {09,04,43}}).
```

正）

```erlang
5> functions:valid_time({{2019,09,06}, {09,04,43}}).
```

p.264 `simple_one_for_one` スーパバイザを使うのコマンドの返り値
---------------------------------------------------------------

誤）

```erlang
4> supervisor:terminate_child(band_supervisor, djembe).
ok
```

正）

```erlang
4> supervisor:terminate_child(band_supervisor, djembe).
{error,simple_one_for_one}
```

thanks to @K0U_CHANG and @kei_q
https://twitter.com/K0U_CHANG/status/645282762493001728

p.490 28.9の見出し
------------------

誤）

```
「EUintをCommon Test内に統合する」
```

正）

```
「EUnitをCommon Test内に統合する」
```

Thanks to @kei_q
https://twitter.com/kei_q/status/648510144431558656

p.529 文中
----------

誤）

```
「これに Dializer を走らせると、次のような出力が得られます。」
```

正）

```
「これに Dialyzer を走らせると、次のような出力が得られます。」
```
