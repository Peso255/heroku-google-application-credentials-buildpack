# pennywise-buildpack
Generates critical config files for `pennywise` on Heroku using config vars, since the config files are left out of the GitHub repo it's pulling from.

## Usage

- Set config var `GOOGLE_CREDENTIALS` as the contents of `google-credentials.json`.
- Set config var `APP_CONFIG` as the contents of `config.js`.
- Both files will be generated into the filesystem by the script upon deployment on Heroku. Easy peasy, lemon squeezy.
