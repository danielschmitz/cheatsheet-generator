# A cheatsheet generator builder

Demo: https://danielschmitz.com.br/cheatsheet-generator/

## How to works

A simple yml file:

```yml
- title: Card 1
  sub-title: Sub Title
  color: C594C5
  items:
      - title: Item 1
        sub-title: A short description
        url: http://www.google.com

      - title: Item 2
        sub-title: A short description
        url: http://www.google.com

      - title: A short description
        sub-title: 
        url: http://www.google.com

- title: Card 2
  sub-title: Sub Title
  color: F99157
  items:
      - title: Item 1
        sub-title: A short description
        url: http://www.google.com

      - title: Item 2
        sub-title: A short description
        url: http://www.google.com

      - title: A short description
        sub-title: 
        url: http://www.google.com
```

becames:

<p align="center">
<img src="https://i.imgur.com/telUVYy.png">
</p>


## Usage

- fork this project
- clone in your account
- edit `data/api.yml`
- Commit & push
- Go to project settings and enable GitHub Pages