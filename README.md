# macaca-test



macaca-test


1.git clone code 


2.npm install / npm i 安装依赖


3.设置pakeage.json中dependencies
"macaca-cli": "^2.2.0",
"macaca-wd": "^3.2.1",
"macaca-chrome": "^1.1.1",

4.在pakeage.json中的scripts添加
"macaca-server" : "node_modules/macaca-cli/bin/macaca-cli-server --verbose"


二、运行test.js code

1.启动Macaca server 服务
npm run macaca server/ macaca server --verbose

2.启动chromedriver 新建终端

cd 到chromedriver所在目录，启动chromedriver.exe

3.执行测试用例testCase.test.js  切换终端  , 开始执行测试用例

mocha testCase.test.js --verbose (开始执行测试脚本)
