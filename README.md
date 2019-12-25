# MERN stack boilerplate

A boilerplate for building web app with the MERN stack.

## Installation

Use the npm package manager to install node modules.

```bash
npm install # installs backend node modules
cd client # switch to frontend client directory
npm install # installs frontend node modules
cd .. # switch to project root directory
```

## Add configurations

Add two `.json` configuration files in the `config` directory, and save them `default.json` as and `production.json`

The configuration files should contain the following:

```bash
{
  "mongoURI": #Your MongoDB connection URI wrapped in double-quotes
  "jwtSecret": #Any string as your JSON web token secret
}
```

## Usage

In the project root directory, run this command:

```bash
npm run dev
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
