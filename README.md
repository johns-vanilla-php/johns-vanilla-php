# Hello there!

My name is John Stuttler.
I have been building web sites since 1998.  I began using PHP and MySQL in 2002.
I am new to using Git, so you won't yet see much of my work, but it is coming!

## Repository Naming Scheme

<table style="width: 100%; border: 0;">
  <tr>
    <td style="width: 100%;" colspan="2">
      To find repositories easier, each one will have a prefix as follows:
    </td>
  </tr>
  <tr>
    <td style="width: 10%;">
      php-
    </td>
    <td style="width: 90%;">
      PHP Examples
    </td>
  </tr>
  <tr>
    <td style="width: 10%;">
      js-
    </td>
    <td style="width: 90%;">
      JavaScript Examples
    </td>
  </tr>
  <tr>
    <td style="width: 10%;">
      css-
    </td>
    <td style="width: 90%;">
      Cascading Style Sheets
    </td>
  </tr>
  <tr>
    <td style="width: 10%;">
      bat-
    </td>
    <td style="width: 90%;">
      Windows Batch Files
    </td>
  </tr>
  <tr>
    <td style="width: 10%;">
      fork-
    </td>
    <td style="width: 90%;">
      Forked Repositories
    </td>
  </tr>
  <tr>
    <td style="width: 10%;">
      test-
    </td>
    <td style="width: 90%;">
      Testing
    </td>
  </tr>
  <tr>
    <td style="width: 10%;">
      mod-
    </td>
    <td style="width: 90%;">
      Modified from another repository
    </td>
  </tr>
  <tr>
    <td style="width: 10%;">
      ex-
    </td>
    <td style="width: 90%;">
      Examples of how I did something.
    </td>
  </tr>
</table>

## File Directory Structure

This is the typical directory structure that I use, unless otherwise noted.  Pleast note that the Root folder will vary depending on your setup:
> The GoDaddy root directory depends on your cPanel login.  For example, if your cPanel login is "x123Y456", then your root directory would be "/home/x123Y456/" and your public directory would be "/home/x123Y456/public_html/".

> If you are hosting this site locally, then your root directory would be dependent on where you installed XAMPP.  For example, if you installed XAMPP in C:\XAMPP drive, then your root directory would be "C:\XAMPP\" and your public directory would be "C:\XAMPP\htdocs\".

> Only files that are referenced are listed here.

```
Root (See notes above)
├───config
│   └───subfolder1
│   │   ├───file111.txt
│   │   ├───file112.txt
│   │   └───file113.txt
│   ├───file011.txt
│   └───file012.txt
├───cron
├───engine
├───error_logs
├───form_actions
├───init
│   ├───file021.txt
│   └───file022.txt
├───public_html (or htdocs)
│   ├───file021.txt
│   └───file022.txt
├───README.md
└───file001.txt    
```

[^1]: The root folder for a GoDaddy-hosted site is "/home/cpanel-account/" where "cpanel-account/ is your GoDaddy cPanel Login.
