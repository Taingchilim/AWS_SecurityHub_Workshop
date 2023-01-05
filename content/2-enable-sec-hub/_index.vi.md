+++
title = "Kích hoạt Security Hub"
weight = 2
chapter = false
pre = "<b>2. </b>"
+++

#### Tổng quan

Để kích hoạt Security Hub, AWS có cung cấp cho người dùng một giao diện hình ảnh để tương tác với dịch vụ này. Ở bước này, chúng ta sẽ kích hoạt Security Hub thông qua giao diện console này.

#### Kích hoạt Security Hub thông qua console

Để kích hoạt Security Hub trên một Region, bạn hãy làm theo các bước sau đây:

1. Đăng nhập vào **Amazon Management Console**. Trên thanh tìm kiếm, nhập và tìm kiếm dịch vụ **Security Hub**.
2. Ở trang **AWS Security Hub**, chọn **Go to Security Hub**.

![Security Hub](/images/1/2.1-1.png?width=90pc)

3. Trên trang **Welcome to AWS Security Hub**, chọn các tiêu chuẩn về bảo mật (**Security standards**) như là **AWS Foundational Security Best Practices**, **CIS AWS Foundations Benchmark**, và **PCI DSS**.
4. Chọn **Enable Security Hub**.

![Security Hub](/images/1/2.1-2.png?width=90pc)

5. Sau khi kích hoạt, bạn sẽ cần chờ một khoản thời gian để Security Hub đánh giá **Security Score** của tài khoản hiện tại của bạn so với từng bộ tiêu chuẩn bảo mật mà bạn thiết lập.

![Security Hub](/images/1/2.1-3.png?width=90pc)

![Security Hub](/images/1/2.1-4.png?width=90pc)

![Security Hub](/images/1/2.1-5.png?width=90pc)

{{% notice warning %}}
Một số trường hợp bạn sẽ gặp thông báo liên quan đến về việc cấu hình **AWS Config**, hãy bật dịch vụ AWS Config tại Region tương ứng. Hầu hết các tiêu chí đánh giá dựa trên các service-level rule của AWS Config. Khi kích hoạt tính năng ghi nhận của AWS Config, hãy chọn phương án ghi nhận tất cả các tài nguyên trên Region tương ứng và các tài nguyên dạng global.
{{% /notice %}}

![Security Hub](/images/1/2.1-6.png?width=90pc)
