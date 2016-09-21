# getProgressBar
プログレスバーを表示するライブラリ
##環境
Python2.7.10
##Example

```Python2
import getProgressBar

if __name__=="__main__":
    data={
        "progress":6048,
		"parameter":10000
	  }
	progressBar=getProgressBar.getProgressBar(data)
	sys.stdout.write(progressBar) # [=======>    ]60.48%
	sys.stdout.flush()
```
