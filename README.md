## Technologies

This project was developed with the following technologies:

- [Node.js](https://nodejs.org)
- [SCSS](https://sass-lang.com)

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org) installed on your computer.

From your command line:

```bash
# Clone this repository

$ git clone https://github.com/joeldorosarioo/scss-boilerblate.git

$ cd cse-boilerplate

# Install dependencies

$ yarn install

# Activate hooks

$ yarn husky install
```

To transpile SCSS to CSS you must run the following command:

```bash
# On root

$ sass --watch scss/import.scss:stylesheets/import.dist.min.css --style compressed
```

## How to contribute

- Make a fork;
- Create a branck with your feature: `git checkout -b my-feature`;
- Commit changes: `git commit -m 'feat: My new feature'`;
- Make a push to your branch: `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## License

This project is under the MIT license. See the [LICENSE](/LICENSE) for details.
