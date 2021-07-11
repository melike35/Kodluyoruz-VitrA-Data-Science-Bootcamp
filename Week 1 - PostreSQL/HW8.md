<h1 align="center"> Odev8 <h1/>
  
  #### test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
~~~sql

create table employee  (
	id INT,
	name VARCHAR(50),
	email VARCHAR(50),
	birthday DATE
);
~~~  
 ####  Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
  ~~~sql
insert into employee  (id, name, email, birthday) values (1, 'Vladamir', 'vdosdell0@wsj.com', '2020-08-06');
insert into employee  (id, name, email, birthday) values (2, 'Luz', 'lwebber1@ftc.gov', '2021-04-11');
insert into employee  (id, name, email, birthday) values (3, 'Clayborne', 'cposen2@phoca.cz', '2020-09-10');
insert into employee  (id, name, email, birthday) values (4, 'Bren', 'bmcsharry3@theatlantic.com', '2021-06-09');
insert into employee  (id, name, email, birthday) values (5, 'Cull', 'cdaniello4@google.co.uk', '2021-01-30');
insert into employee  (id, name, email, birthday) values (6, 'Bob', 'bpurtell5@360.cn', '2021-06-16');
insert into employee  (id, name, email, birthday) values (7, 'Kerby', 'ktodari6@nih.gov', '2021-05-14');
insert into employee  (id, name, email, birthday) values (8, 'Geraldine', 'gdelaunde7@ifeng.com', '2021-03-12');
insert into employee  (id, name, email, birthday) values (9, 'Reg', 'rlackinton8@timesonline.co.uk', '2020-11-04');
insert into employee  (id, name, email, birthday) values (10, 'Rasla', 'rfolshom9@dedecms.com', '2020-09-19');
insert into employee  (id, name, email, birthday) values (11, 'Troy', 'tmacpharlaina@dell.com', '2020-10-14');
insert into employee  (id, name, email, birthday) values (12, 'Bryce', 'bcoronasb@ucla.edu', '2021-03-03');
insert into employee  (id, name, email, birthday) values (13, 'Coriss', 'csinottc@trellian.com', '2021-02-03');
insert into employee  (id, name, email, birthday) values (14, 'Dill', 'dkaliszewskid@sciencedirect.com', '2020-08-30');
insert into employee  (id, name, email, birthday) values (15, 'Ozzy', 'oramele@google.cn', '2020-09-18');
insert into employee  (id, name, email, birthday) values (16, 'Martainn', 'mmustillf@ustream.tv', '2020-08-03');
insert into employee  (id, name, email, birthday) values (17, 'Aviva', 'anaccig@nature.com', '2021-02-21');
insert into employee  (id, name, email, birthday) values (18, 'Ellery', 'emowbrayh@ezinearticles.com', '2020-07-17');
insert into employee  (id, name, email, birthday) values (19, 'Sandi', 'smantrupi@newyorker.com', '2021-06-18');
insert into employee  (id, name, email, birthday) values (20, 'Dawna', 'dmacalorenj@delicious.com', '2021-04-15');
insert into employee  (id, name, email, birthday) values (21, 'Harlin', 'hkerfutk@amazon.co.uk', '2021-04-06');
insert into employee  (id, name, email, birthday) values (22, 'Ophelia', 'ogwyerl@163.com', '2020-12-14');
insert into employee  (id, name, email, birthday) values (23, 'Skylar', 'swolfem@kickstarter.com', '2021-05-18');
insert into employee  (id, name, email, birthday) values (24, 'Lynnelle', 'lwhiffn@de.vu', '2021-04-19');
insert into employee  (id, name, email, birthday) values (25, 'Randell', 'rcroleyo@wired.com', '2021-04-05');
insert into employee  (id, name, email, birthday) values (26, 'Beck', 'bhastlerp@samsung.com', '2020-12-05');
insert into employee  (id, name, email, birthday) values (27, 'Almira', 'asprostonq@pagesperso-orange.fr', '2021-03-23');
insert into employee  (id, name, email, birthday) values (28, 'Teirtza', 'tsisnettr@blogs.com', '2021-03-20');
insert into employee  (id, name, email, birthday) values (29, 'Isaac', 'idyches@soup.io', '2021-06-03');
insert into employee  (id, name, email, birthday) values (30, 'Luce', 'lgoddmant@abc.net.au', '2021-06-27');
insert into employee  (id, name, email, birthday) values (31, 'Orelee', 'obeyneu@unesco.org', '2021-05-14');
insert into employee  (id, name, email, birthday) values (32, 'Vanya', 'vmoortonv@shutterfly.com', '2020-08-17');
insert into employee  (id, name, email, birthday) values (33, 'Dal', 'dsictornesw@umn.edu', '2021-01-24');
insert into employee  (id, name, email, birthday) values (34, 'Raddie', 'rparsonsonx@sun.com', '2020-08-10');
insert into employee  (id, name, email, birthday) values (35, 'Herbert', 'hwhethery@yahoo.com', '2021-06-11');
insert into employee  (id, name, email, birthday) values (36, 'Kassey', 'kdronz@wp.com', '2020-11-24');
insert into employee  (id, name, email, birthday) values (37, 'Ezekiel', 'eawton10@intel.com', '2020-10-31');
insert into employee  (id, name, email, birthday) values (38, 'Dede', 'dtodor11@yahoo.com', '2020-10-09');
insert into employee  (id, name, email, birthday) values (39, 'Gabby', 'gorviss12@oaic.gov.au', '2021-07-02');
insert into employee  (id, name, email, birthday) values (40, 'Fawn', 'flivock13@scribd.com', '2020-08-11');
insert into employee  (id, name, email, birthday) values (41, 'Jermayne', 'jwiddowes14@irs.gov', '2020-07-24');
insert into employee  (id, name, email, birthday) values (42, 'Shaun', 'sstidson15@europa.eu', '2020-12-17');
insert into employee  (id, name, email, birthday) values (43, 'Jessi', 'jwelbrock16@mozilla.org', '2020-09-01');
insert into employee  (id, name, email, birthday) values (44, 'Genna', 'ggorhardt17@salon.com', '2021-06-22');
insert into employee  (id, name, email, birthday) values (45, 'Moina', 'mcardo18@ed.gov', '2021-01-24');
insert into employee  (id, name, email, birthday) values (46, 'Hilary', 'hwickins19@princeton.edu', '2021-03-14');
insert into employee  (id, name, email, birthday) values (47, 'Orsola', 'omoutrayread1a@usa.gov', '2021-06-03');
insert into employee  (id, name, email, birthday) values (48, 'Rene', 'rcostellow1b@comcast.net', '2020-09-20');
insert into employee  (id, name, email, birthday) values (49, 'Douglass', 'dcollens1c@de.vu', '2021-03-20');
insert into employee  (id, name, email, birthday) values (50, 'Emmalyn', 'ecrawforth1d@cbsnews.com', '2021-07-05');
  
  
  ~~~
  
   #### Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
~~~sql
UPDATE employee SET name = 'Newton' WHERE name = 'Isaac';
UPDATE employee SET birthday = '1998-11-02' WHERE name LIKE 'M%';
UPDATE employee SET email = 'md@md', name = 'MD' WHERE id =2;
UPDATE employee SET name ='Gov' WHERE email LIKE '%gov';
UPDATE employee SET name ='x' WHERE name LIKE '%e%';
  ~~~
  
 #### Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
~~~sql
DELETE FROM employee WHERE name = 'x';
DELETE FROM employee WHERE email LIKE '%gov' ;
DELETE FROM employee WHERE id = '2';
DELETE FROM employee WHERE birthday = '1998-11-02';
DELETE FROM employee WHERE name = 'Bob';
  ~~~
