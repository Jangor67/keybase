### Keybase proof

I hereby claim:

  * I am jangor67 on github.
  * I am jdegorter (https://keybase.io/jdegorter) on keybase.
  * I have a public key ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQDawmqGXaaUv6L4bG7oQHDR5HmIlPm+/bNPXpRXWdWZdrQMtMEa8VtqDz0Be2tU3zhYAHc0ANOt2FjAJKHm7QuhLBvdQMsoZjgo9VYx3D2j0tXrJ7evVkENfZM4+ehFgJKokBZUUIxYQwprMjkK695bkVAm3Bq08Q0LnJJy6kbXrPM8+mxu2po+YWs9I39a3F4yhHjabm9lhQNEqAiCzeDxthKSBVCvjILz6x80h0FjGVV7Yr0OdKj/3aZHcNje+SOPH6pbytndh/xEbPd6hMP8kG9bkTjD+6d9rArYcz6Adle2jZm6wy1Q5oPWGvmUQCy70HOYK4lPlfkVLBp2Yt6gDgcHGHhliiiGoxB4rX+v/q+ep/sw3XGS6ZF82cv0zCzZoIqxJ8polfHUXhvYviY8y310QlN+manng+UjxUk8GKALthzMUqMyAQ46xcpYWRFWYwXqnvYWgX3Ln03C7jt8KxhjOYVP/hyvUJYhpGFXAiwQPjLGWO5v4d6JExIs4Knq3f+S0kOvaKXsPWnwnO3PG3suGhUOkUV+JNGqatdXNdbfhISAZyafcLjFthnpChnbI7/KKeYoPQr/VGXaudOBxftAN1D6OD5cvf/ujVHVMl+WssriaegCcWnY3uZmeuZiRO7v24kbKpfYl9/SJNzhQwh2ZaRD8j4Ad2yfT3qMzQ==

To claim this, I am signing this object:

```json
{
  "body": {
    "key": {
      "eldest_kid": "01205d7160440a2cfdb225f24d2d201bfc0a1a351b9da933d133e815fc53fd5cef660a",
      "host": "keybase.io",
      "kid": "01205d7160440a2cfdb225f24d2d201bfc0a1a351b9da933d133e815fc53fd5cef660a",
      "uid": "68629f084a0d7b7e4dd264e986381519",
      "username": "jdegorter"
    },
    "merkle_root": {
      "ctime": 1731413132,
      "hash": "81bf46e0963e9b616f758740c6d793afc5735ccf8b1d9203769650c2ae85da8ae7da5ab70326612e2d58003564d925f27a3e0f45b345d8f82e99d663b98c496d",
      "hash_meta": "788dc052f7f37257319b16f788951678d6ddbf58e21b3b07fec78ffc4e87271e",
      "seqno": 26290926
    },
    "service": {
      "entropy": "MKtuaowPUcmhRZh2o4XDOfIZ",
      "name": "github",
      "username": "jangor67"
    },
    "type": "web_service_binding",
    "version": 2
  },
  "client": {
    "name": "keybase.io go client",
    "version": "6.4.0"
  },
  "ctime": 1731413177,
  "expire_in": 504576000,
  "prev": "5f3baffac3c92e55c8e4930e7db9942e6d7b4170f7137fb58489402095b3b31e",
  "seqno": 4,
  "tag": "signature"
}
```

signed payload is
```
0/DY1BYbpyqYk9tmPaU0AMO+Tk3v+4xqIvFEIAfWKE84ah2tQemDfl9FBGCbANJ+
56kSUDCN86DrStfVfTxnK3FHHgaMRZ6OmXuC4bc/aTtbH32GbAbh5Yp3sb956NOW
Ens4hXPEjbdTFZtdSCcyj2y7mkPc+7a5gWvq+U9mJsYuzQiRG23uudQwhuCCEqh9
ABaXeSDEaUwMDrR0MwenV9dwL+6uilfOnwFgYFg7K5DYX+olnEihunH+jjMXbWa2
/XtkUe0rGZwbEEoWwxhnLRiFcVK/xI03AvAo36T6Fc/uV9Uvk21/1b2t6frmTusl
SLwrN8eHO/dV1a2dUuRnc103chooYTS6BDKjQ5hwlTXWp2cp+iWE9bQPz1WZ17kD
im/nmcNGE+z2gXvOJSaw0DOH6cgNVBOn0o65LBiUl38ESifr8dHFuJ3Dzq7z8YVv
nIDo84nGCMndUwPkY0Ep2tsHpImaGlCueVoEL8TJOAeP7EEwwDd59cwiBfXq2ETI
pk1m4S2NJXygc5pdFjo+Pvw7usF9dAZ9xxJmWqAQEXfnkSBs5+CAng5lKsNthIHK
2p7GV5V3c0YQJd5blRIIvapgZt0GbRKXE8Nwx69rU0IKLEUqPAA5nFS3lU0rqo9G
X70lM+O5HVKz95wbIRHbh567N+Pp4va9JqEo+mqLVWw=
```

Notes about the creation of the signe payload
```
cp <private-key.ppk> <private-key.pem>
ssh-keygen -p -f <private-key.pem>  -m pem
openssl dgst -sha256 -sign <private-key.pem> -out signature.256 keybase.json
openssl base64 -in  signature.sha256 -out signature.b64
```