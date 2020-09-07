# git-wiki

## 建立 repository

#### 初始化 git 並建立新的 repository

```bash
git init
git add .
git commit -m "first commit"
git remote add origin <遠端URL>
git push -u origin master
```

## 檢視狀態

#### 13

```bash
git status
```

```bash
git log
```

## 分支操作

#### 查詢分支

```bash
git branch
```

#### 新增分支

```bash
git branch <分支名稱>
```

#### 切換分支

```bash
git checkout <分支名稱>
```

#### 合併分支

```bash
git checkout <主分支名稱>
git merge <欲合併的分支名稱>
```

## 標籤操作

#### 查詢標籤

```bash
git tag
```

#### 新增標籤

```bash
git tag <標籤名稱>
```

#### 新增有備註內容的標籤

```bash
git tag -am <備註內容> <標籤名稱>
```

#### 刪除標籤

```bash
git tag -d <標籤名稱>
```
