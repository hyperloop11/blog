---
title: ws1
published: true
---

**Category: misc**
**points : 30**
Find my password from ([this recording](https://files.actf.co/66f84b04a2631daadc929b58386bb42a746ec51a4664c2eefde569ce3ece2164/recording.pcapng) :)

### [](#header-3)Solution
Downloading the file, we see that the extention is .pcapng. This gives us a clue that it is a wireshark recording.

Running the following command from the terminal:
`wireshark recording.pcapng`
Applying http filter in wireshark, we find the flag quite plainly in sight.

`flag=actf%7Bwireshark_isn%27t_so_bad_huh-a9d8g99ikdf%7`

Applying proper flag format of the contest, we get our answer.
`flag=actf{wireshark_isn%27t_so_bad_huh-a9d8g99ikdf}`

This was quite easy and straightforward problem.
