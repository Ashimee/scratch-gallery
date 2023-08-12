# Contributing
First I recommend you read https://github.com/TurboWarp/extensions/blob/master/CONTRIBUTING.md

I will go over some rules I am going to change.

# Strictly, banned/fine.
## but the following are highly discouraged:
 * Broad "Utilities" extensions (THESE ARE OK)
 * Extensions that are very similar to existing ones (consider modifying the existing one instead)
 * One-use personal extensions (load the extension as a local file instead)

# Banned APIs
(subject to change)

    eval()
    new Function()
    untrusted or remote <script> or <iframe>
    other arbitrary JS/CSS/HTML evaluation

# License
## We are not lawyers. This is not legal advice.
All extensions that you submit to this gallery must be MIT.

# Code style
Try to keep it concurrent with the turbowarp style and my extensions.

# Linting and Type Checking
Keep it the same as turbowarp.
