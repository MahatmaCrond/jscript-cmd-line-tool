# Jscript-Decrypt-for-MacOS
Port of a tool used to decode MS JScript. Useful for some Malware reverse engineering or random decoding of obfuscated Javascript. I did the port of this tool to MacOS, I didn't write the original implementation. 

Credit goes to: MrBrownstone, mrbrownstone@virtualconspiracy.com



------------------

<b>Usage (single command line): </b>
<br />

./srcdec < infile > < outfile > < -urldec | -htmldec > < -verbose > < -dumb >

<b>Options:</b>
<br />
Use -urldec to unescape %xx style encoding on the fly, or -htmldec to unescape & style encoding.

Use -dumb to bypass HTMLGuardian defeation mechanism.

Use -verbose for verbose output.

Hit enter. Then check the < outfile > you set. 

Simple app.
