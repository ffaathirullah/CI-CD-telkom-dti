react native : lebiih ke native bukan webview, webview ada celah

github : u/clone source code  
gitlab : sudah ada ci/cd, open source
bitbukets : limitasi untuk meng-invite member 

kalau windows memakai gitbash

origin : nama remote
ssh : u/advancenya , agar tidak mengetik username/password lagi

git config --global user.name "Your Name"
git config --global user.email "Email"
git init
git remote add origin
git remote -v
git status : masuk untrack : belum ada historynya
git add. : memasukan value pada status , .= memasukan semua
git commit -m "nama commit", untuk checkup commitan jika waktu realease aplikasi ada yang error
git push -u origin main
git pull origin master : untuk mengupdate
git tags : nandain/kasih label di commit versi stable /dll

developer 2
git clone -b : untuk branchnya
nano readme.md : readme : dokumen yang simple , biasanya berkaitan dengan dokumentasi / cara menjalakan aplikasinya
git status
git add readme.md
git commit -m "nama commit"
git push -u origin main

tags : alternatif deploy kita

travis (3)
travis-ci.com : pihak ketiga , proses build dan proses deploy, banyak bahasa (membaca reponya, lalu deploy apk)
cari file name .travis.yml
ada: menjalankan travis , tida ada : diam
isi travis.yml : 
-config : sdk
-jobs : build, deploy hit/push ke tags
tambah personal access token untuk ditambah ke setting value travisnya

keystore (4)
untuk update di playstores, kalau hilang harus delete
branch : bisa diupdate , branch misal untuk membedakan production atau developmen (masih pengembangan)
tags : tidak bisa diupdate

build : ./gradlew assesmblerelease
