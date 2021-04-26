# ex01_vagrant_mysql

*Infrastructure and Cloud Computing - MBA ES21*

>Desafio:
>>Subir uma máquina virtual, usando Vagrant, com MySQL instalado e que esteja acessível no host da máquina na porta 3306.
>>

> #### Tecnologias utilizadas:
>
> - Vagrant
> - Virtual Box
> - Ubuntu
> - Mysql
>
>#### User: **root**
>#### Password: **root**
>  *Execução/Teste* 
>>**$mysql -u root -p**
>>  
>>$CREATE DATABASE dbdesafio;
>>
>>$USE dbdesafio;
>>
>>$CREATE TABLE primeira ( id smallint unsigned not null auto_increment, name varchar(20) not null, constraint pk_primeira primary key (id) );
>>
>>$INSERT INTO primeira ( id, name ) VALUES ( null, 'Sample data' );
>>$SELECT * FROM primeira;
>>
