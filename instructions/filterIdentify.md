# Writing in the front
我们由衷的希望更多的人参与到规则维护中来


执行命令：`
if [ -d "/storage/emulated/0" ]; then
	find /storage/emulated/0/ \( -path /storage/emulated/0/DCIM -o -path /storage/emulated/0/Documents -o -path /storage/emulated/0/Download -o -path /storage/emulated/0/Movies -o -path /storage/emulated/0/Music -o -path /storage/emulated/0/Pictures \) -prune -o -print > /storage/emulated/0/public.txt
fi
 `
 
 
然后将存储根目录下的public.txt通过邮箱发给我

邮箱地址：tritium404@hotmail.com

然后我会分析其路径并尽快合并到master
## Identify

```json
{
  "Checked": false,
  "Description": "The item description",
  "App": true,
  "Name": "Tittle",
  "Notice": 3,
  "PackName": "pkgname",
  "Paths": [
    "PUBLIC_LOCATION/tencent/micromsg/",
    "PUBLIC_LOCATION/tencent/weixin/"
  ],
  "Redirect_Avoid": false,
  "Regexes": [
    "^\\/(?:.+?\\/)(?>(?:example)\\/)(?>[a-z0-9]{32}\\/)(?>files\\/)(?>.+)"
  ],
  "Size": 0
}
```

