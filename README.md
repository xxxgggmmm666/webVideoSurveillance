一、使用步骤
1、数据库初始化
  （1）、根据数据库生成模板进行对数据从进行添加（逐行添加，第一列为监控画面名称，第二列为监控画面的rtsp协议的信息）。
  （2）、运行数据库初始化.exe程序会生成Monitoring.db的文件，需要和main.exe在同一级目录。
2、软件运行
  （1）、确保Monitoring.db和main.exe在同一个目录，双击运行main.exe程序。
  （2）、检查是否运行成功。运行正确会提示（ * Serving Flask app 'main'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:8080
Press CTRL+C to quit
）
    (3)、打开浏览器访问http://127.0.0.1:8080就可以正常使用
