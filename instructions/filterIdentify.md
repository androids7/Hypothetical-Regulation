# Writing in the front
我们由衷的希望更多的人参与到规则维护中来
> 执行
<
if [ -d "/storage/emulated/0" ]; then
	find /storage/emulated/0/ \( -path /storage/emulated/0/DCIM -o -path /storage/emulated/0/Documents -o -path /storage/emulated/0/Download -o -path /storage/emulated/0/Movies -o -path /storage/emulated/0/Music -o -path /storage/emulated/0/Pictures \) -prune -o -print > /storage/emulated/0/public.txt
fi
    >
