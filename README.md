# creat_namefile_from_number_to
可以生成一个从number1到number2之间所有域名的域名文件

用于测试需要导入域名文件的功能模块，可生成自定义序号之间的域名文件，也可以用于生成指定个数的域名文件。

代码中
  int satrtnum 变量为起始序号
	int endnum 变量为终止序号
  
  如
  int satrtnum = 1;
	int endnum = 1000;
  将会生成 1.test.com  - 1000.test.com  的域名文件，每个域名单独一行。
  
  对
  fprintf(fp, "%d" ".test.com",i);
  该行代码进行修改，即可按照自己需求生成域名，获得指定域名个数的域名文件
