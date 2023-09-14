# Sign the CLA

This page is the step-by-step guide to signing the
Contributors License Agreement (CLA) for the open source projects
at [codeberg.org/sciss](https://codeberg.org/sciss) and [github.com/Sciss](https://github.com/Sciss). It's easy and pretty painless!
For an explanation about why I ask you to do this, see the
[CLA Rationale page](cla-rationale.md).

1. First and foremost, read [the current version of the CLA](cla-1.0.md). 
   It is written to be as close to plain English as possible.

2. Make an account on [Codeberg](https://codeberg.org) or [GitHub](https://github.com/) if you don't already have one.

3. File a pull request on _this_ project ([sciss/Contributing](https://codeberg.org/sciss/Contributing)),
   as [outlined below](#filing-the-pull-request).

4. Email me, as [outlined below](#sending-the-email).

5. Wait for me to merge your pull request. You may start
   opening pull requests for the actual project you're contributing to but I will
   only be able to merge your contributions after your signed CLA is merged.

If you wish to, you may also file the CLA in paper form. Please
see the instructions on [the paper CLA page](sign-cla-paper.md)
for details.

----------------------

## Filing the Pull Request

If you don't yet know how to file a pull request, read [GitHub's
document about it](https://help.github.com/articles/using-pull-requests).

Make your pull request be the addition of a single file to the
[contributors](contributors) directory of this project. Name the file
with the same name as your GitHub user-id, with `.md` appended to the
end. For example, for the user `Sciss`, the full path to the file
would be `contributors/Sciss.md`.

Put the following content in the file:

    [date]
    
    I hereby agree to the terms of the Contributors License
    Agreement, version 1.0, with MD5 checksum
    7dace791a47bc135c2647a7603aaf0c1.
    
    I furthermore declare that I am authorised and able to make this
    agreement and sign this declaration.
    
    Signed,
    
    [your name]
    https://codeberg.org/[your codeberg userid] or https://github.com/[your github userid]

Replace the bracketed text as follows:

- `[date]` with today's date, in the unambiguous numeric form `YYYY-MM-DD`.
- `[your name]` with your name.
- `[your codeberg userid]` with your Codeberg user-id, or `[your github userid]` with your GitHub user-id.

You can confirm the [MD5 checksum](https://en.wikipedia.org/wiki/MD5)
of the CLA by running the md5 or md5sum program over `cla-1.0.md`:

    md5sum cla-1.0.md
    7dace791a47bc135c2647a7603aaf0c1  cla-1.0.md

If the output is different from above, do not sign the CLA and let me know.

That's it!

----------------

## Sending the Email

Send an email to me
at [open-source@sciss.de](mailto:open-source@sciss.de),
with the subject "CLA" and the following body:

    I submitted a pull request to indicate agreement to the terms
    of the Contributors License Agreement.
    
    Signed,
    
    [your name]
    https://codeberg.org/[your codeberg userid] or https://github.com/[your github userid]
    [your address]

Again, replace the bracketed text as follows:

- `[your name]` with your name.
- `[your codeberg userid]` with your Codeberg user-id, or `[your github userid]` with your GitHub user-id.
- `[your address]` with a physical mailing address at which you can be contacted.

If you wish, you may send the email with PGP encryption. My public key with identifier
`0x7437FCBA03E4CB85` and fingerprint `0578 BBA1 5F19 661D 18F7 C345 7437 FCBA 03E4 CB85`
can be retrieved from [sks-keyservers.net](http://p80.pool.sks-keyservers.net/pks/lookup?op=vindex&search=0x7437FCBA03E4CB85).
