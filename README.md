### 编译整个 src 目录下的文件并将输出合并为一个main文件。
npx babel --watch src --out-file main.js --presets react-app/prod

### 编译整个 src 目录下的文件并输出
npx babel --watch src --out-dir . --presets react-app/prod 