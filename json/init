##  Github Actions Git提交操作示例
----
#### 主要核心代码
```
      - name: Commit files
        run: |
          git config --local user.email "action@github.com"
          git config --local user.name "GitHub Action"
          git add -A
          git commit -m "提交注释" -a
      - name: 'Push changes'
        uses: ad-m/github-push-action@master
        with:
          github_token: ${{ secrets.TOKEN }}
```

#### 注意：

需要先在项目仓库中定义 ''' TOKEN ''' 秘钥，值为可操作账户的私人令牌。 

####  本实例为采集bing图片提交到主仓库，信息来源于网络。

