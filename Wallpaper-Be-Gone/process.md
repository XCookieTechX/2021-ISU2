# How to get the flag
1. Download the provided zip file and extract the file that is inside
1. Dabble around with the file itself, and you will see that it is "not the correct fie format"
1. Use an editor, i.e hexedit and find the magic number for the jpeg image
1. Note the characters that are missing because that is the password to unlock the image
1. The wrong characters are "4F2EB7EE"
1. Change them back to the correct magic number for the jpeg image
1. Use "4F2EB7EE" as the pass to extract using steghide
1. You should then get an output which is the flag "cdc{Bitter_Sweet435373u261}"
