# Intership-portofolio-website-development-
How to ReadMe:

Step 01: To create our internship project I have used visual studio code as a tool.


Step 02: In my main folder there are many files as been created for different programming languages.


Step 03: At first html file should be created.
•	HTML is a Hypertext markup language file format used as the basic of a web page.
•	In my html file I have created the outline for my portfolio website.
•	The html tags are used for defining headings, paragraph, lists, links, quotes and interactive forms.
•	Html can be used for embed JavaScript and CSS. 


Step 04: After creation of html file for adding styling CSS is been used. 
•	CSS is the language used to style an HTML document and it describes how HTML elements should be displayed.
•	For styling my HTML file I have created CSS file where CSS file is linked in HTML file for performing the operation.
•	In my CSS file I have a code for custom scroll bar, content styling codes, navbar styling, menu button styling, home section styling, about section styling, project section styling, skills section styling, team section styling, contact section styling, footer section styling, responsive media query start.


 
Step 05: After creation of html and CSS file I have created JavaScript for add interactivity to HTML pages.
•	JavaScript is scripting language used to add interactivity to HTML page.
•	JavaScript is an interpreted language that means the scripts execute without preliminary compilation.
•	In my js file I have a code for sticky navbar on scroll script, scroll up button show/hide script, slide up script, removing smooth scroll on slide up button, applying again smooth scroll on menu items, toggle menu/navbar script, typing text animation script, owl carousel script, 



Step 06: I have PHP file which is linked with HTML file.
•	PHP (hypertext pre-processor) is a popular general purpose scripting language that is especially suited to web development.
•	PHP is a powerful tool for making dynamic and interactive web pages.
•	In my php file I have a code for session start and error reporting. It is having query to sql for storing the database in email.
 

Step 07: For making website viewers to contact me/admin I have created SQL.
•	SQL (structured query language) is a standard database language.
•	It is used to create, maintain and retrieve the data from relational databases like MySQL, oracle etc…
•	In my website I have used phpMyAdmin SQL for storing or getting information of the viewers of my website. 

Code for SQL: [File name: sql.txt]

-- phpMyAdmin SQL Dump
-- version 4.7.9
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Generation Time: May 16, 2019 at 07:58 PM
-- Server version: 10.1.31-MariaDB
-- PHP Version: 7.2.3

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET AUTOCOMMIT = 0;
START TRANSACTION;
SET time_zone = "+00:00";

/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

Table structure for table `tblenquiry`
--
CREATE TABLE `tblenquiry` (
  `ID` int(10) NOT NULL,
  `FullName` varchar(120) DEFAULT NULL,
  `MobileNumber` bigint(10) DEFAULT NULL,
  `Email` varchar(120) DEFAULT NULL,
  `Enquiry` varchar(250) DEFAULT NULL,
  `EnquiryDate` timestamp NULL DEFAULT CURRENT_TIMESTAMP,
  `Is_Read` char(1) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `tblenquiry`
INSERT INTO `tblenquiry` (`ID`, `FullName`, `MobileNumber`, `Email`, `Enquiry`, `EnquiryDate`, `Is_Read`) VALUES
(4, 'Mahesh Shukla', 8978979797, 'Test1@gmail.com', 'vjhgjhgkhkjlkljiojnhkjhjbjhb', '2019-04-29 12:52:06', '1'),
(5, 'Mahesh Shukla', 8978979797, 'Test1@gmail.com', 'vjhgjhgkhkjlkljiojnhkjhjbjhb', '2019-04-29 12:53:08', '1'),
(8, 'Rajnikant', 77978979, 'raj@gmail.com', 'gjytrewsrdsfxchjbklopityrdxcbvnk', '2019-04-30 07:07:07', '1'),
(9, 'Renu Mishra', 7899779746, 'mishra@gmail.com', 'Tell me the cost of normal training', '2019-05-01 09:02:32', '1'),
(11, 'harish', 4564478744, 'gh@gmail.com', 'Any discounts running this time', '2019-05-01 09:05:39', '1'),
(12, 'Menu Tiwari', 9654854896, 'ti@gmail.com', 'Any discounts running this time', '2019-05-01 09:08:55', '1'),
(13, 'sfdgsdgsd', 2832376757, 'gsdgsdg@hggdhg.com', 'dskfhkdshgkhgdg', '2019-05-01 16:14:15', '1'),
(14, 'Hansika', 8899797979, 'sika@gmail.com', 'How much time will you take to teach suv', '2019-05-09 09:34:10', '1'),
(15, 'czxczx', 2342333333, 'cxzczx@jkdah.com', 'This is sample text for testing', '2019-05-16 17:09:52', '1'),
(16, 'Anuj kumar', 1234567890, 'phpgurukulofficial@gmail.com', 'This is sample text for testing', '2019-05-16 17:19:01', NULL),
(17, 'anuj', 1234567890, 'support@phpgurukul.com', 'This isa sample text for testing.', '2019-05-16 17:19:46', '1');


Step 08: For making website more interactive I have used jpg and png.
•	JPG is a digital image format which contains compressed image data.
•	JPG format contains important image details and this format is the most popular image format for sharing photos and other images on the internet and between mobile and PC users.
•	In our website we have JPG format for home page and about page.
•	PNG is a popular bitmap image format on the internet.
•	It is short for portable graphics format where it was created as an alternative of graphics interchange format (GIF).
•	In my website we have PNG for prowess page.

