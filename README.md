# Acme Explosives

## Setup

These commands are a helpful quick start. You may choose to ignore them completely and create your own directory structure. If you choose to use this recommendation, just copy the commands below and paste. It doesn't matter what directory you are currently in.

```bash
mkdir -p ~/workspace/exercises/mjd/acme-explosives && cd $_
```

## Requirements

You are going to be creating several JSON files that will be describing all of the explosive products that you sell. You need to use Promises to handle the order of the asynchronous operations needed to load the data.

### Product Categories

Choose at least two, but as many of you like, categories for your products. Give each one an integer unique id.

Here's an example.

##### categories.json

```js
{
    "categories": [
        {
            "id": 0,
            "name": "Fireworks"
        },
        {
            "id": 1,
            "name": "Demolition"
        }
    ]
}
```
