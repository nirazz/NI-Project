This program reads from a file invoice numbers represented using 7-segments-display digits. The numbers are being parsed to the actual value.

logic:

- split by linefeed '\n'
- build an array with single ASCII digits
- join a single ASCII digit to a string
- map the ASCII value
- join the result to a string
