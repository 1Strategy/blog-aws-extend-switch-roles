# Easily Switch Between Multiple AWS Accounts

## Introduction

If you use the AWS (GUI) console to manage multiple AWS accounts or IAM Roles, you may have noticed that the Account drop-down menu lists your five most recently used
(MRU) IAM Roles and lets you conveniently switch between them. The MRU account
menu works really well if you sign into a main identity account and then assume
an IAM Role in one or more resource accounts, e.g. dev, test, prod.

<img width="200" alt="AWS Switch Role Menu"
src="./img/aws-console-switch-role-menu.png">

But the AWS account drop-down menu has limitations. Besides being limited to
five Roles, there's no way to filter Roles by account. In other words, if you
have five work accounts and two personal AWS accounts and you frequently switch
between them, your work and personal Roles will be shown together in the
drop-down in the order you last accessed them. As consultants who deal with many
different customer accounts we need a better solution, and you may too.

In this post I'll show you how to use _"AWS Extend Switch Roles"_, a
[Chrome](https://chrome.google.com/webstore/detail/aws-extend-switch-roles/jpmkfafbacpgapdghgdpembnojdlgkdl)
or
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/aws-extend-switch-roles3/)
extension which extends the number of IAM Roles beyond five and lets you create
groups of related AWS accounts/Roles. For example, when you logon to your
Identity account at work, the Account drop-down menu will only show work-related
Roles, e.g. dev, test, prod; your personal accounts will not be shown.

##