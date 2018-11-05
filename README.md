# Phalcon 后台基本框架

# lat api/推广/监视资料

### 初始化

1.  git checkout 到 develop
2.  composer install
3.  phalcon指令需在 payment_php 的images 裡面執行

### 新增／建立资料表

1.  複製一份 phinx.yml.sample 在project/migration的资料夹里，并命名为phinx.yml 且更改裡面的db連線
2.  進入docker環境裡 project/application/app/migration 的资料夹
3.  在此檔案執行 ../vendor/bin/phinx migrate
