

添加egg-sequelize 多数据库源的delegate名称参数，option中添加：egg_delegate:'some_model', 即可
修复camel无效bug
## Example

    egg-sequelize-auto -o "./models" -d test -h localhost -u root -p root -x my_password -e mysql -i 'delegatemodelMysql' -C
