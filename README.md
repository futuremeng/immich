<!--
 * @Author: be_loving@163.com 
 * @Date: 2024-12-26 12:59:31
 * @LastEditors: be_loving@163.com 
 * @LastEditTime: 2024-12-26 13:05:27
 * @FilePath: /immich/README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# 安装说明

需要docker和docker-compose

## 复制env

cp .env.example .env

## docker-compose

docker-compose up -d

## 初始化

打开 http://IP:2283 ，设置邮箱（仅用作登录名）和密码

## 必要的设置

打开 http://IP:2283/admin/system-settings?isOpen=machine-learning

1. 修改 机器学习设置的URL

http://immich-machine-learning:3003 为 http://immich_machine_learning:3003

2. 修改智能搜索CLIP模型

XLM-Roberta-Large-Vit-B-16Plus

保存
