# Patika.dev-SQL-odev8

1.test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
CREATE TABLE employee (
id INTEGER,
name VARCHAR(50) ,
birthday DATE,
email VARCHAR(100)
);
```

2. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
insert into MOCK_DATA (name, email, Birthday) values ('Marijo', 'msline0@github.io', '2022-04-17');
insert into MOCK_DATA (name, email, Birthday) values ('Kalli', 'kmeneux1@scientificamerican.com', '2022-04-23');
insert into MOCK_DATA (name, email, Birthday) values ('Even', 'ewhitcomb2@economist.com', '2021-06-24');
insert into MOCK_DATA (name, email, Birthday) values ('Lilith', 'lbrashaw3@utexas.edu', '2022-02-22');
insert into MOCK_DATA (name, email, Birthday) values ('Berkeley', 'bducaen4@marriott.com', '2021-05-26');
insert into MOCK_DATA (name, email, Birthday) values ('Dotti', 'dstannard5@printfriendly.com', '2021-11-16');
insert into MOCK_DATA (name, email, Birthday) values ('Sauncho', 'smadigan6@sciencedirect.com', '2021-05-20');
insert into MOCK_DATA (name, email, Birthday) values ('Donetta', 'dlammerts7@state.tx.us', '2021-05-22');
insert into MOCK_DATA (name, email, Birthday) values ('Leah', 'lsemken8@about.com', '2022-04-28');
insert into MOCK_DATA (name, email, Birthday) values ('Odella', 'oedmenson9@tinypic.com', '2021-12-17');
insert into MOCK_DATA (name, email, Birthday) values ('Kinsley', 'kstedalla@ucla.edu', '2021-06-12');
insert into MOCK_DATA (name, email, Birthday) values ('Faustina', 'fcarlettb@ed.gov', '2021-08-07');
insert into MOCK_DATA (name, email, Birthday) values ('Standford', 'sbrimsonc@godaddy.com', '2022-01-02');
insert into MOCK_DATA (name, email, Birthday) values ('Tod', 'ttintond@chicagotribune.com', '2022-02-27');
insert into MOCK_DATA (name, email, Birthday) values ('Cyndia', 'cweatherelle@cafepress.com', '2022-04-25');
insert into MOCK_DATA (name, email, Birthday) values ('Rivy', 'rcubittf@abc.net.au', '2021-08-24');
insert into MOCK_DATA (name, email, Birthday) values ('Harman', 'hharping@gov.uk', '2022-02-06');
insert into MOCK_DATA (name, email, Birthday) values ('Jennifer', 'jnolinh@omniture.com', '2021-10-07');
insert into MOCK_DATA (name, email, Birthday) values ('Celine', 'cchavesi@time.com', '2022-03-28');
insert into MOCK_DATA (name, email, Birthday) values ('Dulcia', 'dlooselyj@upenn.edu', '2021-06-04');
insert into MOCK_DATA (name, email, Birthday) values ('Riley', 'rmcphelimyk@sphinn.com', '2021-11-14');
insert into MOCK_DATA (name, email, Birthday) values ('Harwilll', 'hlonginal@businessweek.com', '2021-12-25');
insert into MOCK_DATA (name, email, Birthday) values ('Selle', 'slooneym@chronoengine.com', '2021-07-30');
insert into MOCK_DATA (name, email, Birthday) values ('Forrest', 'ftrembeyn@zdnet.com', '2021-10-24');
insert into MOCK_DATA (name, email, Birthday) values ('Thibaud', 'tfreegardo@loc.gov', '2022-03-09');
insert into MOCK_DATA (name, email, Birthday) values ('Georgine', 'graddenp@nifty.com', '2022-03-16');
insert into MOCK_DATA (name, email, Birthday) values ('Perry', 'pprovostq@cdbaby.com', '2022-03-07');
insert into MOCK_DATA (name, email, Birthday) values ('David', 'dwiffenr@hc360.com', '2022-02-16');
insert into MOCK_DATA (name, email, Birthday) values ('Eleonora', 'etalbots@yellowbook.com', '2021-06-30');
insert into MOCK_DATA (name, email, Birthday) values ('Laurella', 'lemburyt@1688.com', '2021-11-01');
insert into MOCK_DATA (name, email, Birthday) values ('Fin', 'fffrenchu@spiegel.de', '2021-08-25');
insert into MOCK_DATA (name, email, Birthday) values ('Alla', 'ameddingsv@indiatimes.com', '2021-08-30');
insert into MOCK_DATA (name, email, Birthday) values ('Davis', 'djupew@squarespace.com', '2021-10-01');
insert into MOCK_DATA (name, email, Birthday) values ('Ann-marie', 'acouldwellx@wordpress.org', '2021-05-25');
insert into MOCK_DATA (name, email, Birthday) values ('Penni', 'pszymczyky@xinhuanet.com', '2022-02-04');
insert into MOCK_DATA (name, email, Birthday) values ('Sharron', 'shawkeyz@geocities.jp', '2021-06-09');
insert into MOCK_DATA (name, email, Birthday) values ('Hurlee', 'hthorndycraft10@deviantart.com', '2021-08-17');
insert into MOCK_DATA (name, email, Birthday) values ('Berri', 'bsambiedge11@chronoengine.com', '2021-05-26');
insert into MOCK_DATA (name, email, Birthday) values ('Base', 'bneiland12@cdc.gov', '2021-06-17');
insert into MOCK_DATA (name, email, Birthday) values ('Malena', 'mferreiro13@fda.gov', '2022-03-08');
insert into MOCK_DATA (name, email, Birthday) values ('Thatch', 'trockall14@comsenz.com', '2022-04-01');
insert into MOCK_DATA (name, email, Birthday) values ('Kelci', 'kwhewill15@vinaora.com', '2021-11-18');
insert into MOCK_DATA (name, email, Birthday) values ('Marleen', 'mdesson16@diigo.com', '2022-01-29');
insert into MOCK_DATA (name, email, Birthday) values ('Marilyn', 'mtylor17@latimes.com', '2022-04-11');
insert into MOCK_DATA (name, email, Birthday) values ('Corny', 'cjudron18@springer.com', '2021-06-14');
insert into MOCK_DATA (name, email, Birthday) values ('Barclay', 'bhawtin19@msn.com', '2021-06-29');
insert into MOCK_DATA (name, email, Birthday) values ('Thaddus', 'tsyalvester1a@blog.com', '2022-03-28');
insert into MOCK_DATA (name, email, Birthday) values ('Paten', 'pfeaveryear1b@myspace.com', '2021-05-23');
insert into MOCK_DATA (name, email, Birthday) values ('Bradley', 'bbrunroth1c@nymag.com', '2021-09-04');
insert into MOCK_DATA (name, email, Birthday) values ('Gabie', 'gperes1d@nationalgeographic.com', '2021-09-20');
```
3. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
UPDATE employee
		 SET name = 'Albert ' ,
		 email ='alberto3567@gmail.com' ,
		 birthday ='1995-03-23'
		 WHERE id = 1 ;

UPDATE employee
		 SET name = 'Gaben' ,
		 email ='gaben21@gmail.com' ,
		 birthday ='1978-02-06'
		 WHERE id = 2 ;
UPDATE employee
		 SET name = 'Hari Seldon  ' ,
		 email ='h.seldon@gmail.com' ,
		 birthday ='1971-02-01'
		 WHERE id = 3 ;
UPDATE employee
		 SET name = 'MİKE ' ,
		 email ='mike@gmail.com' ,
		 birthday ='2000-03-05'
		 WHERE id = 4 ;
UPDATE employee
		 SET name = 'Oscar ' ,
		 email ='oscar22@gmail.com' ,
		 birthday ='1994-02-24'
		 WHERE id = 5 ;

```
4.
Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee
		WHERE id IN (1,2,3,4,5)
		RETURNING *;
```
