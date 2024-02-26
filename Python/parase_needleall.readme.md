## Code:

```
needleall -asequence classII.bacteriocins.deduplicate.fa -bsequence precusor_21_clusters.fa -outfile out.needleall.21_clusters_known_2_unknwon -auto -aformat srspair
```

Intput:

`out.needleall.21_clusters`

![image](https://github.com/ZhangDengwei/Scripts/blob/main/images/out.needleall.21_clusters.png)


- Convert
```
python /data3/zhangdw/04.Scripts/01.Python3/parase_needleall.py --inPut out.needleall.21_clusters --outPut out.needleall.21_clusters.tsv
```

Output:

`out.needleall.21_clusters.tsv`

