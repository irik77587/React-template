# React Template
### Starter template built on webpack v4
The [Guide](https://medium.com/edonec/how-to-create-a-react-app-without-create-react-app-aa0b5adba4cd) I found had some issues. I made some changes and tested it. Hope it helps. In webpack 5, webpack.config.js `contentBase` is deprecated by `static`

### Another thing to note
I tested it on node 10.19.0 and webpack@5 failed to load contentBase until I installed webpack-dev-server@3
