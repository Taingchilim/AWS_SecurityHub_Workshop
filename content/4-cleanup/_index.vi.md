+++
title = "Dọn dẹp tài nguyên"
date = 2021-07-07T21:33:20+07:00
weight = 4
chapter = false
pre = "<b>4. </b>"
+++

Ở phần này, bạn sẽ tắt AWS Security Hub để không phát sinh chi phí cho tài khoản AWS của bạn ( Phần lớn chi phí của việc bật Security Hub đến từ AWS Config ). Tuy nhiên, nếu bạn đang triển khai trên môi trường production, bạn nên để AWS Security Hub hoạt động để giúp bạn quản lý an ninh tài khoản tốt hơn.
#### Bỏ kích hoạt AWS Security Hub

1. Truy cập vào Security Hub Management Console
    - Chọn Settings ở thanh bên trái

2. Trong trang **Settings** ở bên phải, chọn tab General
    - Cuộn xuống dưới cùng và chọn Disable AWS Security Hub
    - Trong prompt, chọn Disable AWS Security Hub
