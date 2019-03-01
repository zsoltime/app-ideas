# How You Doin'?

Say hello to your visitors in their native language.

## User Stories

> TODO

## Challenges

- [ ] Return a translation of 'Good morning', 'Good afternoon', or 'Good evening', depending on the current time in the user's timezone

## API Endpoints

| Method | Route          | Get a string with the translation of the word `Hello`...                           |
| :----: | :------------- | :--------------------------------------------------------------------------------- |
|  GET   | /              | ... in the user's language, depending on their location                            |
|  GET   | /:ip           | ... in the country's official language, based on the `:ip` provided                |
|  GET   | /country/:iso2 | ... in the country's official language, based on the `:iso2` country code provided |
|  GET   | /lang/:lang    | ... in `:lang` language                                                            |
