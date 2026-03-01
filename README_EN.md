# Complete Guide: Google Account Purchase, Maintenance & Student Eligibility

[中文](README.md)

---

> Originally published on LINUX DO by @sauterne. Please credit the source and GitHub repo: https://github.com/dongshuyan/GoogleAccount.

This guide summarizes the complete process for purchasing, maintaining, and maximizing student eligibility for Google accounts, based on experience with over 100 accounts.

### 0. Purchase an Account

Purchase channels are not recommended here—please search on your own. After purchase, each account should be in a format similar to:

```
XXX@gmail.com|password|recovery_email|2FA|country(optional)
```

> **Important**: All following steps should be done with a clean US proxy and in a fingerprint browser environment.

### 1. Set Up Email Forwarding to Your Email

![Email Forwarding](pics/邮件转发.png)

- Check **Filters and Blocked Addresses**—ensure it is empty
- Configure email forwarding in **Forwarding and POP/IMAP**

This step is critical as a fallback recovery option.

### 2. Disable All Payment Profiles

- Visit: <https://payments.google.com/gp/w/u/1/home/settings>
- Remove all existing payment methods and payment info; disable all payment profiles
- Note: This does not affect existing student membership status

### 3. Sign Out All Other Clients and Third-Party Apps

Sign out all other clients and enable **Enhanced Safe Browsing for your account**.

![Manage Clients](pics/管理客户端.png)

### 4. Change 2FA and Password

On the same page, change 2FA first, then the password.

### 5. Create Passkey and Backup Code

On the same page, add a passkey under two-step verification, then generate and save the backup code.

### 6. Create a New Console Project

- Visit: <https://console.cloud.google.com/>
- Create a new project—required for using Gemini CLI

### 7. Change Country/Region (Both Places)

#### 7.1 First Location

- Visit: <https://policies.google.com/u/1/country-association-form?pli=1&pageId=none>
- Prefer United States

#### 7.2 Second Location

- Visit: <https://play.google.com/store/paymentmethods>
- Check if the region in the bottom-right is US; usually a US proxy will already show US region
- Reference if needed: <https://linux.do/t/topic/1287642>

### 8. Age Verification

- Visit: <https://myaccount.google.com/u/1/age-verification>
- You can verify manually or use this site for auto-verification (tested but no guarantee of availability or security): <https://age.tokawa-sakiko.xyz/>

### 9. Create AI Studio Account

- Visit: <https://aistudio.google.com/u/1/prompts/new_chat?pli=1>

### 10. Access Gemini

- Visit: <https://gemini.google.com/u/1/app?pageId=none>
- If that fails, create a gem: <https://gemini.google.com/u/1/gems/create?hl=en-US&pli=1&pageId=none>
- If still not working, add the account to a Pro family group for Gemini access

If you need to create a gem or join a Pro family group to get Gemini access, the account likely has no student eligibility. If Gemini works from the start, a clean proxy is usually enough for student eligibility.

### 11. Check Student Eligibility

- Visit: <https://one.google.com/u/1/ai-student?g1_landing_page=75&otzr=1&pageId=none>
