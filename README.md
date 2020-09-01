# Compare material-ui vs ant design vs tailwindcss

Compare material-ui vs ant design vs tailwindcss in a react app with CRA

![material-ui button](https://github.com/mberneti/material-ui-ant-design-tailwindcss/blob/master/images/material-ui-button.PNG?raw=true)
## material-ui
Builded file sizes after gzip

  | size     | file                                     |
  | -------- | ---------------------------------------- |
  | 62.14 KB | build\static\js\2.821814f2.chunk.js      |
  | 784 B    | build\static\js\runtime-main.cbc14a35.js |
  | 530 B    | build\static\js\main.3ec4d24c.chunk.js   |
  | 304 B    | build\static\css\main.de44605d.chunk.css |

![ant design button](https://github.com/mberneti/material-ui-ant-design-tailwindcss/blob/master/images/ant-design-button.PNG?raw=true)
## ant design
Builded file sizes after gzip

  | size     | file                                     |
  | -------- | ---------------------------------------- |
  | 64.22 KB | build\static\css\2.d4e7eff5.chunk.css    |
  | 63.71 KB | build\static\js\2.a4e2ff05.chunk.js      |
  | 848 B    | build\static\js\runtime-main.b3febbbe.js |
  | 528 B    | build\static\js\main.25f39053.chunk.js   |
  | 303 B    | build\static\css\main.d9b5e89a.chunk.css |


![tailwindcss button](https://github.com/mberneti/material-ui-ant-design-tailwindcss/blob/master/images/tailwindcss-button.PNG?raw=true)
## tailwindcss
Builded file sizes after gzip

  | size     | file                                     |
  | -------- | ---------------------------------------- |
  | 41.55 KB | build\static\js\2.5aa3c038.chunk.js      |
  | 1.83 KB  | build\static\css\main.e89c07d1.chunk.css |
  | 848 B    | build\static\js\runtime-main.e78c30e6.js |
  | 552 B    | build\static\js\main.1f8bd29a.chunk.js   |

## Runtime performance by Google Chrome DevTools

  | size      | material-ui | and design | tailwindcss |
  | --------- | ----------- | ---------- | ----------- |
  | Loading   | 3 ms        | 18 ms      | 3 ms        |
  | Scripting | 49 ms       | 35 ms      | 18 ms       |
  | Rendering | 2 ms        | 6 ms       | 2 ms        |
  
## Lighthouse statistics

  | metric                   | material-ui | ant design | tailwindcss |
  | ------------------------ | ----------- | ---------- | ----------- |
  | First Contentful Paint   | 0.4 s       | 0.5 s      | 0.4 s       |
  | Largest Contentful Paint | 0.4 s       | 0.5 s      | 0.4 s       |
  | Time to Interactive      | 0.4 s       | 0.5 s      | 0.4 s       |
