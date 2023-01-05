+++
title = "Clean up resources"
date = 2021-07-07T21:33:20+07:00
weight = 4
chapter = false
pre = "<b>4. </b>"
+++

In this section, you will disable AWS Security Hub so there is no cost to your AWS account (Most of the cost of enabling Security Hub comes from AWS Config ). However, if you are deploying to production, we recommend leaving AWS Security Hub running to help you better manage account security.
#### Deactivate AWS Security Hub

1. Access to Security Hub Management Console
     - Select Settings in the left sidebar

2. In the **Settings** page on the right, select the General tab
     - Scroll to the bottom and select Disable AWS Security Hub
     - In the prompt, select Disable AWS Security Hub