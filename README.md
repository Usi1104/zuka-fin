# zuka-fin

```mermaid
flowchart TD
a["a<-[男性社員の平均賃金]"]
b["b<-[女性社員の平均賃金]"]
c["c<-[男性社員の人数]"]
d["d<-[女性社員の人数]"]

a-->b-->c-->d
d-->e["a*c"]
e-->f["b*d"]
f-->g["d+e"]
g-->h["g/c+d"]
h-->i["g<--[四捨五入]"]
i-->gool["全体の平均賃金"]
