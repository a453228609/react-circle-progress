react citcle progress three type
 CanCirPro SvgCirPro 支持渐变色和动画

<img width="270" height="480" src="./localhost1.gif" />
### Installation

```cmake
npm i react-circle-progress
```

### Usage

```react
import { SvgCirPro,CanCirPro,CircleProgress } from "react-circle-progress";
```


### More examples

```react
ReactDOM.render(<div>

    <CircleProgress percent={33} />

    <CanCirPro percent={88} />

    <SvgCirPro percent={100}/>

</div>, document.getElementById('root'));

```

### props

|     name      |                        content                        |
| :-----------: | :---------------------------------------------------: |
|    offset     |                        offset                         |
|    radius     |                        radius                         |
|    percent    |                        percent                        |
|  borderWidth  |                      borderWidth                      |
|  startcolor   |                      startcolor                       |
|  centercolor  |                      centercolor                      |
|   endColor    | endColor(如果不是使用渐变色，可以三个props同样颜色值) |
|   textStyle   |                       textStyle                       |
| openAnimation |                     openAnimation                     |

### qq交流群
    179916551  欢迎交流前端各种问题