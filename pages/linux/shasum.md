# shasum

> Print or Check SHA Checksums. The shasum script provides the easiest and most convenient way to compute SHA message digests. Rather than writing a program, the user simply feeds data to the script via the command line, and waits for the results to be printed on standard output. Data can be fed to shasum through files, standard input, or both.

- Calculate the sha-256 checksum for example.txt:

`$ shasum -a 256 example.txt`

- Or using an alias:

`$ alias sha256='shasum -a 256'`
