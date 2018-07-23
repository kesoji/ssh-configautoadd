# SSH Config Auto-add

```
mv ssh-configautoadd /path/to/somewehere_in_the_$PATH/
chmod +x /path/to/somewhere_in_the_$PATH/ssh-configautoadd
echo "alias ssh=ssh-configautoadd" >> ~/.bashrc
```

## Description
~/.ssh/configに登録されてなかったら登録プロンプトを出して登録します

## TODO
* HostNameのマッチが雑なので直す
* オプションをもっと柔軟に指定できるようにする
* 補完もできるようにする
