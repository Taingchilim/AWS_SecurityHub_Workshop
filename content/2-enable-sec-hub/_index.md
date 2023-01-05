+++
title = "Enable Security Hub"
weight = 2
chapter = false
pre = "<b>2. </b>"
+++

#### Overview

To enable Security Hub, AWS provides users with a visual interface to interact with the service. In this step, we will enable Security Hub through this console interface.

#### Enable Security Hub via console

To enable Security Hub on a Region, follow these steps:

1. Login to **Amazon Management Console**. In the search bar, type and search for **Security Hub** service.
2. On the **AWS Security Hub** page, select **Go to Security Hub**.

![Security Hub](/images/1/2.1-1.png?width=90pc)

3. On the **Welcome to AWS Security Hub** page, select the security standards (**Security standards**) such as **AWS Foundational Security Best Practices**, **CIS AWS Foundations Benchmark**, and **PCI DSS**.
4. Select **Enable Security Hub**.

![Security Hub](/images/1/2.1-2.png?width=90pc)

5. After activation, you will need to wait a while for Security Hub to evaluate the **Security Score** of your current account against each set of security standards you set.

![Security Hub](/images/1/2.1-3.png?width=90pc)

![Security Hub](/images/1/2.1-4.png?width=90pc)

![Security Hub](/images/1/2.1-5.png?width=90pc)

{{% notice warning %}}
In some cases you will encounter a message regarding **AWS Config**, please enable the AWS Config service in the respective Region. Most of the evaluation criteria are based on the service-level rules of AWS Config. When AWS Config logging is enabled, choose to record all resources in the respective Region and global resources.
{{% /notice %}}

![Security Hub](/images/1/2.1-6.png?width=90pc)