MySQL
002 MySQL Install App Setup

http://startbootstrap.com/template-overviews/freelancer/

CREATE DATABASE portfolio;

CREATE TABLE `portfolio`.`projects` ( `id` INT(11) NOT NULL AUTO_INCREMENT , `title` VARCHAR(255) NOT NULL , `description` TEXT NOT NULL , `service` VARCHAR(255) NOT NULL , `client` VARCHAR(255) NOT NULL , `image` VARCHAR(255) NOT NULL , `date` DATE NOT NULL , PRIMARY KEY (`id`) ) ENGINE = InnoDB;

INSERT INTO `portfolio`.`projects` (`id`, `title`, `description`, `service`, `client`, `image`, `date`) VALUES (NULL, 'Project1', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed volutpat tincidunt congue. Etiam vel diam pulvinar, commodo lacus vitae, ullamcorper ante. In hendrerit, lacus a mollis molestie, enim arcu pharetra arcu, sit amet lacinia metus odio ac lacus. Proin eu ligula eu mi vehicula accumsan.', 'Web Development', 'client One', '1.jpg', '2015-10-11');

INSERT INTO `portfolio`.`projects` (`id`, `title`, `description`, `service`, `client`, `image`, `date`) VALUES (NULL, 'Project Two', 'Vivamus eu tortor a enim porttitor mollis non a quam. Mauris non mi placerat magna hendrerit sollicitudin eget non ipsum. Quisque quis scelerisque dolor, sit amet dictum sem. ', 'Web Development', 'client Two', '2.jpg', '2015-10-01');


$ express
$ npm install
$ npm install --save mysql
$ npm install --save express-session
$ npm install --save express-messages
$ npm install --save connect-flash
$ npm install --save multer@0.1.8
$ npm install --save moment
$ npm install --save express-validator


$ npm start
localhost:3000
003 S3 - Frontend Project Display Part A

Covert html to Jade:
http://html2jade.aaron-powell.com/

004 S3 - Frontend Project Display Part B

$ npm start
005 Create Backend Add Projects Part A

http://getbootstrap.com/examples/starter-template/

006 Create Backend Add Projects Part B

http://localhost:3000/admin

$ npm start
007 Project Edit Delete

$ npm start