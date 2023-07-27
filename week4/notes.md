lecture link -> https://youtu.be/SPoqW1CMEhY
lecture -> https://skilstak.io/boost/2023/week4/


- Create a local Linux container fo the Boost using Podman
'''
podman run -it --hostname skilstak --name boost -v shared://shared ghcr.io/rwxrob/ws-skilstak
'''

- What is a file descriptor and how do I use them?
    Understand origins of TTY (teletype machines)
        - 
    standard input (/dev/stdin, 0)
    standard output (/dev/stdout, 1)
    standard error (/dev/stderr, 2)


- How do I find files with a keyword in the name?
    `find . -name '*vim*' 2> /dev/null`

    - `find / -name '*md*' &> /tmp/foo`
    Here's a breakdown of the command:

    - 'find': This is the command used to search for files and directories.
    - '/': It specifies the starting point of the search, which is the root directory.
    - '-name '*md*': This is an option for the 'find' command that specifies the pattern to match
    for file names. In this case, it looks for files with names containing 'md'.
    - '&>': This is a redirection operator that redirects both standard output (stdout) and
    standard error (stderr) to a file.
    - '/tmp/foo': It specifies the file '/tmp/foo' as the destination for the redirected output.
    

