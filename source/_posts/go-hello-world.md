---
title: برنامه نویسی Go همراه با مثال > Hello World
date: 2021-02-13 23:56:03
tags: golang
categories: برنامه نویسی
---
برای شروع قصد داریم پروژه چاپ سلام دنیای معروف رو با  زبان برنامه نویسی Go پیاده سازی  کنیم.
متن کامل برنامه را اینجا می تونید مشاهده کنید:
{% codeblock hello-world.go lang:Go https://play.golang.org/p/NeviD0awXjt  line_number:false %}
package main
import "fmt"
func main() {
    fmt.Println("hello world")
}
{% endcodeblock %}
برای اجرای برنامه  کافیه که کد برنامه  رو داخل فایل hello-world.go ذخیره کنید و از طریق خط فرمان مطئمن شوید که در مسیر مورد نظر قرار دارید و سپس با استفاده از دستور زیر برنامه را اجرا می کنیم .
``` bash
$ go run hello-world.go
hello world
```
گاهی لازمه که به جای اجرای مستقیم برنامه یه خروجی باینری از برنامه داشته باشیم و بعد اقدام به اجرای برنامه کنیم .برای این کار می تونیم از دستور build به شکل زیر استفاده کنیم .

``` bash
$ go build hello-world.go
$ ls
hello-world    hello-world.go
```
حالا می تونیم به صورت مستقیم برنامه رو اجرا کنیم .
	
``` bash
$ ./hello-world
hello world
```
حالا که یاد گرفتیم یه برنامه پایه Go  رو ایجاد و اجرا کنیم بهتره بریم که سایر ویژگی های این زبان رو با هم یاد بگیریم.