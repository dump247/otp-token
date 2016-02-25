A python script to generate OTP tokens.

The secret is stored in the system keyring/store. The code can be copied to the
clipboard for easy paste.

To create or update a secret:

```shell
$ otp-token somename --set totp
Enter the OTP secret:
Token: 120800
Time remaining: 25 secs
```

Generate a token:

```shell
$ otp-token somename
Token: 120800
Time remaining: 25 secs
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
