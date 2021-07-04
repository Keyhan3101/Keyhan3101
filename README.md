create database  RegistrosBD

go 

use RegistrosBD

go 

create table Ciudad
(

    id int primary key identity (1,1),
	nombre nvarchar(60),
	activo int  default 1 not null

)

go 


create table Cliente
(

   id nvarchar(16) primary key,
   nombres nvarchar(30),
   apellidos nvarchar(30),
   ciudad int not null,
   direccion nvarchar(100)not null,
   numcelular nvarchar(60),
   fechaNac datetime not null,
   activo int default 1 not null

)


go 


insert into Ciudad(nombre) values ('Milan'), ('Nueva York'), ('Paises Bajo'), ('Stuttgar'), ('Barcelona'), ('Monaco'), ('Montevideo'), ('Lima'), ('Managua'), ('Manchester') 

go

insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('1','Sandro Tonalli', 'Ramos Castellon',1, 'Lombardia', 77850739,'31 enero, 2002')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('2','Fernando Junior', 'Tatis',1, 'Manhattan',74768901, '8 Junio, 1998')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('3','Jennifer Guadalupe','Castellon Delgado',1, 'Amsterdan', 896587, '18 junio, 2005')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('4','Laura Fernanda', 'Galdamez Gonzales',1, 'Casa Real', 48548972 , '28 Octubre, 2000')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('5','Keyhan Jesus', 'Rostran Arevalo',2, 'El lacmiel', 43521809, '3 Noviembre, 2000')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('6','Francisco Javier', 'Molina Lopez',2, 'Avenidad Bolivar',23769803, '9 febrero, 2005')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('7','Maria Jose  ', 'Davila Perez',2, 'El calvario',437998523, '31 septiembre, 2005')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('8','Paul  javier', 'Zelaya Payan',3, '1ro de mayo',23105698, '28 octubre, 2005')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('9','Ediwn Castillo', 'Lopez Aguilar',4, 'Carretera Norte',76859047,'10 mayo, 2005')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('10','Samuel Agustin', 'Paiz Solorzano',5, 'Carretera sur',67098534, '5 julio, 2005')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('11','Rigoberto Luis', 'Espadas Moreno',10, 'Calle San Juan',34789012, '12 mayo, 1990')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('12','Angel Gabriel', 'Marinez',6, 'Tercera Calle',34789012, '3 septiembre, 2012')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('13','Gabriel Hernandez', 'Cuadra Garcia',9, 'Paseo Naciones Unidas',34789012, '17 febrero, 2004')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('14','Gabriel Garcia', 'Omar Sanchez',4, 'Calle Zaragoza',34789012, '23 enero, 2001')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('15','Daniel Omar', 'Sanchez Oreol',2, 'Avenida Mártires del 1.º de Mayo',34789012, '26 mayo, 2008')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('16','Markus', 'Urbina',6, 'Kilometro 16',34789012, '8 noviembre, 2002')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('17','Alejandra Maria', 'Lopez Argueñal',6, 'Tercera Calle',34789012, '3 septiembre, 2012')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('18','Yura Rocha', 'Aguilar',7, 'Kilometro 14',34789012, '7 enero, 1990')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('19','Thelma Sanchez', 'Rios Concepcion',9, 'Pista Miguel Obando y Bravo',34789012, '11 agosto, 1991')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('20','Tupac Navarro', 'Oreol Ortiz',10, 'Bulevar de Los Mártires',34789012, '20 abril, 1999')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('21','Kevin Castillo', 'Perez',3, '12.ª Avenida',34789012, '30 septiembre, 2007')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('22','Emiliano Gallardo', 'Jose Espadas',10, 'Tercera Calle',34789012, '8 octubre, 2009')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('23','Marvin Ezequiel', 'de la Concepcion',7, '55.ª Avenida',34789012, '3 marzo, 2001')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('24','Axel Junior', 'De la Rocha',8, 'Calle centro amrica',34789012, '9 diciembre, 1988')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('25','Ruben Alejandro', ' Mojica Aguilar',2, 'Avenida Casimiro Sotelo',34789012, '14 diciembre, 2000')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('26','Giselle Astrid', 'Rivero',3, 'Avenida UNAN/Pista La UNAN',34789012, '5 julio, 2003')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('27','Mia Ocampo', 'Rivera Ortiz',9, 'Tercera Calle',34789012, '7 mayo, 2012')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('28','Erick Valverde', 'Herrera Arauz',7, 'Calle Zaragoza',34789012, '19 febrero, 2009')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('29','Emanuel Raul', 'Gracia Gomez',5, 'Tercera Calle',14569082, '5 mayo, 2008')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('30','Hansell de Jesus', 'Gomez Garcia',3, 'Tercera Calle',34789012, '7 Noviembre, 2012')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('31','Gustavo de la Cruz', 'Ramirez Argueñal ',5, 'Tercera Calle',34789012, '3 septiembre, 2012')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('32','Jose carlos', ' Marin Galan',10, 'Calle 27 de Mayo',34789012, '24  abril, 1991')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('33','Jose Areas', 'Korea Macherano',10, 'Calle Robles',34789012, '12 junio, 2005')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('34','Gareth Marin', 'Arenas Guzman',9, 'Carretera a Masaya',34789012, '20 diciembre, 1996')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('35','Diego Ruiz', 'Sanchez	Ruben',8, 'Cuarta Avenida Noroeste',34789012, '3 julio, 2003')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('36','Erick Duarte', 'Ruiz de Pinedo',7, 'Octava Calle Suroeste',34789012, '28 junio, 2002')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('37','Axel Morazan', 'Rocha de la luz',6, 'Tercera Calle',34789012, '3 septiembre, 1981')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('38','Marcos Lanuza', 'de la Encarnacion',5, 'Tercera Calle',34789012, '4 Mayo, 1995')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('39','Marcos Montalvan', 'Meza',3, 'Segunda Calle',34789012, '1 diciembre, 1982')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('40','Andres Javier', 'Marin Obrador',4, 'Primera Calle',43789012, '5 febrero, 1999')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('41','Clarence Molina', 'Roberto Aleman',5, 'Carretera a Las Nubes',78789012, '3 septiembre, 2000')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('42','Luis SanRoman', 'Ochoha',1, 'Cuarta Calle',09789012, '30 diciembre, 2004')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('43','Valentina Karina', 'Molina Rizo',1, 'Tercera Calle',12789012, '31 agosto, 2004')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('44','German', 'Martinez',9, 'Tercera Calle',34589212, '15 mayo, 1986')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('45','Pedro', 'Pascal',8, 'Tercera Calle',34789012, '14 abril, 1980')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('46','Martin obrador', 'Ruiz Espadas',7, 'Paseo Luis A. Somoza',34789012, '3 septiembre, 2012')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('47','Daniel Ruiz', 'Castellon',7, 'Paseo Luis A. Somoza',34789012, '20 septiembre, 2002')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('48','Grace Porras', 'Torres Arias',4, 'Calle Pamplona',34789012, '3 septiembre, 2012')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('49','Deborah Massiel', 'Del Rosario',1, 'Calle Robles',34789012, '5 enero, 1981')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('50','Jessica Massiel', 'Aviles Treminio',1, 'Calle Ávila',34789012, '30 septiembre, 2002')
insert into Cliente (id, nombres, apellidos,ciudad, direccion, numcelular,fechaNac) values ('51','Jessica Massiel', 'Aviles Treminio',1, 'Calle Ávila',34789012, ' 2002')

go

update Ciudad set nombre = 'La Mancha' where id = 1
update Ciudad set nombre  = 'Detroid'   where id = 2
update Ciudad set nombre  = 'Misk'   where id = 3
update Ciudad set nombre  = 'Niza'   where id = 4
update Ciudad set nombre  = 'Denver'   where id = 5

select * from Ciudad


go



delete from Cliente where id = 1
delete from Cliente where id = 34
delete from Cliente where id = 10
delete from Cliente where id = 2

go

select * from Cliente

go

select nombres  as 'Clientes',nombre from Ciudad a inner join Cliente b on a.id = b.ciudad where a.id = 1

select nombres as 'Cliente', (Year(getdate()) - Year(fechaNac)) as Edad from Cliente where (Year(getdate()) - Year(fechaNac)) > 30

select nombres, fechaNac from Cliente where Year(fechaNac) between 2000 and 2005


select nombres, apellidos  as 'Clientes',(Year(getdate()) - Year(fechaNac)) as Edad ,nombre from Ciudad a inner join Cliente b on a.id = b.ciudad where a.id = 2

select nombres + ' ' + apellidos as 'Nombre Completo', fechaNac from Cliente
