# arxiv_paper2slack

ArxivのオープンAPIを使って論文を探して、ChatGPTに要約してもらった文章をSlackのbotに投げてもらうコードです。

ローカルで実行して見たい人は、まず以下で必要なライブラリをインストールします。
```
$ pip install -r requirements.txt
```
その後、以下で実行してください。

```
$ python paper_arxiv.py
```

クラウドで実行したい場合は[こちらのサイト](https://gammasoft.jp/blog/schdule-running-python-script-by-serverless/)を参考にしてmain.pyとrequirements.txtを使用してください。
