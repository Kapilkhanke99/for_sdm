

create table Project( 
project_name varchar(100) primary key,
description varchar(200),
start_date date,
end_date date,
project_manager varchar(100)
);

create table Task (
task_name varchar(100), 
description varchar(200) ,
team_members varchar(50),
start_date date, 
end_date date
);


create table Team (
members varchar(200) ,
projects varchar(200),
Project_manager varchar(100)
);

create table Document (
documents varchar(200), 
specifications varchar(100), 
project_plans varchar(200)
);