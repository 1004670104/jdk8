# jdk8
jdk源码导入项目后缺少tools.jar包，从lib中将tools.jar包引入项目
运行Main方法时出现Error:java: OutOfMemoryError: insufficient memory错误，修改项目配置：setting->Build，Execution,Deployment->Compiler，增大Build process head size的值为1024

