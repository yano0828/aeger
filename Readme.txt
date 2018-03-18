aeger: A Japanese NLP tool to extract medical entity with its polarity judgement
Usage: aeger [options]
 -s, --standard name                    print suggested standard disease name.
 -c, --ICD10 code                       print corresponding ICD10 code.
 -h, --help                             show this help and exit.
 -v, --version                          show the version and exit.

At the prompt, enter input sentence. The 'return' is recognized as the end of sentence
The output is the input sentence with <P> and <N> tags
        <P> tag: Extracted medical entity whose polarity is judged as positive.
        <N> tag: Extracted medical entity whose polarity is judged as negative.
