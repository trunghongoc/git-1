# Khai niem

- repository, (repo): kho luu tru  code (nha  cung ca p: github, gitlab, ...)
- client

# command de lam viec voi git
- download code lan dau
- update code
- upload code


# thao tac voi 1 repository
Buoc 0. link den 1 repo nao do (lam 1 lan duy nhat)
git remote add origin [origin-url]

Buoc 1. khai bao se upload nhung gi len

// kiem tra trang thai code
git status

git add [options]
git add .
git add *
git add [path]

// bo cai gi do ra khoi add
git reset [options]
git reset [path]

Buoc 2. Khai bao, la minh da lam nhung gi: note: Tao header cho home page (tao 1 ghi chu)
git commit -m [message]

Buoc 3. KHi bi conflict
- download code tren repo ve may, va chon xem la noi dung nao moi la dung
git pull origin [branch_name]

giai quyet conflict (resolve conflict)
add phan vua resolve vao, sau do commit lai 1 lan nua


Buoc 4. Upload code cua minh len repo
git push origin [branch_name]

git push origin main


## cau lenh thay the cho pull
- download code moi ve
- merge code moi vao local

## fetch
- download code moi tu origin ve
git fetch origin [branch_name]
## merge
git merge [branch_A] [branch_B]

origin origin/main
local main

git merge origin/main main
git merge origin/main


git merge feature-about-page main

## Tao 1 nhanh moi
b: branch
buoc 1: di den nhanh muon lam node goc
git checkout [branch_name]

buoc 2: re nhanh moi tu nhanh dang dung
git checkout -b [branch_name]

## Tao pull request (merge request)


## Xoa 1 nhanh tren local (phai dung tren 1 nhanh khac de xoa)
git branch -d [branch_name]
git branch -D [branch_name]

