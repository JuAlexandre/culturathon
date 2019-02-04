# culturathon

Third hackathon of the Orléans Wild Code School (February 2018 session).

Develop a web application allowing an improved visit to museums.

We chose to offer different descriptions of the works according to the level of visitors (beginner, intermediate and passionate).
We also offer an audio player so that people with vision problems can also have access to culture.

## Installation

Clone the repository and move in :
```
$ git clone https://github.com/JuAlexandre/culturathon.git
$ cd culturathon
```

Install PHP and JS dependencies :
```
$ composer install
$ npm install
```

Build assets :
```
npm run dev
```

Launch the PHP sever :
```
php bin/console server:run
```

You can also use the `npm run build` command for production (minify files) or `npm run watch` to perform the transformation at each change automatically.

## Authors

* [Brice JAUGIN](https://github.com/BriceJ3D)
* [Jérôme LEGRAND](https://github.com/jeromelegrand)
* [Emilie BERGER](https://github.com/EmilieBRG)
* [Julien ALEXANDRE](https://github.com/JuAlexandre)

