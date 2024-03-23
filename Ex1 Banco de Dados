CREATE DATABASE exercicio;
\C exercicio
CREATE TABLE agenda(nome VARCHAR(255) NOT NULL, email VARCHAR(255), telefone VARCHAR(20) NOT NULL, grupo VARCHAR(255) NOT NULL,
\dt
INSERT INTO agenda (nome,email,telefone,grupo) VALUES (‘Ryan’,’ryan@email.com’,’111111111’,’trabalho’), (‘Rian’,’rian@email.com’,’111111112’,’escola’), 
(‘Hyan’,’hyan@email.com’,’111111113’,igreja’), 
(‘Hian’,’hian@email.com’,’111111114’,’banda’), 
(‘Gabriel’,’Gabriel@email.com’,’111111115’,’trabalho’), 
(‘Carlos’,’carlos@email.com’,’111111116’,’trabalho’), 
(‘César’,’cesar@email.com’,’111111117’,’trabalho’), 
(‘Henrique’,’henrique@email.com’,’111111118’,’faculdade’), 
(‘Lucas’,’lucas@email.com’,’111111119’,’escola’), 
(‘Paulo’,’paulo@email.com’,’111111120’,’trabalho’), 
(‘Pedro’,’pedro@email.com’,’111111121’,’banda’), 
(‘Tiago’,’tiago@email.com’,’111111122’,’trabalho’), 
(‘Gabriel’,’celoto@email.com’,’111111123’,’trabalho’), 
(‘Gabriel’,’xaolin@email.com’,’1111111124’,’igreja’), 
(‘Ademir’,’ademir@email.com’,’111111125’,’trabalho’), 
(‘Prieto’,’prieto@email.com’,’111111126’,’trabalho’), 
(‘Paulo’,’costa@email.com’,’111111127’,’banda’), 
(‘Michele’,’michele@email.com’,’111111128’,’familia’), 
(‘Marcela’,’marcela@email.com’,’111111129’,’amigo’), 
(‘Marcelo’,’marcelo@email.com’,’111111130’,’trabalho’), 
(‘Alex’,’alex@email.com’,’111111131’,’faculdade’), 
(‘João’,’jao@email.com’,’1111111132’,’escola’), 
(‘Julia’,’julia@email.com’,’111111133’,’escola’), 
(‘Cleber’,’cleber@email.com’,’1111111134’,’trabalho’), 
(‘Kleber’,’kleber@email.com’,’111111135’,’trabalho’), 
(‘Elder’,’elder@email.com’,’111111136’,’trabalho’), 
(‘Helder’,’helder@email.com’,’111111137’,’banda’), 
(‘Marcos’,’marcos@email.com’,’111111138’,’escola’), 
(‘Márcia’,’marcia@email.com’,’111111139’,’trabalho’), 
(‘Lucimara’,’lucimara@email.com’,’111111140’,’igreja’), 
(‘Luciana’,’luciana@email.com’,’111111141’,’escola’), 
(‘Fábio’,’fabio@email.com’,’111111142’,’familia’), 
(‘Flávio’,’flavio@email.com’,’111111143’,’familia’), 
(‘Flavia’,’flavia@email.com’,’111111144’,’banda’), 
(‘Bianca’,’bianca@email.com’,’111111145’,’médico’), 
(‘Mariana’,’mariana@email.com’,’111111146’,’médico’), 
(‘Marianna’,’Marianna@email.com’,’111111147’,’médico’), 
(‘Esequiel’,’esequiel@email.com’,’111111148’,’escola’), 
(‘Maria’,’maria@email.com’,’111111149’,’igreja’), 
(‘Clara’,’clara@email.com’,’111111150’,’amigo’), 
(‘Beatriz’,’beatriz@email.com’,’111111151’,’amigo’), 
(‘Ana’,’ana@email.com’,’111111152’,’igreja’), 
(‘Albert’,’Albert@email.com’,’111111153’,’banda’), 
(‘Alberto’,’alberto@email.com’,’111111154’,’familia’), 
(‘José’,’josé@email.com’,’111111155’,’banda’), 
(‘Renato’,’renato@email.com’,’111111156’,’trabalho’), 
(‘Rita’,’rita@email.com’,’111111157’,’igreja’), 
(‘Samanta’,’samanta@email.com’,’111111158’,’banda’), 
(‘Roberto’,’roberto@email.com’,’111111159’,’trabalho’), 
(‘Juliano’,’juliano@email.com’,’111111160’,’escola’); 

SELECT nome, telefone FROM agenda;
SELECT nome FROM agenda WHERE grupo=’amigo’;



UPDATE agenda SET email = ‘naruto123@email.com’ WHERE nome=’João’;
UPDATE agenda SET telefone = ‘123141231235’ WHERE nome=’Hian’;
UPDATE agenda SET grupo = ‘familia’ WHERE nome=’Beatriz’;
UPDATE agenda SET nome = ‘Sonia’ WHERE telefone=’11111112’;
UPDATE agenda SET email = ‘sonia@email.com’ WHERE telefone=’11111112’;
UPDATE agenda SET telefone = ‘9999999999’ WHERE nome=’11111157’;
UPDATE agenda SET nome = ‘Juliana’ WHERE email=’juliano@email.com’;
UPDATE agenda SET nome = ‘juliana@email.com’ WHERE nome=’Juliana’;
UPDATE agenda SET grupo = ‘banda’ WHERE nome=’Juliana’;
UPDATE agenda SET email = ‘ferreiro@email.com’ WHERE nome=’Cleber’;

DELETE FROM agenda WHERE nome=’Alberto’;
DELETE FROM agenda WHERE telefone=’11111149’;



ALTER TABLE agenda ADD favorito BOOLEAN;
