---
title: برنامه نویسی Go همراه با مثال > مقادیر
date: 2021-02-14 23:11:19
tags: golang
categories: برنامه نویسی
---
زبان برنامه نویسی Go از مقادیر مختلفی از جمله رشته ها، اعداد صحیح، اعداد اعشاری، نوعی جبری و ... پشتیبانی می کند.
در اینجا مثال هایی از این نوع داده ها را مشاهده می کنید.
{% codeblock values  lang:Go http://play.golang.org/p/YnVS3LZr8pk  line_number:false %}
package main

import "fmt"

func main() {

    fmt.Println("go" + "lang")

    fmt.Println("1+1 =", 1+1)
    fmt.Println("7.0/3.0 =", 7.0/3.0)

    fmt.Println(true && false)
    fmt.Println(true || false)
    fmt.Println(!true)
}
{% endcodeblock %}

رشته ها را می توان توسط عملگر + با هم الحاق کرد.
{% codeblock lang:Go  line_number:false %}
 fmt.Println("go" + "lang")
{% endcodeblock %}

اعداد صحیح و اعشاری
{% codeblock  lang:Go  line_number:false %}
    fmt.Println("1+1 =", 1+1)
    fmt.Println("7.0/3.0 =", 7.0/3.0)
{% endcodeblock %}
مقادیر منطقی و عملگرهایی که احتمالا از قبل با آن آشنا هستید.
{% codeblock lang:Go  line_number:false %}    fmt.Println(true && false)
    fmt.Println(true || false)
    fmt.Println(!true)
{% endcodeblock %}