# Deciphers

You will now need to decipher the message in the file `answer.text` with command line.

# Translating & mapping characters

It's rather uncommon but this is a fair bonus fact for Linux.

We can use `tr` to map characters and rotate them around to get various output.

In this case, we lose the number to rotate characters, so here are all possible rotations that we can make.

```
ROT-3 = tr 'd-za-cD-ZA-C' 'a-zA-Z'
ROT-4 = tr 'e-za-dE-ZA-D' 'a-zA-Z'
ROT-5 = tr 'f-za-eF-ZA-E' 'a-zA-Z'
ROT-6 = tr 'g-za-fG-ZA-F' 'a-zA-Z'
ROT-7 = tr 'h-za-gH-ZA-G' 'a-zA-Z'
ROT-8 = tr 'i-za-hI-ZA-H' 'a-zA-Z'
ROT-9 = tr 'j-za-iJ-ZA-I' 'a-zA-Z'
ROT-10 = tr 'k-za-jK-ZA-J' 'a-zA-Z'
ROT-11 = tr 'l-za-kL-ZA-K' 'a-zA-Z'
ROT-12 = tr 'm-za-lM-ZA-L' 'a-zA-Z'
ROT-13 = tr 'n-za-mN-ZA-M' 'a-zA-Z'
ROT-14 = tr 'o-za-nO-ZA-N' 'a-zA-Z'
ROT-15 = tr 'p-za-oP-ZA-O' 'a-zA-Z'
ROT-16 = tr 'q-za-pQ-ZA-P' 'a-zA-Z'
ROT-17 = tr 'r-za-qR-ZA-Q' 'a-zA-Z'
ROT-18 = tr 's-za-rS-ZA-R' 'a-zA-Z'
ROT-19 = tr 't-za-sT-ZA-S' 'a-zA-Z'
ROT-20 = tr 'u-za-tU-ZA-T' 'a-zA-Z'
ROT-21 = tr 'v-za-uV-ZA-U' 'a-zA-Z'
ROT-22 = tr 'w-za-vW-ZA-V' 'a-zA-Z'
ROT-23 = tr 'x-za-wX-ZA-W' 'a-zA-Z'
ROT-24 = tr 'y-za-xY-ZA-X' 'a-zA-Z'
ROT-25 = tr 'z-za-yZ-ZA-Y' 'a-zA-Z'
```

We can use `cat` and pipe the output to `tr`!

```sh
cat answer.txt | tr
```
