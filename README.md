A python script to generate OTP tokens.

The secret is stored in the system keyring/store. The generated OTP code can be copied
automatically to the clipboard for easy paste.

To create or update a secret:

```shell
$ otp-token somename --set totp
Enter the OTP secret:
120800
```

Generate a token:

```shell
$ otp-token somename
120800
```

Generate a token and copy to clipboard:

```shell
$ otp-token somename --copy
Time remaining: 25 secs
```

Delete a secret:

```shell
$ otp-token somename --delete
```
