<p align="center">
  <img src="https://blog.openblocks.dev/_gatsby/image/376626d2b0c5c4aa79daa5c53f49e2d4/2a22caff1b12eeed23153a33837aa41c/how-to-import-or-export-csv-excel-files-in-mysql-header.avif?u=https%3A%2F%2Fimages.ctfassets.net%2F1cnhuyin0xyv%2F4oMvT4BKvC39woUGzrZh6a%2Fec4408701ef2d2e9e273c9aa8d670a58%2Fhow-to-import-or-export-csv-excel-files-in-mysql-header.png&a=w%3D1448%26h%3D642%26fm%3Davif%26q%3D75&cd=2023-02-10T07%3A17%3A29.650Z" width="200" />
</p>

<p align="center">
  This tool is very useful, in my opinion, whether it is to introduce new users to the system,  or new products to the e-commerce system. Someday, you will meet with annoying <img src="https://m.media-amazon.com/images/W/MEDIAX_792452-T2/images/I/719IQp4yPuL._SX522_.jpg" width=35 height=35 /> CSV and Excel files that need to map the data in them and other.
<hr/>
 All you have to do is: <ul>
   <li>Connect to MySql on your project in product env or on localhost machine</li>
   <li>Give a name to the csv/Excel file that you want to upload as its required table name in MySql schema</li>
   <li>Set the location of the CSV/Excel Excel file on your machine</li>
 </ul> 
</p>
  <p align="center" style={color:'red'}>and, with fast optimization, it's will create new schema (IF NOT EXISTS) and insert the data too, as a seed file, in one GO!!</p>
  <p align="center" font-size="22px"> Amazing ! ! ! </p>

  ## About the code
  <p>If you have a sensitive eye you will notice that I applied:</p> 
    <p>- SOLID priciples in the logic layer</p>
    <p>- DAG priciple</p> 
    <p>and all with clean and readable code that every child can understand</p><img src="https://storage.googleapis.com/sticker-prod/NFYUpmqjfGbOHVAUydxk/cover.thumb256.png" width=40 height=40/>
<p align="left">Youtube:https://youtu.be/uZED_yDgtsU</p>
  [![YToube video](https://www.youtube.com/watch?v=Jwo1TUFAEsA)](https://github.com/HeloyoM/csv-transporter/assets/57059886/636137ea-7e9c-4ebe-8728-b88c13cf1817)
  
  ## Architecture - the flow of control and appling architecture principles
  ![Sys architecture](https://github.com/HeloyoM/csv-transporter/assets/57059886/018ec208-387d-4866-87db-41c072cc9fd4)

  ## Stay in touch

- Author - Meir Juli
- Linkedin -
  <p><a href="https://www.linkedin.com/in/meir-juli-a301a5197" target="_blank"><img src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Linkedin_unofficial_colored_svg-512.png" width=25 height=25 /></a> Send a connect request</p>

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```
## Technologies
```bash
# NestJs - A progressive Node.js framework for building efficient and scalable server-side applications.
# Typeorm - Object-to-Object mapping Typescript framework 
```
