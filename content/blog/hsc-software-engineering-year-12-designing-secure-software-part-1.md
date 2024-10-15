+++
author = "Michael Grassi"
title = "HSC Software Engineering (Year 12) - Designing Secure Software Part 2"
date = "2024-10-06"
description = "Describe how the capabilities and experience of end users influence the secure design features of software."
tags = [
    "hsc",
    "software",
    "software engineering",
    "year 12",
    "designing software",
    "secure software architecture"
]
+++

# Part 2 | Designing Secure Software | HSC Software Engineering

When designing secure software, it’s crucial to think about the people who will actually use it—the end users. Different users have different levels of technical skills, and this directly influences how we design security features. The challenge? Making security strong but still usable for everyone, from beginners to tech pros. Let's look at how user capabilities and experience impact secure software design:

### 1. User Authentication Methods

#### **Influence of User Capabilities**
- **Novice Users**: Users who aren't super tech-savvy might find complex authentication methods (like multi-factor authentication or tricky password rules) frustrating. This can lead them to bad habits, like writing passwords down or using the same simple password for everything.
- **Experienced Users**: More tech-savvy users might feel comfortable with advanced security features, like using fingerprint or face recognition, or managing passwords with a password manager.

#### **Design Considerations**
- **Simplified Authentication**: Offer simple but secure options, like **single sign-on (SSO)** or even **passwordless logins** for less tech-savvy users. For the pros, offer **multi-factor authentication (MFA)** for extra security.
- **User Education**: Help users create strong passwords by providing built-in password generators or simple guidelines. Educate users on why good password practices are so important.

### 2. Data Protection and Privacy Controls

#### **Influence of User Capabilities**
- **Novice Users**: Less experienced users might not understand how to adjust privacy settings, which can lead to accidental data exposure.
- **Experienced Users**: More advanced users usually want more control over their data and like to explore privacy settings in detail.

#### **Design Considerations**
- **Clear and Simple Privacy Settings**: Make privacy settings easy to use with clear language and explanations so that everyone can make informed choices without feeling overwhelmed.
- **Granular Control for Advanced Users**: Give tech-savvy users more options, like managing app permissions or adjusting encryption settings.

### 3. Security Warnings and Prompts

#### **Influence of User Capabilities**
- **Novice Users**: These users might ignore security warnings if they sound too technical or confusing, which can lead to risky behavior.
- **Experienced Users**: More advanced users prefer detailed warnings so they can make informed decisions about potential security risks.

#### **Design Considerations**
- **Contextual and Clear Messaging**: Keep security warnings easy to understand by using plain language for beginner users. For example, if there’s a suspicious login attempt, explain the risk clearly and offer a simple action like "Reset Password."
- **Actionable Choices**: Give users simple, clear actions they can take—like "Approve login" or "Report suspicious activity"—instead of bombarding them with confusing technical info.

### 4. Security Defaults and User Control

#### **Influence of User Capabilities**
- **Novice Users**: These users often stick with default settings, which means it's super important for those defaults to be secure.
- **Experienced Users**: Advanced users usually want to customize settings to match their specific security needs, like managing firewall settings or choosing encryption methods.

#### **Design Considerations**
- **Secure Defaults**: Set strong default settings, like enabling encryption automatically and keeping software updated. This is crucial for protecting users who aren’t likely to change default options.
- **Customizable Options for Advanced Users**: Allow experienced users to adjust security features, like configuring API keys, encryption settings, or access control lists (ACLs).

### 5. Usability vs. Security Trade-offs

#### **Influence of User Capabilities**
- **Novice Users**: Less experienced users often prioritize ease of use, which might make them want to turn off security features if they find them too complicated.
- **Experienced Users**: More advanced users are likely to understand the importance of security and tolerate minor inconveniences, like extra login steps, for better protection.

#### **Design Considerations**
- **Balancing Usability and Security**: Make sure security features aren’t too hard to use. For novice users, consider things like automatic logout after inactivity, easy password recovery, and minimal setup. Advanced users can be given more control, like configuring detailed security settings.

### 6. Ongoing Security Maintenance

#### **Influence of User Capabilities**
- **Novice Users**: These users may not realize the importance of keeping software updated, which leaves it open to vulnerabilities.
- **Experienced Users**: Advanced users usually know the value of updates and may want more control over how updates are applied.

#### **Design Considerations**
- **Automatic Updates**: For less experienced users, automatic updates are a great way to keep their software secure without them needing to do anything.
- **Update Notifications and Manual Control**: For tech-savvy users, offer manual updates with detailed info about what’s being updated, so they can assess the security changes themselves.

### Wrapping It Up
When designing secure software, it’s all about balancing **security** and **usability** based on the skills of your users. Make things easy and secure for beginners, while giving the pros the tools they need to stay in control. This way, everyone—from the least experienced user to the most advanced—can use your software confidently and safely.

Remember, a great software product keeps everyone safe, no matter their skill level!