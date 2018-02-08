# Trusting the man in the middle

Software development in a corporate environment can be trying at times. Many corporate environments have a 'Man in the middle' watching all the encrypted traffic as it flows, you know for security. For our browsers this usualy works without a problem. But for your development tools, those corporate certificates cause problems.

There are ways to solve these problems. I'll show you how to trust the man in the middle so that as you use npm, r, go, ruby, and python you can avoid the 'SSL connection refused, untrusted certificate' error; on Windows and Linux.
