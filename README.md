# Facesjs-Bower

This project packages up [faces.js](https://github.com/dumbmatter/facesjs) by @dumbmatter for Bower.

## Installation

`bower install facesjs-bower`

## Usage

Everything is in the variable `faces`. Two important functions: `display` and
`generate`. Look at them first.

Each "face" is just a simple Javascript object and is declarative. Each key in
this face-hashmap is a facial feature, with the component keys and values
controlling the appearance of that facial feature.

Example of the data that comprises a "face":

```javascript
{
  "head": {
    "id": 0
  },
  "eyebrows": [
    {
      "id": 0,
      "lr": "l",
      "cx": 135,
      "cy": 250
    },
    {
      "id": 0,
      "lr": "r",
      "cx": 265,
      "cy": 250
    }
  ],
  "eyes": [
    {
      "id": 1,
      "lr": "l",
      "cx": 135,
      "cy": 280,
      "angle": 4.55309689976275
    },
    {
      "id": 1,
      "lr": "r",
      "cx": 265,
      "cy": 280,
      "angle": 4.55309689976275
    }
  ],
  "nose": {
    "id": 1,
    "lr": "l",
    "cx": 200,
    "cy": 330,
    "size": 0.623936983756721,
    "flip": true
  },
  "mouth": {
    "id": 1,
    "cx": 200,
    "cy": 400
  },
  "hair": {
    "id": 3
  },
  "fatness": 0.812903706682846,
  "color": "#f2d6cb"
}
```

Here's a jsfiddle: http://jsfiddle.net/gnarmis/at0kpcmo/.

## License

MIT License
